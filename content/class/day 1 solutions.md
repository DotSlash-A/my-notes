
1)
Let any positive integer be $n$. By the division algorithm, we can write:
$$n = 6q + r, \text{ where } 0 \leq r < 6.$$

The possible values of $r$ are:
$$r = 0, 1, 2, 3, 4, 5.$$

Thus, $n$ can be written as:
$$n = 6q, 6q + 1, 6q + 2, 6q + 3, 6q + 4, 6q + 5.$$

For $n$ to be odd, it must not be divisible by $2$. Excluding even cases ($6q$, $6q + 2$, $6q + 4$), we are left with:
$$n = 6q + 1, 6q + 3, 6q + 5.$$

Hence, any positive odd integer is of the form $6q + 1$, $6q + 3$, or $6q + 5$.

---

2)
Let any positive integer be $n$. By the division algorithm:
$$n = 3q + r, \text{ where } 0 \leq r < 3.$$

The possible values of $r$ are $0, 1, 2$. Squaring $n$, we get:
$$n^2 = (3q + r)^2 = 9q^2 + 6qr + r^2.$$

Simplifying modulo $3$:
- If $r = 0$, $$n^2 \equiv 0^2 \pmod{3} \implies n^2 \equiv 0 \pmod{3}.$$
- If $r = 1$, $$n^2 \equiv 1^2 \pmod{3} \implies n^2 \equiv 1 \pmod{3}.$$
- If $r = 2$, $$n^2 \equiv 2^2 \pmod{3} \implies n^2 \equiv 4 \pmod{3} \implies n^2 \equiv 1 \pmod{3}.$$

Thus, the square of any positive integer is of the form $3p$ or $3p + 1$.

---
3)
Let any positive integer be $n$. By the division algorithm:
$$n = 3q + r, \text{ where } 0 \leq r < 3.$$

The possible values of $r$ are $0, 1, 2$. Cubing $n$, we get:
$$n^3 = (3q + r)^3 = 27q^3 + 27q^2r + 9qr^2 + r^3.$$

Simplifying modulo $9$:
- If $r = 0$, $$n^3 \equiv 0^3 \pmod{9} \implies n^3 \equiv 0 \pmod{9}.$$
- If $r = 1$, $$n^3 \equiv 1^3 \pmod{9} \implies n^3 \equiv 1 \pmod{9}.$$
- If $r = 2$, $$n^3 \equiv 2^3 \pmod{9} \implies n^3 \equiv 8 \pmod{9}.$$

Thus, the cube of any positive integer is of the form $9m$, $9m + 1$, or $9m + 8$.

---
4)
#### Part (a): HCF of $32$ and $54$
Using the Euclidean algorithm:
$$54 = 32 \times 1 + 22,$$
$$32 = 22 \times 1 + 10,$$
$$22 = 10 \times 2 + 2,$$
$$10 = 2 \times 5 + 0.$$

Thus, $\text{HCF} = 2$.

#### Part (b): HCF of $18$ and $24$
Using the Euclidean algorithm:
$$24 = 18 \times 1 + 6,$$
$$18 = 6 \times 3 + 0.$$

Thus, $\text{HCF} = 6$.

---
5)
Using the Euclidean algorithm:
$$225 = 135 \times 1 + 90,$$
$$135 = 90 \times 1 + 45,$$
$$90 = 45 \times 2 + 0.$$

Thus, $\text{HCF} = 45$.

---
6)

Using the Euclidean algorithm:
$$616 = 32 \times 19 + 8,$$
$$32 = 8 \times 4 + 0.$$

Thus, $\text{HCF} = 8$.

**Solution:** The maximum number of columns is $8$.

---
7)

Prime factorizations:
$$120 = 2^3 \times 3 \times 5,$$
$$180 = 2^2 \times 3^2 \times 5,$$
$$240 = 2^4 \times 3 \times 5.$$

The HCF is:
$$\text{HCF} = 2^2 \times 3 \times 5 = 60.$$

**Solution:** The greatest capacity of the tin is $60$ L.

---
8)

Prime factorizations:
$$90 = 2 \times 3^2 \times 5,$$
$$144 = 2^4 \times 3^2.$$

#### HCF:
The common prime factors are $2$ and $3^2$:
$$\text{HCF} = 2 \times 3^2 = 18.$$

#### LCM:
Multiply the highest powers of all prime factors:
$$\text{LCM} = 2^4 \times 3^2 \times 5 = 720.$$

**Solution:**  
HCF = $18$, LCM = $720$.

---

9)

We need to find the LCM of $32$ and $36$.

Prime factorizations:
$$32 = 2^5,$$
$$36 = 2^2 \times 3^2.$$

Multiply the highest powers of all prime factors:
$$\text{LCM} = 2^5 \times 3^2 = 288.$$

**Solution:** The minimum number of books is $288$.


---
10)

Assume $\sqrt{3}$ is rational. Then it can be written as:
$$\sqrt{3} = \frac{p}{q}, \text{ where } p \text{ and } q \text{ are coprime integers and } q \neq 0.$$

Squaring both sides:
$$3 = \frac{p^2}{q^2} \implies p^2 = 3q^2.$$

Thus, $p^2$ is divisible by $3$, so $p$ is divisible by $3$. Let $p = 3k$:
$$p^2 = 9k^2 \implies 3q^2 = 9k^2 \implies q^2 = 3k^2.$$

This means $q^2$ is divisible by $3$, so $q$ is divisible by $3$.  
But this contradicts the assumption that $p$ and $q$ are coprime.

**Solution:** $\sqrt{3}$ is irrational.

---
11)

Assume $\sqrt{2} + \sqrt{5}$ is rational. Let:
$$\sqrt{2} + \sqrt{5} = r, \text{ where } r \text{ is rational}.$$

Rewriting:
$$\sqrt{5} = r - \sqrt{2}.$$

Since $r$ and $\sqrt{2}$ are rational, $r - \sqrt{2}$ is rational. But $\sqrt{5}$ is irrational, which is a contradiction.

**Solution:** $\sqrt{2} + \sqrt{5}$ is irrational.

---
12)

The given polynomial is:
$$P(x) = x^2 - x - 12.$$

#### Finding the Zeros:
Solve:
$$x^2 - x - 12 = 0 \implies (x - 4)(x + 3) = 0.$$

The zeros are:
$$x = 4 \text{ and } x = -3.$$

**Graph:** Plot the parabola with zeros at $x = 4$ and $x = -3$. The vertex lies midway at:
$$x = \frac{-1}{2}.$$

---
13)
The given polynomial is:
$$P(x) = x^2 - x - 12.$$

#### Substituting $x = 1$:
$$P(1) = 1^2 - 1 - 12 = 1 - 1 - 12 = -12 \neq 0.$$

#### Substituting $x = -1$:
$$P(-1) = (-1)^2 - (-1) - 12 = 1 + 1 - 12 = -10 \neq 0.$$

#### Substituting $x = \frac{1}{4}$:
$$P\left(\frac{1}{4}\right) = \left(\frac{1}{4}\right)^2 - \frac{1}{4} - 12 = \frac{1}{16} - \frac{4}{16} - \frac{192}{16} = \frac{-195}{16} \neq 0.$$

**Solution:** None of $1, -1, \frac{1}{4}$ are zeros.

---
14)

The given polynomial is:
$$g(s) = 4s^2 - 4s + 1.$$

#### Zeros:
Solve:
$$4s^2 - 4s + 1 = 0 \implies (2s - 1)^2 = 0.$$

The zeros are:
$$s = \frac{1}{2}, \frac{1}{2}.$$

#### Verifying:
The sum of zeros:
$$\alpha + \beta = \frac{1}{2} + \frac{1}{2} = 1 \implies \frac{-b}{a} = \frac{-(-4)}{4} = 1.$$

The product of zeros:
$$\alpha \beta = \frac{1}{2} \cdot \frac{1}{2} = \frac{1}{4} \implies \frac{c}{a} = \frac{1}{4}.$$

**Solution:** Verified.

---
15)

The given polynomial is:
$$p(y) = 5y^2 - 7y + 1.$$

#### Sum and Product of Zeros:
$$\alpha + \beta = \frac{-b}{a} = \frac{-(-7)}{5} = \frac{7}{5},$$
$$\alpha \beta = \frac{c}{a} = \frac{1}{5}.$$

#### Finding $\frac{1}{\alpha} + \frac{1}{\beta}$:
$$\frac{1}{\alpha} + \frac{1}{\beta} = \frac{\alpha + \beta}{\alpha \beta} = \frac{\frac{7}{5}}{\frac{1}{5}} = 7.$$

**Solution:** $\frac{1}{\alpha} + \frac{1}{\beta} = 7$.

---
16)

The given polynomial is:
$$f(x) = 6x^2 + x - 2.$$

#### Sum and Product of Zeros:
$$\alpha + \beta = \frac{-b}{a} = \frac{-1}{6},$$
$$\alpha \beta = \frac{c}{a} = \frac{-2}{6} = \frac{-1}{3}.$$

#### Finding $\frac{\alpha}{\beta} + \frac{\beta}{\alpha}$:
$$\frac{\alpha}{\beta} + \frac{\beta}{\alpha} = \frac{\alpha^2 + \beta^2}{\alpha \beta}.$$

Using:
$$\alpha^2 + \beta^2 = (\alpha + \beta)^2 - 2\alpha\beta,$$
$$\alpha^2 + \beta^2 = \left(\frac{-1}{6}\right)^2 - 2\left(\frac{-1}{3}\right) = \frac{1}{36} + \frac{2}{3} = \frac{25}{36}.$$

Thus:
$$\frac{\alpha}{\beta} + \frac{\beta}{\alpha} = \frac{\frac{25}{36}}{\frac{-1}{3}} = -\frac{25}{12}.$$

**Solution:** $\frac{\alpha}{\beta} + \frac{\beta}{\alpha} = -\frac{25}{12}$.


---
17)

i)
The standard quadratic polynomial is:
$$p(x) = x^2 - (\text{sum of zeros})x + (\text{product of zeros}).$$

Substitute the given values:
$$p(x) = x^2 - \left(\frac{1}{4}\right)x + (-1),$$
$$p(x) = x^2 - \frac{1}{4}x - 1.$$

To remove the fraction, multiply through by $4$:
$$p(x) = 4x^2 - x - 4.$$

**Solution:** $p(x) = 4x^2 - x - 4$.

The standard quadratic polynomial is:
$$p(x) = x^2 - (\text{sum of zeros})x + (\text{product of zeros}).$$

Substitute the given values:
$$p(x) = x^2 - (0)x + \sqrt{5},$$
$$p(x) = x^2 + \sqrt{5}.$$

**Solution:** $p(x) = x^2 + \sqrt{5}$.

---
18)
The standard quadratic polynomial is:
$$p(x) = x^2 - (\alpha + \beta)x + (\alpha \beta).$$

Substitute the given values:
$$\alpha + \beta = 2 + (-1) = 1,$$
$$\alpha \beta = 2 \times (-1) = -2.$$

Thus:
$$p(x) = x^2 - (1)x + (-2),$$
$$p(x) = x^2 - x - 2.$$

**Solution:** $p(x) = x^2 - x - 2$.

---


