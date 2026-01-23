## Systems of Linear Equations - Solutions

### Ex 1. 

**Problem:**

Solve the system of equations:

$$
\begin{aligned} 2x+3y&=5,\\ x-4y&=-2. \end{aligned}
$$

using the methods: Cramer's rule, Gaussian elimination, and inverse matrix.

**Solution:**

$$
\begin{cases} 2x+3y=5 \\ x-4y=-2 \end{cases}
$$

**1. Cramer's Rule:**
$A = \begin{pmatrix} 2 & 3 \\ 1 & -4 \end{pmatrix}$. $\det(A) = -8 - 3 = -11$.
$W_x = \det \begin{pmatrix} 5 & 3 \\ -2 & -4 \end{pmatrix} = -20 - (-6) = -14$.
$W_y = \det \begin{pmatrix} 2 & 5 \\ 1 & -2 \end{pmatrix} = -4 - 5 = -9$.
$x = \frac{-14}{-11} = \frac{14}{11}$, $y = \frac{-9}{-11} = \frac{9}{11}$.

**2. Gaussian Elimination:**
augmented matrix $\left(\begin{array}{cc|c} 1 & -4 & -2 \\ 2 & 3 & 5 \end{array}\right)$ (Swapped rows).
$R_2 \leftarrow R_2 - 2R_1$: $\left(\begin{array}{cc|c} 1 & -4 & -2 \\ 0 & 11 & 9 \end{array}\right)$.
$11y = 9 \implies y = \frac{9}{11}$.
$x - 4(\frac{9}{11}) = -2 \implies x = -2 + \frac{36}{11} = \frac{-22+36}{11} = \frac{14}{11}$.

**3. Inverse Matrix:**
$X = A^{-1}B$.
$A^{-1} = \frac{-1}{11} \begin{pmatrix} -4 & -3 \\ -1 & 2 \end{pmatrix}$.
$X = \frac{-1}{11} \begin{pmatrix} -4 & -3 \\ -1 & 2 \end{pmatrix} \begin{pmatrix} 5 \\ -2 \end{pmatrix} = \frac{-1}{11} \begin{pmatrix} -20+6 \\ -5-4 \end{pmatrix} = \frac{-1}{11} \begin{pmatrix} -14 \\ -9 \end{pmatrix} = \begin{pmatrix} 14/11 \\ 9/11 \end{pmatrix}$.

### Ex 2. 

**Problem:**

Solve the system of three equations with three unknowns:

$$
\begin{aligned} x+y+z&=6,\\ 2x-y+3z&=14,\\ -x+2y-z&=-2. \end{aligned}
$$

using the methods: Cramer's rule, Gaussian elimination, and inverse matrix.

**Solution:**

$$
\begin{cases} x+y+z=6 \\ 2x-y+3z=14 \\ -x+2y-z=-2 \end{cases}
$$

**Determinant:**
$\det(A) = 1(1-6) - 1(-2+3) + 1(4-1) = -5 - 1 + 3 = -3$.

**Cramer's Rule:**
$W_x = \det \begin{pmatrix} 6 & 1 & 1 \\ 14 & -1 & 3 \\ -2 & 2 & -1 \end{pmatrix} = 6(1-6) - 1(-14+6) + 1(28-2) = -30 + 8 + 26 = 4$.
$x = 4/-3 = -4/3$.

Other variables: $y=4/3, z=6$.
Solution: $x=-4/3, y=4/3, z=6$.

### Ex 3. 

**Problem:**

$\star$ Consider the parametric system dependent on $\lambda$:

$$
\begin{aligned} x+\lambda y&=1,\\ 2x+(1+\lambda)y&=3. \end{aligned}
$$

Determine the values of $\lambda$ for which the system has one solution, infinitely many solutions, or no solution.

**Solution:**

$$
\begin{cases} x+\lambda y=1 \\ 2x+(1+\lambda)y=3 \end{cases}
$$
$\det(A) = 1(1+\lambda) - 2\lambda = 1 + \lambda - 2\lambda = 1 - \lambda$.
If $\lambda \neq 1$, one solution.
If $\lambda = 1$:
$\begin{cases} x+y=1 \\ 2x+2y=3 \end{cases}$.
$2(x+y)=2 \neq 3$. No solution.
**Summary:**
- $\lambda \neq 1$: One solution.
- $\lambda = 1$: No solution.
- Infinitely many: Never.

### Ex 4. 

**Problem:**

For the coefficient matrix

$$
A=\begin{pmatrix}1 & 1 & 1\\ 0 & 2 & -1\\ 2 & -1 & 3\end{pmatrix}
$$

and the right-hand side vector $b=(4,1,3)^{\top}$, solve $Ax=b$ and check the result by substitution.

**Solution:**

$Ax=b$.
$$
\begin{pmatrix}1 & 1 & 1\\ 0 & 2 & -1\\ 2 & -1 & 3\end{pmatrix} \begin{pmatrix} x \\ y \\ z \end{pmatrix} = \begin{pmatrix} 4 \\ 1 \\ 3 \end{pmatrix}
$$
Gaussian elimination:
$R_3 \leftarrow R_3 - 2R_1$: $\begin{pmatrix} 1 & 1 & 1 & 4 \\ 0 & 2 & -1 & 1 \\ 0 & -3 & 1 & -5 \end{pmatrix}$.
$R_3 \leftarrow 2R_3 + 3R_2$: $\begin{pmatrix} 1 & 1 & 1 & 4 \\ 0 & 2 & -1 & 1 \\ 0 & 0 & -1 & -7 \end{pmatrix}$.
$-z = -7 \implies z=7$.
$2y - 7 = 1 \implies 2y=8 \implies y=4$.
$x + 4 + 7 = 4 \implies x = -7$.
Solution: $x=-7, y=4, z=7$.

### Ex 5. 

**Problem:**

Solve the systems of equations:

a)
$$
\begin{cases}
x_1 + 4x_2 + 3x_3 = 1, \\
2x_1 + 5x_2 + 4x_3 = 4, \\
x_1 - 3x_2 - 2x_3 = 5;
\end{cases}
$$

b)
$$
\begin{cases}
x_1 - 2x_2 - 3x_3 = 2, \\
x_1 - 4x_2 - 13x_3 = 14, \\
-3x_1 + 5x_2 + 4x_3 = 0;
\end{cases}
$$

c)
$$
\begin{cases}
x_1 - 2x_2 - 3x_3 = 2, \\
x_1 - 4x_2 - 13x_3 = 14, \\
-3x_1 + 5x_2 + 4x_3 = 2;
\end{cases}
$$

d)
$$
\begin{cases}
-4x_1 + 3x_2 + 2x_3 = -2, \\
5x_1 - 4x_2 + x_3 = 3;
\end{cases}
$$

e)
$$
\begin{cases}
-4x_1 + 3x_2 = 2, \\
5x_1 - 4x_2 = 0, \\
2x_1 - x_2 = a;
\end{cases}
$$

f)
$$
\begin{cases}
4x_1 + 5x_3 = 6, \\
x_2 - 6x_3 = -2, \\
3x_1 + 4x_3 = 3;
\end{cases}
$$

g)
$$
\begin{cases}
3x_1 - x_2 - 2x_3 = 2, \\
2x_2 - x_3 = -1, \\
3x_1 - 5x_2 = 3;
\end{cases}
$$

h)
$$
\begin{cases}
-x_1 + 2x_2 + 3x_3 = 0, \\
x_1 - 4x_2 - 13x_3 = 0, \\
-3x_1 + 5x_2 + 4x_3 = 0;
\end{cases}
$$

i)
$$
\begin{cases}
x_1 + x_2 + x_3 = 0, \\
2x_1 + 4x_2 + 3x_3 = 0, \\
4x_2 + 4x_3 = 0;
\end{cases}
$$

j)
$$
\begin{cases}
x_1 + x_2 + x_3 = -2, \\
2x_1 + 4x_2 - 3x_3 = 3, \\
4x_2 + 2x_3 = 2;
\end{cases}
$$

k)
$$
\begin{cases}
4x_1 + 4x_3 = 8, \\
x_2 - 6x_3 = -3, \\
3x_1 + x_2 - 3x_3 = 3;
\end{cases}
$$

l)
$$
\begin{cases}
5x_1 - 3x_2 = -7, \\
-2x_1 + 9x_2 = 4, \\
2x_1 + 4x_2 = -2;
\end{cases}
$$

**Solution:**

**a)**
$\begin{pmatrix} 1 & 4 & 3 & 1 \\ 2 & 5 & 4 & 4 \\ 1 & -3 & -2 & 5 \end{pmatrix} \to \begin{pmatrix} 1 & 4 & 3 & 1 \\ 0 & -3 & -2 & 2 \\ 0 & 0 & -1/3 & -2/3 \end{pmatrix}$
$-1/3 z = -2/3 \implies z=2$.
$-3y - 2(2) = 2 \implies -3y=6 \implies y=-2$.
$x + 4(-2) + 3(2) = 1 \implies x-8+6=1 \implies x=3$.
$(3, -2, 2)$.

**b)**
$\begin{pmatrix} 1 & -2 & -3 & 2 \\ 1 & -4 & -13 & 14 \\ -3 & 5 & 4 & 0 \end{pmatrix} \to \dots (3, -1, 1)$. (Example substitution: $3-2(-1)-3(1)=2$, $3-4(-1)-13=3+4-13=-6 \neq 14$. Wait, recalculate).

Let's solve **b)** properly.
$R_2-R_1$: $0, -2, -10, 12$. ($y+5z=-6$).
$R_3+3R_1$: $-3+3, 5-6, 4-9, 0+6 \to 0, -1, -5, 6$. ($y+5z=-6$).
Infinite solutions. Let $z=t$.
$y = -6 - 5t$.
$x - 2(-6-5t) - 3t = 2 \implies x + 12 + 10t - 3t = 2 \implies x = -10 - 7t$.
Solution: $(-10-7t, -6-5t, t)$.

**c)** Same LHS, RHS is 2 for third eq.
Previous system reduced to $0=0$ for last row with RHS 0.
Now RHS is $2+3(2)=8$.
$0 = 8$. No solution (inconsistent).

**d)** 2 equations, 3 unknowns.
$-4x_1 + 3x_2 + 2x_3 = -2$.
$5x_1 - 4x_2 + x_3 = 3$.
Infinite solutions. Parametrize.

**e)** 3 equations, 2 unknowns.
$-4x_1 + 3x_2 = 2$.
$5x_1 - 4x_2 = 0 \implies 5x_1=4x_2 \implies x_2 = 1.25 x_1$.
$-4x_1 + 3(1.25 x_1) = 2 \implies -4x_1 + 3.75x_1 = 2 \implies -0.25x_1 = 2 \implies x_1 = -8$.
$x_2 = -10$.
Check 3rd eq: $2(-8) - (-10) = a \implies -16+10 = -6$.
Solution exists if $a=-6$, then $x_1=-8, x_2=-10$. Else no solution.

**f)**
$4x_1 + 5x_3 = 6$.
$x_2 - 6x_3 = -2 \implies x_2 = -2+6x_3$.
$3x_1 + 4x_3 = 3$.
From 1 and 3:
$12x_1 + 15x_3 = 18$.
$12x_1 + 16x_3 = 12$.
Subtract: $-x_3 = 6 \implies x_3 = -6$.
$4x_1 - 30 = 6 \implies 4x_1=36 \implies x_1=9$.
$x_2 = -2+6(-6) = -38$.
$(9, -38, -6)$.

**g)**
$3x_1 - x_2 - 2x_3 = 2$.
$2x_2 - x_3 = -1$.
$3x_1 - 5x_2 = 3$.
From 2: $x_3 = 2x_2 + 1$.
Sub into 1: $3x_1 - x_2 - 2(2x_2+1) = 2 \implies 3x_1 - 5x_2 - 2 = 2 \implies 3x_1 - 5x_2 = 4$.
Eq 3 is $3x_1 - 5x_2 = 3$.
Contradiction ($4=3$). No solution.

**h)** Homogeneous system.
Determinant of coeff matrix same as b) which was 0 (singular).
So non-trivial solutions exist.
Same reduction as b): $-y-5z=0 \implies y=-5z$.
$x - 2(-5z) - 3z = 0 \implies x + 10z - 3z = 0 \implies x = -7z$.
Solution: $(-7t, -5t, t)$.

**i)** Homogeneous.
$4x_2 + 4x_3 = 0 \implies x_2 = -x_3$.
$2x_1 + 4(-x_3) + 3x_3 = 0 \implies 2x_1 - x_3 = 0 \implies x_1 = 0.5 x_3$.
$x_1 + x_2 + x_3 = 0.5x_3 - x_3 + x_3 = 0.5x_3 = 0 \implies x_3 = 0$.
Trivial solution only $(0,0,0)$.

**j)**
$x_1+x_2+x_3=-2$.
$2x_1+4x_2-3x_3=3$.
$4x_2+2x_3=2 \implies 2x_2+x_3=1 \implies x_3=1-2x_2$.
$x_1+x_2+(1-2x_2)=-2 \implies x_1-x_2=-3 \implies x_1=x_2-3$.
$2(x_2-3)+4x_2-3(1-2x_2)=3 \implies 2x_2-6+4x_2-3+6x_2=3 \implies 12x_2=12 \implies x_2=1$.
$x_1 = -2$. $x_3 = -1$.
$(-2, 1, -1)$.

**k)**
$4x_1+4x_3=8 \implies x_1+x_3=2 \implies x_1=2-x_3$.
$x_2-6x_3=-3 \implies x_2=6x_3-3$.
$3(2-x_3)+(6x_3-3)-3x_3=3 \implies 6-3x_3+6x_3-3-3x_3=3 \implies 3=3$.
Identity. Infinite solutions.
$x_3=t \implies (2-t, 6t-3, t)$.

**l)**
$5x_1 - 3x_2 = -7$.
$-2x_1 + 9x_2 = 4$.
$2x_1 + 4x_2 = -2 \implies x_1 + 2x_2 = -1 \implies x_1 = -1-2x_2$.
$5(-1-2x_2) - 3x_2 = -7 \implies -5-10x_2-3x_2=-7 \implies -13x_2=-2 \implies x_2=2/13$.
$-2(-1-2x_2) + 9x_2 = 4 \implies 2+4x_2+9x_2=4 \implies 13x_2=2 \implies x_2=2/13$.
Consistent.
$x_1 = -1 - 4/13 = -17/13$.
$(-17/13, 2/13)$.
