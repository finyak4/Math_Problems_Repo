## Determinants - Solutions

### Ex 1. 

**Problem:**

Calculate the determinant of the matrix

$$
A=\begin{pmatrix}
2 & 3 & 1\\\\
0 & -1 & 4\\\\
5 & 2 & 0
\end{pmatrix}
\quad
B=\begin{pmatrix}
1 & 2 & 2\\\\
4 & 0 & 0\\\\
7 & 8 & 9
\end{pmatrix}
\qquad
C=\begin{pmatrix}
3 & 0 & 2\\\\
2 & 0 & -2\\\\
0 & 1 & 1
\end{pmatrix}
$$

using Sarrus' rule.

**Solution:**

**Calculate determinant of A:**
$$
\begin{aligned}
\det(A) &= (2 \cdot (-1) \cdot 0) + (3 \cdot 4 \cdot 5) + (1 \cdot 0 \cdot 2) - (1 \cdot (-1) \cdot 5) - (2 \cdot 4 \cdot 2) - (3 \cdot 0 \cdot 0) \\\\
&= 0 + 60 + 0 - (-5) - 16 - 0 \\\\
&= 60 + 5 - 16 = 49
\end{aligned}
$$

**Calculate determinant of B:**
$$
\begin{aligned}
\det(B) &= (1 \cdot 0 \cdot 9) + (2 \cdot 0 \cdot 7) + (2 \cdot 4 \cdot 8) - (2 \cdot 0 \cdot 7) - (1 \cdot 0 \cdot 8) - (2 \cdot 4 \cdot 9) \\\\
&= 0 + 0 + 64 - 0 - 0 - 72 \\\\
&= -8
\end{aligned}
$$

**Calculate determinant of C:**
$$
\begin{aligned}
\det(C) &= (3 \cdot 0 \cdot 1) + (0 \cdot (-2) \cdot 0) + (2 \cdot 2 \cdot 1) - (2 \cdot 0 \cdot 0) - (3 \cdot (-2) \cdot 1) - (0 \cdot 2 \cdot 1) \\\\
&= 0 + 0 + 4 - 0 - (-6) - 0 \\\\
&= 4 + 6 = 10
\end{aligned}
$$

### Ex 2. 

**Problem:**

Determine the determinants using Laplace expansion:

$$
A=\begin{pmatrix}
1
\end{pmatrix}
\quad
B=\begin{pmatrix}
1 & 0 & 2\\\\
3 & 1 & 0\\\\
4 & 5 & 6
\end{pmatrix}
\quad
C=\begin{pmatrix}
1 & 2 & 3 & 4\\\\
0 & 1 & 0 & 0\\\\
0 & 0 & 1 & 1\\\\
0 & 0 & 0 & 2
\end{pmatrix}
$$

**Solution:**

**Matrix A:**
$A=(1)$. $\det(A) = 1$.

**Matrix B:**
Laplace expansion along the first row:
$$
\begin{aligned}
\det(B) &= 1 \cdot \begin{vmatrix} 1 & 0 \\\\ 5 & 6 \end{vmatrix} - 0 \cdot \begin{vmatrix} 3 & 0 \\\\ 4 & 6 \end{vmatrix} + 2 \cdot \begin{vmatrix} 3 & 1 \\\\ 4 & 5 \end{vmatrix} \\\\
&= 1(6 - 0) - 0 + 2(15 - 4) = 6 + 2(11) = 6 + 22 = 28
\end{aligned}
$$

**Matrix C:**
This is an upper triangular matrix. The determinant is the product of the diagonal elements:
$$
\det(C) = 1 \cdot 1 \cdot 1 \cdot 2 = 2
$$

### Ex 3. 

**Problem:**

Show that if two rows in a matrix are equal, then the determinant is equal to zero. Give an example of a $3\times3$ matrix with two equal rows and calculate its determinant. Justify why this happens.

**Solution:**

**Property:** If two rows in a matrix are equal, the determinant is zero.
**Justification:** Swapping two rows reverses the sign of the determinant ($\det(A') = -\det(A)$). If two rows are identical, swapping them results in the same matrix ($A' = A$), so $\det(A) = -\det(A)$, which implies $2\det(A) = 0 \implies \det(A) = 0$.

**Example:**
$$
A = \begin{pmatrix} 1 & 2 & 3 \\\\ 1 & 2 & 3 \\\\ 4 & 5 & 6 \end{pmatrix}
$$
Calculating determinant (e.g., expansion along row 3):
$$
\det(A) = 4(6-6) - 5(3-3) + 6(2-2) = 0
$$

### Ex 4. 

**Problem:**

Calculate the determinant of the triangular matrix $T$ with diagonal elements $(3,-2,5,1)$.

**Solution:**

$$
\det(T) = 3 \cdot (-2) \cdot 5 \cdot 1 = -30
$$

### Ex 5. 

**Problem:**

For the matrix dependent on parameter $t$:

$$
M(t)=\begin{pmatrix}
t & 1\\\\
2 & t\\\\
\end{pmatrix}
$$

calculate $\det(M(t))$ and find the values of $t$ for which the matrix is singular.

**Solution:**

$$
\det(M(t)) = t \cdot t - 1 \cdot 2 = t^2 - 2
$$

The matrix is singular when $\det(M(t)) = 0$:

$$
t^2 - 2 = 0 \implies t^2 = 2 \implies t = \sqrt{2} \quad \text{or} \quad t = -\sqrt{2}
$$

### Ex 6. 

**Problem:**

Solve the equation

$$
\det\begin{pmatrix}
x & 3\\\\
2 & x
\end{pmatrix} = 0
$$

**Solution:**

$$
\det\begin{pmatrix}
x & 3\\\\
2 & x
\end{pmatrix} = x^2 - 6 = 0 \implies x^2 = 6 \implies x = \pm\sqrt{6}
$$

### Ex 7. 

**Problem:**

$\star$ Solve the equation

$$
\det\begin{pmatrix}
x & 3\\\\
2 & -x
\end{pmatrix} = 0
$$

**Solution:**

$$
\det\begin{pmatrix}
x & 3\\\\
2 & -x
\end{pmatrix} = -x^2 - 6 = 0 \implies x^2 = -6
$$
No real solution. Complex solutions: $x = \pm i\sqrt{6}$.

### Ex 8. 

**Problem:**

Calculate the determinant of the matrix

$$
\begin{vmatrix}
x & y & x+y \\\\
y & x+y & x \\\\
x+y & x & y
\end{vmatrix}
$$

**Solution:**

Add Col 2 and Col 3 to Col 1 ($C_1 \leftarrow C_1+C_2+C_3$):
$$
D = \begin{vmatrix}
2(x+y) & y & x+y \\\\
2(x+y) & x+y & x \\\\
2(x+y) & x & y
\end{vmatrix} = 2(x+y) \begin{vmatrix}
1 & y & x+y \\\\
1 & x+y & x \\\\
1 & x & y
\end{vmatrix}
$$
Perform $R_2 \leftarrow R_2-R_1$ and $R_3 \leftarrow R_3-R_1$:
$$
= 2(x+y) \begin{vmatrix}
1 & y & x+y \\\\
0 & x & -y \\\\
0 & x-y & -x
\end{vmatrix}
$$
Expand along first col:
$$
\begin{aligned}
D &= 2(x+y) \cdot [x(-x) - (-y)(x-y)] = 2(x+y) [-x^2 - (-xy + y^2)] \\\\
&= 2(x+y)(-x^2 + xy - y^2) = -2(x+y)(x^2 - xy + y^2) = -2(x^3 + y^3)
\end{aligned}
$$

### Ex 9. 

**Problem:**

Show that the equality holds

$$
\begin{vmatrix}
1 & 1 & 1 \\\\
x & y & z \\\\
x^2 & y^2 & z^2
\end{vmatrix}
= (z-x)(z-y)(y-x)
$$

Prove a similar equality for the determinant

$$
\begin{vmatrix}
1 & 1 & 1 & 1 \\\\
x & y & z & u \\\\
x^2 & y^2 & z^2 & u^2 \\\\
x^3 & y^3 & z^3 & u^3
\end{vmatrix}
$$

**Solution:**

**Vandermonde Determinant:**
$$
V_3 = \begin{vmatrix}
1 & 1 & 1 \\\\
x & y & z \\\\
x^2 & y^2 & z^2
\end{vmatrix}
$$
Perform column operations $C_2 \leftarrow C_2-C_1$, $C_3 \leftarrow C_3-C_1$:
$$
= \begin{vmatrix}
1 & 0 & 0 \\\\
x & y-x & z-x \\\\
x^2 & y^2-x^2 & z^2-x^2
\end{vmatrix} = 1 \cdot \begin{vmatrix} y-x & z-x \\\\ (y-x)(y+x) & (z-x)(z+x) \end{vmatrix}
$$
Factor out $(y-x)$ from col 1 and $(z-x)$ from col 2:
$$
= (y-x)(z-x) \begin{vmatrix} 1 & 1 \\\\ y+x & z+x \end{vmatrix} = (y-x)(z-x) [(z+x)-(y+x)]
$$
$$
= (y-x)(z-x)(z-y)
$$
Rearranging terms matches the prompt: $(z-x)(z-y)(y-x)$.

**4x4 Case:**
$$
\det(V_4) = (y-x)(z-x)(u-x)(z-y)(u-y)(u-z)
$$
General formula: $\prod_{1 \le i < j \le n} (x_j - x_i)$.

### Ex 10. 

**Problem:**

Calculate the determinant of the matrix

$$
\begin{vmatrix}
a & a & a \\\\
-a & a & a \\\\
-a & -a & a
\end{vmatrix}
\quad
\text{\&}
\quad
\begin{vmatrix}
a & 0 & b \\\\
0 & c & 0 \\\\
d & 0 & a
\end{vmatrix}
$$

**Solution:**

**First Matrix:**
$$
D_1 = \begin{vmatrix}
a & a & a \\\\
-a & a & a \\\\
-a & -a & a
\end{vmatrix}
$$
$R_2 \leftarrow R_2+R_1$, $R_3 \leftarrow R_3+R_1$:
$$
D_1 = \begin{vmatrix}
a & a & a \\\\
0 & 2a & 2a \\\\
0 & 0 & 2a
\end{vmatrix} = a \cdot 2a \cdot 2a = 4a^3
$$

**Second Matrix:**
$$
D_2 = \begin{vmatrix}
a & 0 & b \\\\
0 & c & 0 \\\\
d & 0 & a
\end{vmatrix}
$$
Expand along second row:
$$
D_2 = c \cdot (-1)^{2+2} \begin{vmatrix} a & b \\\\ d & a \end{vmatrix} = c(a^2 - bd)
$$

### Ex 11. 

**Problem:**

Check the validity of the following relationships:

a)

$$
\begin{vmatrix}
a+b & b \\\\
c+d & d
\end{vmatrix}
=
\begin{vmatrix}
a & b \\\\
c & d
\end{vmatrix}
$$

b)

$$
\begin{vmatrix}
a+bx & b \\\\
c+dx & d
\end{vmatrix}
=
\begin{vmatrix}
a & b \\\\
c & d
\end{vmatrix}
$$

**Solution:**

**a)**
$$
\begin{vmatrix}
a+b & b \\\\
c+d & d
\end{vmatrix}
$$
Operation $C_1 \leftarrow C_1 - C_2$:
$$
= \begin{vmatrix}
a & b \\\\
c & d
\end{vmatrix}
$$
**True.**

**b)**
$$
\begin{vmatrix}
a+bx & b \\\\
c+dx & d
\end{vmatrix}
$$
Operation $C_1 \leftarrow C_1 - xC_2$:
$$
= \begin{vmatrix}
a & b \\\\
c & d
\end{vmatrix}
$$
**True.**
