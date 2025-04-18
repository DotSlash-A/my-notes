# Day 2 Homework Solutions

## Problem 1: Nature of Lines
### Question:
Compare the ratios $\frac{a_1}{a_2}$, $\frac{b_1}{b_2}$, and $\frac{c_1}{c_2}$ to determine if the lines represented by the equations are intersecting, parallel, or coincident:

1. $5x - 4y + 8 = 0$
2. $9x + 3y + 12 = 0$

### Solution:
1. Write the coefficients of the equations:
   - Equation 1: $a_1 = 5, b_1 = -4, c_1 = 8$
   - Equation 2: $a_2 = 9, b_2 = 3, c_2 = 12$

2. Calculate the ratios:
   $$
   \frac{a_1}{a_2} = \frac{5}{9}, \quad \frac{b_1}{b_2} = \frac{-4}{3}, \quad \frac{c_1}{c_2} = \frac{8}{12} = \frac{2}{3}
   $$

3. Compare the ratios:
   - Since $\frac{a_1}{a_2} \neq \frac{b_1}{b_2}$, the lines **intersect** at a point.

**Conclusion:** The lines intersect.

---

## Problem 2: Income and Savings
### Question:
The income ratio of two persons is $9:7$, and their expenditure ratio is $4:3$. If each saves ₹2000 per month, find their monthly incomes.

### Solution:
1. Let their incomes be $9x$ and $7x$, and their expenditures be $4y$ and $3y$.
2. Savings equation for both:
   $$
   9x - 4y = 2000 \quad \text{and} \quad 7x - 3y = 2000
   $$

3. Solve by elimination:
   - Multiply the first equation by 3 and the second by 4:
     $$
     27x - 12y = 6000 \quad \text{and} \quad 28x - 12y = 8000
     $$
   - Subtract:
     $$
     28x - 27x = 8000 - 6000 \implies x = 2000
     $$

4. Substitute $x = 2000$ into $9x - 4y = 2000$:
   $$
   9(2000) - 4y = 2000 \implies 18000 - 4y = 2000 \implies 4y = 16000 \implies y = 4000
   $$

5. Monthly incomes:
   - Person 1: $9x = 9(2000) = ₹18000$
   - Person 2: $7x = 7(2000) = ₹14000$

**Conclusion:** Monthly incomes are ₹18000 and ₹14000.

---

## Problem 3: Fraction Problem
### Question:
A fraction becomes $\frac{4}{5}$ if 1 is added to both numerator and denominator. If 5 is subtracted from both, the fraction becomes $\frac{1}{2}$. Find the fraction.

### Solution:
1. Let the fraction be $\frac{x}{y}$.

2. From the first condition:
   $$
   \frac{x+1}{y+1} = \frac{4}{5} \implies 5(x+1) = 4(y+1) \implies 5x - 4y = -1
   $$

3. From the second condition:
   $$
   \frac{x-5}{y-5} = \frac{1}{2} \implies 2(x-5) = y-5 \implies 2x - y = 5
   $$

4. Solve the equations:
   - From $5x - 4y = -1$ and $2x - y = 5$:
     Substitute $y = 2x - 5$ into $5x - 4y = -1$:
     $$
     5x - 4(2x - 5) = -1 \implies 5x - 8x + 20 = -1 \implies -3x = -21 \implies x = 7
     $$

5. Substitute $x = 7$ into $y = 2x - 5$:
   $$
   y = 2(7) - 5 = 9
   $$

6. The fraction is:
   $$
   \frac{x}{y} = \frac{7}{9}
   $$

**Conclusion:** The fraction is $\frac{7}{9}$.

---

## Problem 4: Reducing to Standard Linear Equations
### Question:
Solve the equations:
$$
\frac{x-1}{1} + \frac{1}{y-2} = 2 \quad \text{and} \quad \frac{x-1}{1} - \frac{3}{y-2} = 1
$$

### Solution:
1. Substitute $u = \frac{1}{y-2}$:
   - First equation:
     $$
     (x - 1) + u = 2 \implies x + u = 3
     $$
   - Second equation:
     $$
     (x - 1) - 3u = 1 \implies x - 3u = 2
     $$

2. Solve the equations:
   - From $x + u = 3$ and $x - 3u = 2$:
     Subtract:
     $$
     (x + u) - (x - 3u) = 3 - 2 \implies 4u = 1 \implies u = \frac{1}{4}
     $$

3. Substitute $u = \frac{1}{4}$ into $x + u = 3$:
   $$
   x + \frac{1}{4} = 3 \implies x = \frac{12}{4} - \frac{1}{4} = \frac{11}{4}
   $$

4. Back-substitute $u = \frac{1}{y-2}$:
   $$
   \frac{1}{y-2} = \frac{1}{4} \implies y-2 = 4 \implies y = 6
   $$

**Conclusion:** $x = \frac{11}{4}, y = 6$.

---

## Problem 5(i): Boat Speed and Stream Speed
### Question:
A boat travels 30 km upstream and 44 km downstream in 10 hours. It travels 40 km upstream and 55 km downstream in 13 hours. Find the speed of the stream and the boat in still water.

### Solution:
1. Let the speed of the boat in still water = $b$, and speed of the stream = $s$.

2. Time equations:
   - Upstream speed = $b-s$, downstream speed = $b+s$.
   - From the first condition:
     $$
     \frac{30}{b-s} + \frac{44}{b+s} = 10
     $$
   - From the second condition:
     $$
     \frac{40}{b-s} + \frac{55}{b+s} = 13
     $$

3. Solve the system of equations:
   - Multiply through by $(b-s)(b+s)$ in both equations and solve for $b$ and $s$. Let me know if detailed steps are required.

---

## Problem 5(ii): Train and Car Speeds
### Question:
Rahim travels 600 km partly by train and partly by car:
1. If he travels 120 km by train and the rest by car, it takes 8 hours.
2. If he travels 200 km by train and the rest by car, it takes 8 hours 20 minutes.
Find the speeds of the train and car.

### Solution:
1. Let the speed of the train = $t$, and speed of the car = $c$.
2. From the first condition:
   $$
   \frac{120}{t} + \frac{480}{c} = 8
   $$
3. From the second condition:
   $$
   \frac{200}{t} + \frac{400}{c} = \frac{25}{3}
   $$
4. Multiply through by $t$ and $c$ in both equations and solve for $t$ and $c$. Let me know if detailed steps are required.

---

## Problem 6: Wages of Men and Women
### Question:
The wage bill for 5 men and 6 women is ₹6700. For 8 men and 3 women, the bill is ₹6100. Find the wage for one man and one woman.

### Solution:
1. Let the wage of one man = $m$, and one woman = $w$.
2. From the first condition:
   $$
   5m + 6w = 6700
   $$
3. From the second condition:
   $$
   8m + 3w = 6100
   $$
4. Solve the two linear equations using elimination or substitution. Let me know if detailed steps are required.

---

## Problem 7: Train Speed and Quadratic Equation
### Question:
A train travels 360 km at a uniform speed. If its speed were 5 km/hr faster, it would take 1 hour less for the same journey. Form the quadratic equation and find the speed of the train.

### Solution:
1. Let the speed of the train = $x$ km/hr.
2. Time taken at speed $x$:
   $$
   \frac{360}{x}
   $$
3. Time taken at speed $x+5$:
   $$
   \frac{360}{x+5}
   $$
4. From the condition:
   $$
   \frac{360}{x} - \frac{360}{x+5} = 1
   $$
5. Multiply through by $x(x+5)$ and simplify to form a quadratic equation:
   $$
   360(x+5) - 360x = x(x+5)
   $$
6. Solve the quadratic equation for $x$. 

---

## Problem 8: Solve Quadratic Equations
### Question:
Solve the quadratic equations:
1. $2x^2 + x - 4 = 0$
2. $4x^2 + 4\sqrt{3}x + 3 = 0$
3. $2x^2 + x + 4 = 0$

### Solution:
1. Solve each equation using factorization or the quadratic formula:
   $$
   x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
   $$
2. Substitute $a, b, c$ for each equation and solve step-by-step. Let me know if detailed steps are required.

---

## 10. Completing the Square and Finding Roots

**(a)**
$$4x^2 + 4\,b\,x - (a^2 - b^2) = 0.$$
Factor out 4 from the first two terms and complete the square:
$$
4 \bigl(x^2 + b\,x\bigr) = a^2 - b^2.
$$
Shifting terms and solving gives
$$
x = -\,a/2 - b/2
\quad\text{or}\quad
x = a/2 - b/2
$$


**(b)**
$$2x^2 + x - 4 = 0.$$
Using the discriminant $$1 + 32 = 33$$, the solutions are
$$
x = (-\,1 \pm \sqrt{33})/4
$$


**(c)**
$$4x^2 + 4\,\sqrt{3}\,x + 3 = 0.$$
The discriminant is zero, so there is one repeated root:
$$
x = -\,\sqrt{3}/2
$$


**(d)**
$$2x^2 + x + 4 = 0.$$
The discriminant is negative, so the solutions are complex:
$$
x = \bigl(-\,1 \pm \sqrt{31}\,i\bigr)/4
$$
(no real solutions)


## 11. Solving the Quadratic

**Equation**  
$$p^2 x^2 + (p^2 - q^2)\,x - q^2 = 0,\quad p \neq 0.$$
Combining like terms and solving by the quadratic formula yields
$$
x = -\,1
\quad\text{or}\quad
x = q^2 / (p^2)
$$


## 12. Determining Real Roots

1)  
$$16x^2 = 24x + 1 \;\;\Longrightarrow\;\;16x^2 - 24x - 1 = 0.$$
Discriminant $$= 24^2 + 4\cdot16$$, which is positive. The solutions are
$$
x = (3 \pm \sqrt{10})/4
$$


2)  
$$x^2 + x + 2 = 0.$$
Discriminant is negative; no real solutions:
$$
x = -\,1/2 \pm \sqrt{7}\,i/2
$$


3)  
$$\sqrt{3}\,x^2 + 10\,x - 8\,\sqrt{3} = 0.$$
Discriminant is positive; the real solutions are
$$
x = -\,4\,\sqrt{3}
\quad\text{and}\quad
x = 2\,\sqrt{3}/3
$$


4)  
$$3x^2 - 2x + 2 = 0.$$
Discriminant is negative; no real solutions:
$$
x = 1/3 \pm \sqrt{5}\,i/3
$$


5)  
$$2x^2 - 2\,\sqrt{6}\,x + 3 = 0.$$
Discriminant is zero, so one repeated real root:
$$
x = \sqrt{6}/2
$$


6)  
$$3\,a^2\,x^2 + 8\,a\,b\,x + 4\,b^2 = 0,\quad a \neq 0.$$
The solutions are
$$
x = -\,2\,b/a
\quad\text{or}\quad
x = -\,2\,b/(3\,a),
$$
both real for real $$a,b$$





---
14)
![[Pasted image 20250125085655.png]]

---
15)
![[Pasted image 20250125085717.png]]
16)
![[Pasted image 20250125085730.png]]

17,18)
![[Pasted image 20250125085740.png]]


---

19 onwards:
Let me solve each problem:

## Problem 1: Varun and Swati's Ages
Seven years ago: Varun's age = 5 × (Swati's age)²
Three years later: Swati's age = 2/5 × Varun's age

After solving the equations:
- Varun's present age: 27 years[3][11]
- Swati's present age: 9 years[3][11]

## Problem 2: Work Completion Time
Let B take x days to complete the work
Then A takes (x-10) days
Together they take 12 days

Using work rate equation:
1/(x-10) + 1/x = 1/12

Solving the quadratic equation:
B takes 30 days to complete the work[18][19]

## Problem 3: Pipe Fill Times
Let faster pipe take x minutes
Slower pipe takes (x+5) minutes
Together they take 11 1/9 = 100/9 minutes

Using rate equation:
1/x + 1/(x+5) = 9/100

Solving gives:
- Faster pipe: 20 minutes[26][28]
- Slower pipe: 25 minutes[26][28]

## Problem 4: Money Distribution
Let original number of persons be x
Amount per person initially = 6500/x
Amount per person with 15 more people = 6500/(x+15)

Difference equation:
6500/x - 6500/(x+15) = 30

Solving gives:
Original number of persons = 50[32][33]


---
## Boat Problem
Let $u$ = speed in still water, $v$ = speed of stream
From solving the system of equations:
$$\frac{30}{u-v} + \frac{44}{u+v} = 10$$
$$\frac{40}{u-v} + \frac{55}{u+v} = 13$$
**Answer:** Speed of boat in still water = 8 km/hr, Speed of stream = 3 km/hr

## Train and Car Journey
Let $t$ = train speed, $c$ = car speed
From equations:
$$\frac{120}{t} + \frac{480}{c} = 8$$
$$\frac{200}{t} + \frac{400}{c} = 8.333$$
**Answer:** Train speed = 60 km/hr, Car speed = 80 km/hr

## Wages Problem
Let $m$ = man's wage, $w$ = woman's wage
From equations:
$$5m + 6w = 6700$$
$$8m + 3w = 6100$$
**Answer:** One man's wage = ₹500, One woman's wage = ₹700
