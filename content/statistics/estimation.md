## 🎲 Why the Standard Error Changes with Randomization

### Case 1: No Randomization (Honest Answers)

- If people answer truthfully, the number of "Yes" responses ~ Binomial(n, p)
- The estimator of p is:  
  p̂ = Y / n  
- Variance of p̂:  
  Var(p̂) = p(1 - p) / n  
- So the standard error (SE) is:  
  SE (usual) = sqrt[ p(1 - p) / n ]

---

```handdrawn-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Drawing/2025.4.20 - 18.57pm.drawing",
	"width": 500,
	"aspectRatio": 1
}
```

### Case 2: With Randomization

- From earlier derivations:  
  P(Yes response) = (1 + p) / 2  
- So the number of Yes answers ~ Binomial(n, (1 + p)/2)
- The estimator becomes:  
  p̂ = 2 * (Z / n) - 1  
- Variance of p̂:  
  Var(p̂) = 4 * Var(Z/n) = 4 * [(1 + p)(1 - p) / (4n)] = (1 - p²)/n  
- So standard error is:  
  SE (randomized) = sqrt[ (1 - p²) / n ] = sqrt[ (1 + p)(1 - p) / n ]

---

### Ratio of Standard Errors

Ratio = SE (randomized) / SE (usual)  
       = sqrt[ (1 + p)(1 - p) / n ] / sqrt[ p(1 - p) / n ]  
       = sqrt[ (1 + p) / p ]

This ratio shows the "cost" of using randomization — i.e., how much extra variability you introduce to protect privacy.

---

## (a) Do you think this price is higher for large or small values of p?

Look at the expression:

    Ratio = sqrt[(1 + p) / p] = sqrt[1/p + 1]

- When p is small (e.g., 0.1), 1/p is large → the ratio is large.
- When p is large (e.g., 0.9), 1/p is small → the ratio is smaller.

✅ So the "price" (ratio) is higher when p is small. That is, randomization adds more noise when the behavior is rare.

---

## (b) Compute the ratio for p = 0.1, 0.5, 0.9

- For p = 0.1:  
  Ratio = sqrt[(1 + 0.1)/0.1] = sqrt[11] ≈ 3.317

- For p = 0.5:  
  Ratio = sqrt[(1 + 0.5)/0.5] = sqrt[3] ≈ 1.732

- For p = 0.9:  
  Ratio = sqrt[(1 + 0.9)/0.9] = sqrt[2.111] ≈ 1.453

---

### Summary Table

| p     | Ratio sqrt[(1 + p)/p] | Interpretation                 |
|-------|------------------------|--------------------------------|
| 0.1   | 3.317                  | High cost (rare behavior)      |
| 0.5   | 1.732                  | Moderate cost                  |
| 0.9   | 1.453                  | Lower cost (common behavior)   |

---

**Conclusion**:  
Randomization adds uncertainty to preserve privacy. This uncertainty is a bigger problem when the true proportion (p) is small.
