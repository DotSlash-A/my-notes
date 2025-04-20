Okay, babe! Let's get this Complex Numbers class planned out perfectly. You'll ace this! We'll cover everything from the ground up, making sure your students get a solid understanding. We'll structure it nicely so you can easily study and deliver it.

Here’s a plan drawing inspiration from NCERT (foundational concepts), RD Sharma (variety and depth), and Telugu Academy (often good for additional examples and rigor).

**Class Plan: Complex Numbers (Class 11th & 12th)**

**Overall Goal:** To introduce students to the concept of complex numbers, their algebra, geometric representation, and key theorems like De Moivre's, enabling them to solve problems involving complex numbers.

**Books Referenced (Mentally):** NCERT (Chapter 5, Class 11), RD Sharma (Vol 1, relevant chapters), Telugu Academy (Intermediate Maths IIA/relevant sections).

**Today's Agenda:**

1.  **Introduction & Motivation (Why Complex Numbers?)**
    *   The need for `i` (iota).
    *   Definition of a complex number (`a + ib`).
    *   Real and Imaginary Parts.
    *   Equality of Complex Numbers.
2.  **Algebra of Complex Numbers**
    *   Addition, Subtraction, Multiplication.
    *   Properties (Closure, Commutative, Associative, Identity, Inverse).
    *   Powers of `i`.
    *   Division of Complex Numbers.
    *   Identities.
3.  **Modulus and Conjugate**
    *   Definition and Geometric Meaning.
    *   Properties of Modulus.
    *   Properties of Conjugate.
    *   Relationship: `z * z̄ = |z|²`.
4.  **Argand Plane and Polar Representation**
    *   Geometric Representation (Argand Diagram).
    *   Polar Form: `r(cos θ + i sin θ)`.
    *   Modulus (`r`) and Argument (`θ`).
    *   Principal Argument.
    *   Euler's Form: `re^(iθ)` (Brief mention/connection).
5.  **Square Root of a Complex Number**
    *   Method to find `√(a + ib)`.
6.  **Quadratic Equations with Complex Roots**
    *   Using the quadratic formula when `D < 0`.

**(Optional - Depending on Time/Level - Can be next class)**

7.  **De Moivre's Theorem**
    *   Statement (for integer index).
    *   Applications (finding powers).
8.  **Cube Roots of Unity**
    *   Finding the roots (`1, ω, ω²`).
    *   Properties (`ω³ = 1`, `1 + ω + ω² = 0`).
    *   Applications.

---

**Let's Dive In!**

**1. Introduction & Motivation**

*   **Theory:**
    *   Start by asking: What is the solution to `x² - 1 = 0`? (Answer: `x = ±1`).
    *   Now ask: What is the solution to `x² + 1 = 0`? (Leads to `x² = -1`). Within the real number system, there's no solution.
    *   Mathematicians introduced the imaginary unit `i` (iota), defined as `i = √(-1)`, such that `i² = -1`.
    *   This allows us to define **Complex Numbers**. A number of the form `z = a + ib`, where `a` and `b` are real numbers, is called a complex number.
    *   `a` is called the **Real part** of `z`, denoted as `Re(z)`.
    *   `b` is called the **Imaginary part** of `z`, denoted as `Im(z)`.
    *   Examples: `3 + 2i` (Re=3, Im=2), `-5i` (Re=0, Im=-5), `7` (Re=7, Im=0).
    *   A complex number is purely real if `Im(z) = 0`.
    *   A complex number is purely imaginary if `Re(z) = 0`.
    *   **Equality:** Two complex numbers `z₁ = a + ib` and `z₂ = c + id` are equal (`z₁ = z₂`) if and only if `a = c` and `b = d`. (Real parts are equal AND imaginary parts are equal).

*   **Problems & Solutions:**

    1.  **Problem:** Find the real and imaginary parts of `z = -√3 + √(-7)`.
        *   **Solution:** `z = -√3 + √(-1 * 7) = -√3 + √(-1) * √7 = -√3 + i√7`.
            *   `Re(z) = -√3`
            *   `Im(z) = √7`

    2.  **Problem:** If `(2x - 1) + i(y + 3) = 5 - 2i`, find the real values of `x` and `y`.
        *   **Solution:** Equating the real and imaginary parts:
            *   `2x - 1 = 5`  => `2x = 6` => `x = 3`
            *   `y + 3 = -2` => `y = -5`
            *   So, `x = 3` and `y = -5`.

**2. Algebra of Complex Numbers**

*   **Theory:**
    *   Let `z₁ = a + ib` and `z₂ = c + id`.
    *   **Addition:** `z₁ + z₂ = (a + c) + i(b + d)` (Add real parts, add imaginary parts).
    *   **Subtraction:** `z₁ - z₂ = (a - c) + i(b - d)` (Subtract real parts, subtract imaginary parts).
    *   **Multiplication:** `z₁ * z₂ = (a + ib)(c + id) = ac + iad + ibc + i²bd = (ac - bd) + i(ad + bc)` (Multiply like binomials, remember `i² = -1`).
    *   **Properties:** Addition and Multiplication are:
        *   *Closure:* Sum/Product of two complex numbers is a complex number.
        *   *Commutative:* `z₁ + z₂ = z₂ + z₁`, `z₁ * z₂ = z₂ * z₁`.
        *   *Associative:* `(z₁ + z₂) + z₃ = z₁ + (z₂ + z₃)`, `(z₁ * z₂) * z₃ = z₁ * (z₂ * z₃)`.
        *   *Additive Identity:* `0 = 0 + i0` such that `z + 0 = z`.
        *   *Multiplicative Identity:* `1 = 1 + i0` such that `z * 1 = z`.
        *   *Additive Inverse:* For `z = a + ib`, the inverse is `-z = -a - ib` such that `z + (-z) = 0`.
        *   *Multiplicative Inverse:* For `z = a + ib` (where `z ≠ 0`), the inverse `z⁻¹` or `1/z` exists. (We'll see how to calculate it using the conjugate later).
        *   *Distributive Law:* `z₁(z₂ + z₃) = z₁z₂ + z₁z₃`.
    *   **Powers of `i`:**
        *   `i⁰ = 1`
        *   `i¹ = i`
        *   `i² = -1`
        *   `i³ = i² * i = -i`
        *   `i⁴ = i² * i² = (-1)(-1) = 1`
        *   The pattern repeats every 4 powers: `i^n = i^(4k+r) = (i⁴)^k * i^r = 1^k * i^r = i^r`, where `r` is the remainder when `n` is divided by 4 (`r = 0, 1, 2, 3`).
        *   Also useful: `1/i = i³/i⁴ = i³ = -i`. Or `1/i = (1 * -i) / (i * -i) = -i / -i² = -i / 1 = -i`.
    *   **Division:** To divide `z₁ / z₂`, multiply the numerator and denominator by the conjugate of the denominator (explained in the next section). `z₁ / z₂ = z₁ * (1/z₂)`.
    *   **Identities:** Standard algebraic identities hold, e.g.,
        *   `(z₁ + z₂)² = z₁² + 2z₁z₂ + z₂²`
        *   `(z₁ - z₂)² = z₁² - 2z₁z₂ + z₂²`
        *   `z₁² - z₂² = (z₁ - z₂)(z₁ + z₂)`

*   **Problems & Solutions:**

    1.  **Problem:** Express `(5 - 3i)( -2 + i)` in the form `a + ib`.
        *   **Solution:** `(5 - 3i)(-2 + i) = 5(-2) + 5(i) + (-3i)(-2) + (-3i)(i)`
            *   `= -10 + 5i + 6i - 3i²`
            *   `= -10 + 11i - 3(-1)`
            *   `= -10 + 11i + 3`
            *   `= -7 + 11i`

    2.  **Problem:** Evaluate `i^39`.
        *   **Solution:** Divide 39 by 4: `39 = 4 * 9 + 3`. The remainder is 3.
            *   So, `i^39 = i³ = -i`.

    3.  **Problem:** Evaluate `i⁻⁹⁹⁹`.
        *   **Solution:** `i⁻⁹⁹⁹ = 1 / i⁹⁹⁹`.
            *   Divide 999 by 4: `999 = 4 * 249 + 3`. Remainder is 3.
            *   `i⁹⁹⁹ = i³ = -i`.
            *   So, `i⁻⁹⁹⁹ = 1 / (-i)`. Multiply numerator and denominator by `i`:
            *   `= (1 * i) / (-i * i) = i / (-i²) = i / (-(-1)) = i / 1 = i`.

    4.  **Problem:** Find the value of `1 + i² + i⁴ + i⁶ + ... + i²⁰`.
        *   **Solution:** `1 + i² + i⁴ + i⁶ + ... + i²⁰ = 1 + (-1) + (i²)² + (i²)³ + ... + (i²)¹⁰`
            *   `= 1 - 1 + (-1)² + (-1)³ + ... + (-1)¹⁰`
            *   `= 1 - 1 + 1 - 1 + 1 - 1 + ... + 1`
            *   There are 11 terms (from `i⁰` to `i²⁰`).
            *   `(1-1) + (1-1) + ... + (1-1) + 1` (5 pairs cancelling out, plus the last term `i²⁰ = (i⁴)⁵ = 1⁵ = 1`).
            *   Alternatively, it's a Geometric Progression: `a = 1`, `r = i² = -1`, `n = 11` terms.
            *   Sum `S_n = a(1 - r^n) / (1 - r) = 1 * (1 - (-1)¹¹) / (1 - (-1))`
            *   `= (1 - (-1)) / (1 + 1) = (1 + 1) / 2 = 2 / 2 = 1`.

**3. Modulus and Conjugate**

*   **Theory:**
    *   Let `z = a + ib`.
    *   **Conjugate:** The conjugate of `z` is `z̄ = a - ib`. (Change the sign of the imaginary part).
        *   Example: If `z = 3 + 4i`, then `z̄ = 3 - 4i`. If `z = -2 - i`, then `z̄ = -2 + i`. If `z = 5i`, `z̄ = -5i`. If `z = 7`, `z̄ = 7`.
    *   **Modulus:** The modulus of `z` is `|z| = √(a² + b²)`. It represents the distance of the point `(a, b)` from the origin in the Argand plane. Modulus is always a non-negative real number.
        *   Example: If `z = 3 + 4i`, then `|z| = √(3² + 4²) = √(9 + 16) = √25 = 5`.
    *   **Properties of Conjugate:**
        *   `overline(z̄) = z`
        *   `z + z̄ = 2 Re(z)`
        *   `z - z̄ = 2i Im(z)`
        *   `z = z̄` <=> `z` is purely real.
        *   `z = -z̄` <=> `z` is purely imaginary (or zero).
        *   `overline(z₁ + z₂) = z̄₁ + z̄₂`
        *   `overline(z₁ - z₂) = z̄₁ - z̄₂`
        *   `overline(z₁ * z₂) = z̄₁ * z̄₂`
        *   `overline(z₁ / z₂) = z̄₁ / z̄₂` (provided `z₂ ≠ 0`)
    *   **Properties of Modulus:**
        *   `|z| = 0` <=> `z = 0`
        *   `|z| = |z̄| = |-z| = |-z̄|`
        *   `-|z| ≤ Re(z) ≤ |z|` and `-|z| ≤ Im(z) ≤ |z|`
        *   `z * z̄ = |z|²`  (VERY IMPORTANT: `(a + ib)(a - ib) = a² - (ib)² = a² - i²b² = a² + b²`)
        *   `|z₁ * z₂| = |z₁| * |z₂|`
        *   `|z₁ / z₂| = |z₁| / |z₂|` (provided `z₂ ≠ 0`)
        *   `|z₁ + z₂| ≤ |z₁| + |z₂|` (Triangle Inequality)
        *   `|z₁ - z₂| ≥ ||z₁| - |z₂||`
        *   `|zⁿ| = |z|ⁿ`
    *   **Multiplicative Inverse using Conjugate:**
        *   `z⁻¹ = 1/z = (1 * z̄) / (z * z̄) = z̄ / |z|²`.
        *   For `z = a + ib`, `z⁻¹ = (a - ib) / (a² + b²)`.

*   **Problems & Solutions:**

    1.  **Problem:** Find the modulus and conjugate of `z = -1 - i√3`.
        *   **Solution:**
            *   Conjugate: `z̄ = -1 + i√3`.
            *   Modulus: `|z| = √((-1)² + (-√3)²) = √(1 + 3) = √4 = 2`.

    2.  **Problem:** Find the multiplicative inverse of `z = 2 - 3i`.
        *   **Solution:**
            *   Method 1: Using formula `z⁻¹ = z̄ / |z|²`.
                *   `z̄ = 2 + 3i`
                *   `|z|² = 2² + (-3)² = 4 + 9 = 13`
                *   `z⁻¹ = (2 + 3i) / 13 = (2/13) + i(3/13)`.
            *   Method 2: `1 / (2 - 3i)`
                *   `= (1 * (2 + 3i)) / ((2 - 3i)(2 + 3i))`
                *   `= (2 + 3i) / (2² - (3i)²) = (2 + 3i) / (4 - 9i²) = (2 + 3i) / (4 - 9(-1))`
                *   `= (2 + 3i) / (4 + 9) = (2 + 3i) / 13 = (2/13) + i(3/13)`.

    3.  **Problem:** Express `(3 + i√5)(3 - i√5) / ((√3 + √2i) - (√3 - i√2))` in the form `a + ib`. (Similar to NCERT Ex 5.1, Q14)
        *   **Solution:**
            *   Numerator: `(3 + i√5)(3 - i√5)` is in the form `(a+ib)(a-ib) = a² + b²`.
                *   `= 3² + (√5)² = 9 + 5 = 14`.
            *   Denominator: `(√3 + √2i) - (√3 - i√2) = √3 + √2i - √3 + i√2`
                *   `= (√3 - √3) + i(√2 + √2) = 0 + i(2√2) = 2√2 i`.
            *   Fraction: `14 / (2√2 i) = 7 / (√2 i)`.
            *   Multiply numerator and denominator by `i` (or `-i`):
                *   `= (7 * i) / (√2 i * i) = 7i / (√2 i²) = 7i / (√2 * -1) = -7i / √2`.
                *   Rationalize: `= (-7i * √2) / (√2 * √2) = -7√2 i / 2`.
            *   In `a + ib` form: `0 + i(-7√2 / 2)`.
            *   So, `a = 0`, `b = -7√2 / 2`.

    4.  **Problem:** If `(x + iy)³ = u + iv`, show that `u/x + v/y = 4(x² - y²)`. (Inspired by RD Sharma)
        *   **Solution:** Expand `(x + iy)³`:
            *   `(x + iy)³ = x³ + 3(x²)(iy) + 3(x)(iy)² + (iy)³`
            *   `= x³ + 3ix²y + 3x(i²y²) + i³y³`
            *   `= x³ + 3ix²y - 3xy² - iy³` (since `i²=-1`, `i³=-i`)
            *   `= (x³ - 3xy²) + i(3x²y - y³)`
            *   We are given `(x + iy)³ = u + iv`. Equating real and imaginary parts:
                *   `u = x³ - 3xy² = x(x² - 3y²)`
                *   `v = 3x²y - y³ = y(3x² - y²)`
            *   From these, `u/x = x² - 3y²` and `v/y = 3x² - y²`.
            *   Therefore, `u/x + v/y = (x² - 3y²) + (3x² - y²)`
            *   `= 4x² - 4y² = 4(x² - y²)`. Hence shown.

**4. Argand Plane and Polar Representation**

*   **Theory:**
    *   **Argand Plane (or Complex Plane):** A two-dimensional plane where complex numbers `z = a + ib` are represented by the point `P(a, b)`. The horizontal axis is the **Real axis**, and the vertical axis is the **Imaginary axis**.
    *   A complex number `z` can also be viewed as a vector `OP` from the origin `O` to the point `P(a, b)`.
    *   **Polar Form (Modulus-Argument Form):** Instead of Cartesian coordinates `(a, b)`, we can use polar coordinates `(r, θ)`.
        *   `r`: The distance from the origin `O` to the point `P`. This is simply the modulus `|z|`. So, `r = |z| = √(a² + b²)`. (`r ≥ 0`).
        *   `θ`: The angle made by the line segment `OP` with the positive direction of the real axis (measured counterclockwise). This is called the **Argument** or **Amplitude** of `z`, denoted as `arg(z)`.
        *   From trigonometry in the right triangle formed by `(0,0), (a,0), (a,b)`:
            *   `a = r cos θ`
            *   `b = r sin θ`
        *   Therefore, `z = a + ib = r cos θ + i (r sin θ) = r(cos θ + i sin θ)`. This is the **Polar Form**.
    *   **Finding the Argument (`θ`):**
        *   From `a = r cos θ` and `b = r sin θ`, we have `tan α = |b/a|`, where `α` is the acute angle.
        *   Determine the quadrant in which the point `(a, b)` lies:
            *   Quadrant I (`a>0, b>0`): `θ = α`
            *   Quadrant II (`a<0, b>0`): `θ = π - α`
            *   Quadrant III (`a<0, b<0`): `θ = π + α` or `θ = -(π - α)`
            *   Quadrant IV (`a>0, b<0`): `θ = 2π - α` or `θ = -α`
    *   **Principal Argument:** The unique value of the argument `θ` such that `-π < θ ≤ π`.
        *   Finding Principal Argument:
            *   Calculate `α = tan⁻¹|b/a|` (the acute angle).
            *   Quadrant I (`a>0, b>0`): `θ = α`
            *   Quadrant II (`a<0, b>0`): `θ = π - α`
            *   Quadrant III (`a<0, b<0`): `θ = -(π - α) = α - π`
            *   Quadrant IV (`a>0, b<0`): `θ = -α`
        *   Special Cases:
            *   If `z` is positive real (`a>0, b=0`), `θ = 0`.
            *   If `z` is negative real (`a<0, b=0`), `θ = π`.
            *   If `z` is positive imaginary (`a=0, b>0`), `θ = π/2`.
            *   If `z` is negative imaginary (`a=0, b<0`), `θ = -π/2`.
    *   **Euler's Form:** `e^(iθ) = cos θ + i sin θ`. So, the polar form can be written compactly as `z = r e^(iθ)`. (Useful for De Moivre's).

*   **Problems & Solutions:**

    1.  **Problem:** Represent the complex number `z = 1 + i√3` in the polar form. (NCERT Ex 5.2, Q3)
        *   **Solution:**
            *   `z = 1 + i√3`. Here `a = 1`, `b = √3`.
            *   Find `r`: `r = |z| = √(1² + (√3)²) = √(1 + 3) = √4 = 2`.
            *   Find `θ`: The point `(1, √3)` is in Quadrant I.
                *   `tan α = |b/a| = |√3 / 1| = √3`.
                *   The acute angle `α` such that `tan α = √3` is `α = π/3`.
                *   Since it's Quadrant I, `θ = α = π/3`.
            *   Polar Form: `z = r(cos θ + i sin θ) = 2(cos(π/3) + i sin(π/3))`.

    2.  **Problem:** Convert the complex number `z = -1 - i` into polar form. Find the principal argument.
        *   **Solution:**
            *   `z = -1 - i`. Here `a = -1`, `b = -1`.
            *   Find `r`: `r = |z| = √((-1)² + (-1)²) = √(1 + 1) = √2`.
            *   Find `θ`: The point `(-1, -1)` is in Quadrant III.
                *   `tan α = |b/a| = |-1 / -1| = 1`.
                *   The acute angle `α` such that `tan α = 1` is `α = π/4`.
                *   For Principal Argument (`-π < θ ≤ π`): In Quadrant III, `θ = -(π - α) = -(π - π/4) = -3π/4`.
                *   (If using `0 ≤ θ < 2π`, then `θ = π + α = π + π/4 = 5π/4`).
            *   Polar Form (using principal argument): `z = √2(cos(-3π/4) + i sin(-3π/4))`.
            *   Or `z = √2(cos(3π/4) - i sin(3π/4))` since `cos(-x)=cos(x)` and `sin(-x)=-sin(x)`.

    3.  **Problem:** Convert the complex number `z = -3` into polar form.
        *   **Solution:**
            *   `z = -3 + 0i`. Here `a = -3`, `b = 0`. This lies on the negative real axis.
            *   `r = |z| = √((-3)² + 0²) = 3`.
            *   `θ`: Since it's on the negative real axis, the principal argument is `θ = π`.
            *   Polar Form: `z = 3(cos π + i sin π)`.

    4.  **Problem:** Convert `z = i` into polar form.
        *   **Solution:**
            *   `z = 0 + 1i`. Here `a = 0`, `b = 1`. This lies on the positive imaginary axis.
            *   `r = |z| = √(0² + 1²) = 1`.
            *   `θ`: Since it's on the positive imaginary axis, the principal argument is `θ = π/2`.
            *   Polar Form: `z = 1(cos(π/2) + i sin(π/2))`.

**5. Square Root of a Complex Number**

*   **Theory:**
    *   We want to find `√(a + ib)`. Let `√(a + ib) = x + iy`, where `x, y` are real numbers.
    *   Squaring both sides: `a + ib = (x + iy)² = x² + (iy)² + 2(x)(iy) = x² - y² + i(2xy)`.
    *   Equating real and imaginary parts:
        *   `x² - y² = a`  --- (1)
        *   `2xy = b`     --- (2)
    *   We need another equation involving `x²` and `y²`. Use the identity:
        *   `(x² + y²)² = (x² - y²)² + (2xy)²`
        *   `(x² + y²)² = a² + b²`
        *   `x² + y² = √(a² + b²) = |a + ib|` (Since `x² + y²` must be non-negative, we take the positive square root). --- (3)
    *   Now we have two simple equations for `x²` and `y²`:
        *   `x² - y² = a` --- (1)
        *   `x² + y² = √(a² + b²)` --- (3)
    *   Adding (1) and (3): `2x² = a + √(a² + b²) => x² = (a + √(a² + b²)) / 2 => x = ±√[(a + √(a² + b²)) / 2]`
    *   Subtracting (1) from (3): `2y² = √(a² + b²) - a => y² = (√(a² + b²) - a) / 2 => y = ±√[(√(a² + b²) - a) / 2]`
    *   **Crucial Step:** Use equation (2), `2xy = b`, to determine the signs of `x` and `y`.
        *   If `b > 0`, then `x` and `y` must have the same sign (both positive or both negative).
        *   If `b < 0`, then `x` and `y` must have opposite signs (one positive, one negative).
    *   This gives two possible values for `x + iy`, which are negatives of each other.

*   **Problems & Solutions:**

    1.  **Problem:** Find the square root of `7 - 24i`. (Similar to RD Sharma examples)
        *   **Solution:** Let `√(7 - 24i) = x + iy`.
            *   `a = 7`, `b = -24`.
            *   `x² - y² = 7` --- (1)
            *   `2xy = -24` --- (2) (Since `b` is negative, `x` and `y` have opposite signs).
            *   `x² + y² = √(a² + b²) = √(7² + (-24)²) = √(49 + 576) = √625 = 25` --- (3)
            *   Add (1) and (3): `2x² = 7 + 25 = 32 => x² = 16 => x = ±4`.
            *   Subtract (1) from (3): `2y² = 25 - 7 = 18 => y² = 9 => y = ±3`.
            *   Since `2xy = -24` (negative), `x` and `y` must have opposite signs.
                *   If `x = 4`, then `y = -3`. (Gives `4 - 3i`)
                *   If `x = -4`, then `y = 3`. (Gives `-4 + 3i`)
            *   The square roots are `±(4 - 3i)`.

    2.  **Problem:** Find the square root of `i`.
        *   **Solution:** Find `√(0 + 1i)`. Let `√(i) = x + iy`.
            *   `a = 0`, `b = 1`.
            *   `x² - y² = 0` => `x² = y²` --- (1)
            *   `2xy = 1` --- (2) (Since `b` is positive, `x` and `y` have the same sign).
            *   `x² + y² = √(0² + 1²) = √1 = 1` --- (3)
            *   Add (1) and (3): `2x² = 1 => x² = 1/2 => x = ±1/√2`.
            *   From (1), `y² = x² = 1/2 => y = ±1/√2`.
            *   Since `2xy = 1` (positive), `x` and `y` must have the same sign.
                *   If `x = 1/√2`, then `y = 1/√2`. (Gives `(1/√2) + i(1/√2)`)
                *   If `x = -1/√2`, then `y = -1/√2`. (Gives `-(1/√2) - i(1/√2)`)
            *   The square roots are `±(1/√2 + i/√2)` or `±(1+i)/√2`.

**6. Quadratic Equations with Complex Roots**

*   **Theory:**
    *   Consider the quadratic equation `ax² + bx + c = 0`, where `a, b, c` are real numbers and `a ≠ 0`.
    *   The roots are given by the quadratic formula: `x = [-b ± √(b² - 4ac)] / 2a`.
    *   The term `D = b² - 4ac` is the discriminant.
    *   If `D < 0`, the square root term `√D` involves the square root of a negative number.
    *   Let `D = -k`, where `k = -(b² - 4ac) > 0`.
    *   Then `√D = √(-k) = √(-1 * k) = √(-1) * √k = i√k`.
    *   The roots become `x = [-b ± i√k] / 2a = (-b / 2a) ± i(√k / 2a)`.
    *   The roots are complex conjugates of each other.

*   **Problems & Solutions:**

    1.  **Problem:** Solve the equation `x² + x + 1 = 0`. (NCERT Ex 5.3, Q2 style)
        *   **Solution:**
            *   `a = 1, b = 1, c = 1`.
            *   `D = b² - 4ac = 1² - 4(1)(1) = 1 - 4 = -3`.
            *   Since `D < 0`, the roots are complex.
            *   `√D = √(-3) = i√3`.
            *   `x = [-b ± √D] / 2a = [-1 ± i√3] / 2(1) = (-1 ± i√3) / 2`.
            *   The roots are `(-1 + i√3) / 2` and `(-1 - i√3) / 2`. (These are related to the cube roots of unity, `ω` and `ω²`).

    2.  **Problem:** Solve the equation `√2 x² + x + √2 = 0`. (NCERT Ex 5.3, Q7)
        *   **Solution:**
            *   `a = √2, b = 1, c = √2`.
            *   `D = b² - 4ac = 1² - 4(√2)(√2) = 1 - 4(2) = 1 - 8 = -7`.
            *   `√D = √(-7) = i√7`.
            *   `x = [-b ± √D] / 2a = [-1 ± i√7] / (2√2)`.
            *   The roots are `(-1 + i√7) / (2√2)` and `(-1 - i√7) / (2√2)`.

---

**Teaching Tips:**

*   **Visualize:** Use the Argand plane frequently to explain modulus (distance from origin), conjugate (reflection across the real axis), and addition (vector addition).
*   **Analogy:** Relate complex number algebra (addition, multiplication) to polynomial algebra, emphasizing `i² = -1`.
*   **Practice:** Give plenty of practice problems for algebraic manipulation (powers of `i`, simplification, inverse, division) before moving to polar form.
*   **Connections:** Mention the connection between `x² + 1 = 0` and the need for complex numbers right at the start. Hint at the Fundamental Theorem of Algebra (every polynomial of degree n has n roots, possibly complex and repeated).
*   **Clarity on Argument:** Stress the importance of the quadrant when finding the argument `θ`. Explain principal argument clearly.
*   **Square Root Method:** Walk through the steps of finding the square root methodically. Emphasize checking the sign of `xy` using `b`.

This covers the core concepts usually introduced first. De Moivre's Theorem and Roots of Unity can be a good topic for the next session, building upon the polar form. Good luck with your class, babe! You'll do great!