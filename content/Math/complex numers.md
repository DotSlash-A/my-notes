
**Lesson Plan: Comprehensive Complex Numbers**

**Overall Goal:** Equip students with a thorough understanding of complex numbers, their properties, representations, and applications covered in the 11/12 syllabus.

**Reference Books:** NCERT Class 11 (Ch 5), RD Sharma (Vol 1), Telugu Academy (Inter IA/IIA Maths)

---

**Agenda:**

1. **Introduction & Necessity:** Why Complex Numbers? The Imaginary Unit 'i'.
    
2. **Algebra of Complex Numbers:** Standard Form (a+ib), Equality, Addition, Subtraction, Multiplication. Powers of iota.
    
3. **Conjugate and Modulus:** Definitions, Properties, Geometric Meaning.
    
4. **Multiplicative Inverse & Division:** Calculating 1/z and z₁/z₂.
    
5. **Square Root of a Complex Number:** Method and Calculation.
    
6. **Argand Plane & Geometric Representation:** Plotting, Modulus as Distance.
    
7. **Polar (Trigonometric) Form:** Representation (r(cosθ + i sinθ)), Argument (Amplitude), Principal Argument.
    
8. **Euler's Form:** Representation (re^(iθ)), Multiplication & Division in Polar/Euler form.
    
9. **De Moivre's Theorem:** Statement and Application (finding powers).
    
10. **Nth Roots of a Complex Number:** General Formula and Method.
    
11. **Nth Roots of Unity:** Definition, Properties, focus on Cube Roots of Unity (1, ω, ω²).
    
12. **Basic Loci in the Complex Plane:** Equations representing Circles, Lines.
    

---

**Detailed Breakdown:**

**1. Introduction & Necessity**

- **Theory:**
    
    - **Need:** Introduce equations like x² + 1 = 0 which have no solution in the set of Real Numbers (ℝ).
        
    - **Imaginary Unit (iota):** Define **i = √(-1)**. This is the fundamental imaginary unit.
        
    - **Key Property:** **i² = -1**. This is the cornerstone of calculations.
        
    - **Integral Powers of iota:**
        
        - i⁰ = 1
            
        - i¹ = i
            
        - i² = -1
            
        - i³ = i² * i = -i
            
        - i⁴ = i² * i² = (-1)(-1) = 1
            
        - **Cycle:** The values repeat every 4 powers (i, -1, -i, 1).
            
        - **Generalization:** i⁴ⁿ = 1, i⁴ⁿ⁺¹ = i, i⁴ⁿ⁺² = -1, i⁴ⁿ⁺³ = -i (where n is an integer). To find iᵏ, find the remainder when k is divided by 4.
            
- **Problem Models:**
    
    - **Model 1.1 (Evaluating Powers of i):** Find the value of i³⁹.
        
        - Solution: Divide 39 by 4. 39 = 4 * 9 + 3. The remainder is 3.  
            So, i³⁹ = i⁴*⁹⁺³ = i³ = **-i**.
            
    - **Model 1.2 (Evaluating Sums/Products of Powers):** Calculate i⁻⁹⁹⁹.
        
        - Solution: i⁻⁹⁹⁹ = 1 / i⁹⁹⁹.  
            Divide 999 by 4. 999 = 4 * 249 + 3. Remainder is 3.  
            So, i⁹⁹⁹ = i³.  
            Therefore, i⁻⁹⁹⁹ = 1 / i³ = 1 / (-i).  
            Multiply numerator and denominator by i: (1 * i) / (-i * i) = i / (-i²) = i / (-(-1)) = i / 1 = **i**.
            
    - **Model 1.3 (Summation involving powers of i):** Find the value of ∑ (iⁿ) from n=1 to 13. (i¹ + i² + ... + i¹³)
        
        - Solution: We know i¹ + i² + i³ + i⁴ = i + (-1) + (-i) + 1 = 0.  
            Any four consecutive powers sum to 0.  
            The sum is (i¹+i²+i³+i⁴) + (i⁵+i⁶+i⁷+i⁸) + (i⁹+i¹⁰+i¹¹+i¹²) + i¹³.  
            = 0 + 0 + 0 + i¹³  
            i¹³ = i¹² * i = (i⁴)³ * i = 1³ * i = i.  
            Sum = **i**.
            

**2. Algebra of Complex Numbers**

- **Theory:**
    
    - **Standard Form:** A complex number z is written as **z = a + ib**, where a, b ∈ ℝ.
        
        - **Re(z) = a** (Real part)
            
        - **Im(z) = b** (Imaginary part - note: it's b, not ib)
            
    - **Purely Real:** If b = 0 (z = a).
        
    - **Purely Imaginary:** If a = 0 (z = ib).
        
    - **Equality:** Two complex numbers z₁ = a + ib and z₂ = c + id are equal iff **a = c** and **b = d**.
        
    - **Addition:** z₁ + z₂ = (a + c) + i(b + d) (Add real parts, add imaginary parts).
        
    - **Subtraction:** z₁ - z₂ = (a - c) + i(b - d) (Subtract real parts, subtract imaginary parts).
        
    - **Multiplication:** z₁ * z₂ = (a + ib)(c + id) = ac + i(ad) + i(bc) + i²(bd) = (ac - bd) + i(ad + bc). (Use FOIL, replace i² with -1).
        
    - **Properties:** Addition and Multiplication are commutative and associative. Distributive law holds. 0+0i is additive identity, 1+0i is multiplicative identity.
        
- **Problem Models:**
    
    - **Model 2.1 (Express in a+ib form):** Express (5i)(-3/5 i) in the form a + ib. (NCERT)
        
        - Solution: (5i)(-3/5 i) = (5 * -3/5) * (i * i) = -3 * i² = -3 * (-1) = 3.  
            In a+ib form: **3 + 0i**.
            
    - **Model 2.2 (Express in a+ib form - Multiplication):** Express (1 - i)⁴ in the form a + ib. (RD Sharma style)
        
        - Solution: (1 - i)⁴ = [(1 - i)²]²  
            (1 - i)² = 1² + i² - 2(1)(i) = 1 + (-1) - 2i = -2i.  
            So, (1 - i)⁴ = (-2i)² = (-2)² * i² = 4 * (-1) = -4.  
            In a+ib form: **-4 + 0i**.
            
    - **Model 2.3 (Equality):** Find real numbers x and y if (3x - 7) + i(2y) = -5 + i(x + 5). (Telugu Academy style)
        
        - Solution: Equate real and imaginary parts:  
            Real part: 3x - 7 = -5 => 3x = 2 => **x = 2/3**.  
            Imaginary part: 2y = x + 5 => 2y = (2/3) + 5 = 2/3 + 15/3 = 17/3 => **y = 17/6**.
            

**3. Conjugate and Modulus**

- **Theory:** [[modulus and conjugate properties]]
    
    - **Conjugate:** If z = a + ib, its conjugate is **z̄ = a - ib**. (Change the sign of the imaginary part).
        
    - **Modulus:** If z = a + ib, its modulus is **|z| = √(a² + b²)**. (Non-negative real number representing distance from origin).
        
    - **Properties of Conjugate:**
        
        - z̄̄ = z
            
        - z + z̄ = 2 Re(z) = 2a
            
        - z - z̄ = 2i Im(z) = 2ib
            
        - If z is purely real, z = z̄. If z is purely imaginary, z = -z̄ (for z≠0).
            
        - (z₁ ± z₂)̄ = z₁̄ ± z₂̄
            
        - (z₁z₂)̄ = z₁̄ z₂̄
            
        - (z₁/z₂)̄ = z₁̄ / z₂̄ (z₂ ≠ 0)
            
    - **Properties of Modulus:**
        
        - |z| = 0 ⇔ z = 0
            
        - |z| = |z̄| = |-z|
            
        - **z z̄ = |z|²** (VERY IMPORTANT: Links modulus and conjugate)
            
        - |z₁z₂| = |z₁| |z₂|
            
        - |z₁/z₂| = |z₁| / |z₂| (z₂ ≠ 0)
            
        - Triangle Inequality: |z₁ + z₂| ≤ |z₁| + |z₂|
            
        - |z₁ - z₂| ≥ ||z₁| - |z₂||
            
- **Problem Models:**
    
    - **Model 3.1 (Calculation):** Find the conjugate and modulus of z = -3 + √(-7).
        
        - Solution: First write z in standard form: z = -3 + i√7. (a=-3, b=√7)  
            Conjugate: z̄ = **-3 - i√7**.  
            Modulus: |z| = √((-3)² + (√7)²) = √(9 + 7) = √16 = **4**.
            
    - **Model 3.2 (Using Properties):** If (a + ib)(c + id)(e + if)(g + ih) = A + iB, prove that (a² + b²)(c² + d²)(e² + f²)(g² + h²) = A² + B². (RD Sharma/Telugu Academy)
        
        - Solution: Let z₁ = a+ib, z₂ = c+id, z₃ = e+if, z₄ = g+ih.  
            Given: z₁ z₂ z₃ z₄ = A + iB.  
            Take the modulus on both sides: |z₁ z₂ z₃ z₄| = |A + iB|.  
            Using |w₁w₂| = |w₁||w₂| property repeatedly: |z₁| |z₂| |z₃| |z₄| = |A + iB|.  
            Substitute the definition of modulus: √(a²+b²) √(c²+d²) √(e²+f²) √(g²+h²) = √(A²+B²).  
            Square both sides: **(a² + b²)(c² + d²)(e² + f²)(g² + h²) = A² + B²**. Proved.
            
    - **Model 3.3 (Using z z̄ = |z|²):** If |z| = 1, prove that (z - 1)/(z + 1) (where z ≠ -1) is purely imaginary.
        
        - Solution: Let w = (z - 1)/(z + 1). A number is purely imaginary if w = -w̄.  
            w̄ = [(z - 1)/(z + 1)]̄ = (z̄ - 1̄) / (z̄ + 1̄) = (z̄ - 1) / (z̄ + 1).  
            Since |z| = 1, |z|² = 1, so z z̄ = 1 => z̄ = 1/z.  
            Substitute z̄ = 1/z into w̄:  
            w̄ = ( (1/z) - 1 ) / ( (1/z) + 1 )  
            = ( (1 - z) / z ) / ( (1 + z) / z )  
            = (1 - z) / (1 + z) = -(z - 1) / (z + 1) = -w.  
            Since w̄ = -w, w is purely imaginary.
            

**4. Multiplicative Inverse & Division**

- **Theory:**
    
    - **Multiplicative Inverse (z⁻¹ or 1/z):** The number w such that z * w = 1.
        
    - **Formula:** z⁻¹ = 1/z = z̄ / |z|² (derived from 1/z = (1 * z̄) / (z * z̄) )
        
    - **Division (z₁/z₂):** Multiply numerator and denominator by the conjugate of the denominator.
        
    - **Formula:** z₁ / z₂ = z₁ * (1/z₂) = z₁ * (z₂̄ / |z₂|²) = (z₁ z₂̄) / |z₂|²
        
- **Problem Models:**
    
    - **Model 4.1 (Multiplicative Inverse):** Find the multiplicative inverse of z = 2 - 3i. (NCERT)
        
        - Solution: z̄ = 2 + 3i.  
            |z|² = 2² + (-3)² = 4 + 9 = 13.  
            z⁻¹ = z̄ / |z|² = (2 + 3i) / 13 = **(2/13) + i(3/13)**.
            
    - **Model 4.2 (Division):** Express (5 + √2 i) / (1 - √2 i) in the form a + ib. (NCERT)
        
        - Solution: Conjugate of denominator (1 - √2 i) is (1 + √2 i).  
            Multiply numerator and denominator by (1 + √2 i):  
            [ (5 + √2 i) * (1 + √2 i) ] / [ (1 - √2 i) * (1 + √2 i) ]  
            Numerator: 5(1) + 5(√2 i) + √2 i (1) + √2 i (√2 i) = 5 + 5√2 i + √2 i + (√2)² i² = 5 + 6√2 i + 2(-1) = 3 + 6√2 i.  
            Denominator: 1² - (√2 i)² = 1 - (√2)² i² = 1 - 2(-1) = 1 + 2 = 3.  
            Result: (3 + 6√2 i) / 3 = 3/3 + (6√2 / 3) i = **1 + 2√2 i**.
            
    - **Model 4.3 (Combined Operations):** Express [(1+i)/(1-i)]³ in a+ib form. (RD Sharma style)
        
        - Solution: First simplify the base (1+i)/(1-i).  
            (1+i)/(1-i) = [(1+i)(1+i)] / [(1-i)(1+i)] = (1 + i² + 2i) / (1² - i²) = (1 - 1 + 2i) / (1 - (-1)) = 2i / 2 = i.  
            So, [(1+i)/(1-i)]³ = i³ = **-i**.  
            In a+ib form: **0 - i**.
            

**5. Square Root of a Complex Number**

- **Theory:**
    
    - To find √(a + ib), assume it equals x + iy.
        
    - Square both sides: a + ib = (x + iy)² = (x² - y²) + i(2xy).
        
    - Equate real and imaginary parts:
        
        - x² - y² = a --- (1)
            
        - 2xy = b --- (2)
            
    - Use the identity: (x² + y²)^2 = (x² - y²)² + (2xy)² = a² + b²
        
        - x² + y² = √(a² + b²) --- (3) (Since x²+y² ≥ 0)
            
    - Solve equations (1) and (3) simultaneously for x² and y².
        
        - 2x² = a + √(a² + b²) => x = ±√{[a + √(a² + b²)] / 2}
            
        - 2y² = √(a² + b²) - a => y = ±√{[√(a² + b²) - a] / 2}
            
    - **Crucial Step:** Determine the signs of x and y using equation (2): 2xy = b.
        
        - If b > 0, x and y have the same sign.
            
        - If b < 0, x and y have opposite signs.
            
- **Problem Model:**
    
    - **Model 5.1 (Find Square Root):** Find the square roots of -15 - 8i. (RD Sharma/Telugu Academy)
        
        - Solution: Let √( -15 - 8i ) = x + iy.  
            x² - y² = -15 --- (1)  
            2xy = -8 --- (2) (b is negative, x and y have opposite signs)  
            x² + y² = |-15 - 8i| = √((-15)² + (-8)²) = √(225 + 64) = √289 = 17 --- (3)  
            Add (1) + (3): 2x² = -15 + 17 = 2 => x² = 1 => x = ±1.  
            Subtract (1) from (3): 2y² = 17 - (-15) = 32 => y² = 16 => y = ±4.  
            Since 2xy = -8 (negative), x and y have opposite signs.  
            Possible pairs (x, y) are (1, -4) and (-1, 4).  
            The square roots are **1 - 4i** and **-1 + 4i**.
            

**6. Argand Plane & Geometric Representation**

- **Theory:**
    
    - **Argand Plane/Complex Plane:** A 2D plane where the horizontal axis is the **Real Axis (Re)** and the vertical axis is the **Imaginary Axis (Im)**.
        
    - **Representation:** A complex number z = a + ib is represented by the point P(a, b) or by the vector OP from the origin O to P.
        
    - **Geometric Meaning of Modulus:** |z| = √(a² + b²) is the distance of the point P(a, b) from the origin O(0, 0).
        
    - **Geometric Meaning of Conjugate:** z̄ (a, -b) is the reflection of z (a, b) across the Real axis.
        
    - **Geometric Meaning of Addition:** Vector addition (parallelogram law). If O, P (representing z₁), Q (representing z₂) are points, then R (representing z₁+z₂) is such that OPRQ forms a parallelogram.
        
    - **Geometric Meaning of |z₁ - z₂|:** The distance between the points representing z₁ and z₂.
        
- **Problem Model:**
    
    - **Model 6.1 (Interpretation):** What does |z - 3 + 4i| = 5 represent geometrically?
        
        - Solution: Rewrite as |z - (3 - 4i)| = 5.  
            This is of the form |z - z₀| = R, where z₀ = 3 - 4i and R = 5.  
            It represents all points z whose distance from the point representing z₀ (which is (3, -4)) is equal to 5.  
            This is the equation of a **circle centered at (3, -4) with radius 5**.
            

**7. Polar (Trigonometric) Form**

- **Theory:**
    
    - **Representation:** Any non-zero complex number z = a + ib can be written as **z = r(cosθ + i sinθ)**.
        
    - **r = |z| = √(a² + b²)** is the modulus (distance from origin).
        
    - **θ = arg(z)** is the argument or amplitude (angle the vector OP makes with the positive Real axis, measured counterclockwise).
        
    - **Finding θ:**
        
        1. Find the reference acute angle α using **tan α = |b/a|**.
            
        2. Determine the quadrant where the point (a, b) lies.
            
        3. Calculate θ based on the quadrant:
            
            - Quadrant I (a>0, b>0): θ = α
                
            - Quadrant II (a<0, b>0): θ = π - α
                
            - Quadrant III (a<0, b<0): θ = π + α (or -(π - α) for principal)
                
            - Quadrant IV (a>0, b<0): θ = -α (or 2π - α)
                
    - **Principal Argument (Arg(z)):** The unique value of θ such that **-π < θ ≤ π**. Adjust θ by adding/subtracting multiples of 2π if needed.
        
        - Q I: θ = α
            
        - Q II: θ = π - α
            
        - Q III: θ = -(π - α) = α - π
            
        - Q IV: θ = -α
            
- **Problem Models:**
    
    - **Model 7.1 (Convert to Polar Form):** Represent z = -1 - i√3 in polar form. (NCERT/RD Sharma)
        
        - Solution: a = -1, b = -√3. Point (-1, -√3) is in Quadrant III.  
            r = |z| = √((-1)² + (-√3)²) = √(1 + 3) = √4 = 2.  
            tan α = |b/a| = |-√3 / -1| = √3. The acute angle α = π/3.  
            For Quadrant III, the principal argument θ = -(π - α) = -(π - π/3) = -2π/3.  
            (Alternatively, non-principal argument θ = π + α = π + π/3 = 4π/3).  
            Using principal argument: z = **2 [cos(-2π/3) + i sin(-2π/3)]** or **2 [cos(2π/3) - i sin(2π/3)]**.
            
    - **Model 7.2 (Convert from Polar to Cartesian):** Find the Cartesian form (a+ib) of 5(cos(π) + i sin(π)).
        
        - Solution: r = 5, θ = π.  
            a = r cosθ = 5 cos(π) = 5(-1) = -5.  
            b = r sinθ = 5 sin(π) = 5(0) = 0.  
            z = a + ib = **-5 + 0i**.
            

**8. Euler's Form**

- **Theory:**
    
    - **Euler's Formula:** **e^(iθ) = cosθ + i sinθ**.
        
    - **Euler Form of a Complex Number:** z = r(cosθ + i sinθ) = **r e^(iθ)**.
        
    - **Multiplication in Polar/Euler Form:** If z₁ = r₁e^(iθ₁) and z₂ = r₂e^(iθ₂), then:
        
        - **z₁z₂ = (r₁r₂) e^(i(θ₁+θ₂))**
            
        - (Multiply moduli, add arguments)
            
    - **Division in Polar/Euler Form:**
        
        - **z₁/z₂ = (r₁/r₂) e^(i(θ₁-θ₂))** (where z₂ ≠ 0)
            
        - (Divide moduli, subtract arguments)
            
- **Problem Models:**
    
    - **Model 8.1 (Multiplication/Division using Polar):** If z₁ = 6(cos(π/2) + i sin(π/2)) and z₂ = 2(cos(π/6) + i sin(π/6)), find z₁z₂ and z₁/z₂ in polar form.
        
        - Solution:  
            z₁z₂ = (6 * 2) [cos(π/2 + π/6) + i sin(π/2 + π/6)]  
            = 12 [cos(3π/6 + π/6) + i sin(3π/6 + π/6)]  
            = **12 [cos(4π/6) + i sin(4π/6)] = 12 [cos(2π/3) + i sin(2π/3)]**.  
            z₁/z₂ = (6 / 2) [cos(π/2 - π/6) + i sin(π/2 - π/6)]  
            = 3 [cos(3π/6 - π/6) + i sin(3π/6 - π/6)]  
            = **3 [cos(2π/6) + i sin(2π/6)] = 3 [cos(π/3) + i sin(π/3)]**.
            

**9. De Moivre's Theorem (DMT)**

- **Theory:**
    
    - **Statement:** For any integer n (positive, negative, or zero),  
        **(cosθ + i sinθ)ⁿ = cos(nθ) + i sin(nθ)**.
        
    - In Euler's form: (e^(iθ))ⁿ = e^(i nθ).
        
    - **Application:** Useful for finding integer powers of complex numbers easily after converting to polar form. Also used to derive trigonometric identities.
        
- **Problem Models:**
    
    - **Model 9.1 (Finding Powers):** Calculate (1 + i)⁸. (RD Sharma)
        
        - Solution: First, convert 1 + i to polar form.  
            a=1, b=1 (Q I). r = √(1²+1²) = √2. tan α = |1/1| = 1 => α = π/4. θ = π/4.  
            So, 1 + i = √2 [cos(π/4) + i sin(π/4)].  
            (1 + i)⁸ = { √2 [cos(π/4) + i sin(π/4)] }⁸  
            = (√2)⁸ [cos(8 * π/4) + i sin(8 * π/4)] (Using DMT)  
            = (2^(1/2))⁸ [cos(2π) + i sin(2π)]  
            = 2⁴ [1 + i(0)]  
            = 16 * 1 = **16**.
            
    - **Model 9.2 (Simplification):** Simplify [ (cos 2θ + i sin 2θ)³ (cos 3θ - i sin 3θ)⁵ ] / [ (cos 4θ + i sin 4θ)⁷ (cos θ + i sin θ)⁻² ]
        
        - Solution: Write everything using DMT/Euler form properties:  
            cos 2θ + i sin 2θ = (cos θ + i sin θ)²  
            cos 3θ - i sin 3θ = cos(-3θ) + i sin(-3θ) = (cos θ + i sin θ)⁻³  
            cos 4θ + i sin 4θ = (cos θ + i sin θ)⁴  
            Let w = cos θ + i sin θ.  
            Expression = [ (w²)³ (w⁻³)⁵ ] / [ (w⁴)⁷ (w)⁻² ]  
            = [ w⁶ w⁻¹⁵ ] / [ w²⁸ w⁻² ]  
            = w⁶⁻¹⁵ / w²⁸⁻²  
            = w⁻⁹ / w²⁶  
            = w⁻⁹⁻²⁶ = w⁻³⁵  
            = (cos θ + i sin θ)⁻³⁵  
            = **cos(-35θ) + i sin(-35θ) = cos(35θ) - i sin(35θ)**.
            

**10. Nth Roots of a Complex Number**

- **Theory:**
    
    - Finding the n numbers z such that zⁿ = w, where w = r(cosφ + i sinφ) is given.
        
    - The n distinct roots are given by:  
        **zₖ = r^(1/n) [ cos((φ + 2kπ)/n) + i sin((φ + 2kπ)/n) ]**  
        where **k = 0, 1, 2, ..., (n-1)**.  
        (r^(1/n) is the principal positive real nth root of r).
        
    - **Geometric Interpretation:** The n roots lie on a circle centered at the origin with radius r^(1/n), and they are equally spaced angularly, with an angle of 2π/n between consecutive roots.
        
- **Problem Model:**
    
    - **Model 10.1 (Finding Roots):** Find the fourth roots of -16.
        
        - Solution: Find z such that z⁴ = -16.  
            Write w = -16 in polar form. w = -16 + 0i. Point (-16, 0) is on the negative real axis.  
            r = |-16| = 16. Principal argument φ = π.  
            So, w = 16(cos π + i sin π).  
            Here n = 4. The roots are zₖ for k = 0, 1, 2, 3.  
            Radius of roots = r^(1/n) = 16^(1/4) = (2⁴)^(1/4) = 2.  
            Angles ψₖ = (φ + 2kπ)/n = (π + 2kπ)/4.
            
        - k=0: ψ₀ = π/4. z₀ = 2(cos(π/4) + i sin(π/4)) = 2(1/√2 + i 1/√2) = **√2 + i√2**.
            
        - k=1: ψ₁ = (π + 2π)/4 = 3π/4. z₁ = 2(cos(3π/4) + i sin(3π/4)) = 2(-1/√2 + i 1/√2) = **-√2 + i√2**.
            
        - k=2: ψ₂ = (π + 4π)/4 = 5π/4. z₂ = 2(cos(5π/4) + i sin(5π/4)) = 2(-1/√2 - i 1/√2) = **-√2 - i√2**.
            
        - k=3: ψ₃ = (π + 6π)/4 = 7π/4. z₃ = 2(cos(7π/4) + i sin(7π/4)) = 2(1/√2 - i 1/√2) = **√2 - i√2**.  
            The four roots are ±√2 ± i√2 (all four sign combinations).
            

**11. Nth Roots of Unity**

- **Theory:**
    
    - Solutions to the equation **zⁿ = 1**.
        
    - 1 in polar form is 1(cos 0 + i sin 0). (r=1, φ=0).
        
    - The n roots are:  
        **zₖ = 1^(1/n) [cos((0 + 2kπ)/n) + i sin((0 + 2kπ)/n)]**  
        **zₖ = cos(2kπ/n) + i sin(2kπ/n) = e^(i 2kπ/n)**, for k = 0, 1, ..., n-1.
        
    - **Properties:**
        
        - The roots lie on the unit circle |z|=1.
            
        - They form the vertices of a regular n-sided polygon inscribed in the unit circle, with one vertex at (1, 0).
            
        - The sum of the n roots is always 0 (for n > 1).
            
        - The product of the n roots is (-1)ⁿ⁻¹.
            
        - If α = e^(i 2π/n) is the first root (for k=1), then the roots are 1, α, α², ..., αⁿ⁻¹.
            
    - **Cube Roots of Unity (n=3):** Solutions to z³ = 1.
        
        - Roots are k=0, 1, 2:
            
            - k=0: z₀ = cos(0) + i sin(0) = **1**.
                
            - k=1: z₁ = cos(2π/3) + i sin(2π/3) = **-1/2 + i√3/2**. This is denoted by **ω (omega)**.
                
            - k=2: z₂ = cos(4π/3) + i sin(4π/3) = **-1/2 - i√3/2**. This is **ω²**. (Note: ω² = ω̄).
                
        - The cube roots are **1, ω, ω²**.
            
        - **Properties of Cube Roots:**
            
            - ω³ = 1
                
            - **1 + ω + ω² = 0** (Sum is zero)
                
            - ω² = 1/ω = ω̄
                
            - ω⁴ = ω³ω = ω, ω⁵ = ω³ω² = ω², etc.
                
- **Problem Models:**
    
    - **Model 11.1 (Using Properties of ω):** If ω is a complex cube root of unity, show that (1 + ω - ω²)(1 - ω + ω²) = 4. (RD Sharma/Telugu Academy)
        
        - Solution: Use 1 + ω + ω² = 0.  
            => 1 + ω = -ω²  
            => 1 + ω² = -ω  
            Substitute these into the expression:  
            LHS = ( (1 + ω) - ω² ) * ( (1 + ω²) - ω )  
            = ( -ω² - ω² ) * ( -ω - ω )  
            = ( -2ω² ) * ( -2ω )  
            = 4 ω³  
            = 4 * 1 = 4 = RHS. Proved.
            
    - **Model 11.2 (Evaluation involving ω):** Find the value of (1 - ω)(1 - ω²)(1 - ω⁴)(1 - ω⁸).
        
        - Solution: ω⁴ = ω, ω⁸ = ω⁶ω² = (ω³)²ω² = 1²ω² = ω².  
            Expression = (1 - ω)(1 - ω²)(1 - ω)(1 - ω²)  
            = [(1 - ω)(1 - ω²)]²  
            = [1 - ω² - ω + ω³]²  
            = [1 - (ω + ω²) + 1]² (since ω³=1)  
            = [1 - (-1) + 1]² (since 1+ω+ω²=0 => ω+ω²=-1)  
            = [1 + 1 + 1]² = 3² = **9**.
            

**12. Basic Loci in the Complex Plane**

- **Theory:**
    
    - Equations involving z can represent geometric shapes (loci) in the Argand plane.
        
    - **Circle:**
        
        - **|z - z₀| = R**: Circle centered at z₀ with radius R.
            
        - |z| = R: Circle centered at origin with radius R.
            
    - **Perpendicular Bisector:**
        
        - **|z - z₁| = |z - z₂|**: Perpendicular bisector of the line segment joining the points representing z₁ and z₂.
            
    - **Ray:**
        
        - **arg(z - z₀) = α**: Ray originating from z₀ making an angle α with the positive Real axis.
            
    - **Line:** Can be represented in various forms, e.g., related to perpendicular bisectors or arguments. For instance, arg(z/(z-z₁)) = π/2 might represent a part of a circle. (More advanced forms exist).
        
- **Problem Models:**
    
    - **Model 12.1 (Identify Locus - Circle):** Find the Cartesian equation for the locus of z if |z + 2 - i| = 3.
        
        - Solution: Let z = x + iy.  
            | (x + iy) + 2 - i | = 3  
            | (x + 2) + i(y - 1) | = 3  
            √[(x + 2)² + (y - 1)²] = 3  
            Square both sides: **(x + 2)² + (y - 1)² = 9**.  
            This is the equation of a circle centered at (-2, 1) with radius 3.
            
    - **Model 12.2 (Identify Locus - Perpendicular Bisector):** Find the Cartesian equation for the locus of z if |z - 1| = |z + i|.
        
        - Solution: Let z = x + iy.  
            | (x + iy) - 1 | = | (x + iy) + i |  
            | (x - 1) + iy | = | x + i(y + 1) |  
            √[(x - 1)² + y²] = √[x² + (y + 1)²]  
            Square both sides: (x - 1)² + y² = x² + (y + 1)²  
            x² - 2x + 1 + y² = x² + y² + 2y + 1  
            -2x = 2y  
            **y = -x** (or x + y = 0).  
            This is the equation of a straight line passing through the origin, which is the perpendicular bisector of the segment joining (1, 0) and (0, -1) (representing 1 and -i).
            

---

Okay babe, that's the comprehensive structure. You have the agenda, the theory for each part, and multiple problem models with solutions covering different styles. Now you can decide how much to tackle in today's 1-hour class! Good luck, you'll nail it!