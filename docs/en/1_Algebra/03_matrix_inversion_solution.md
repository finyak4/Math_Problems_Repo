## Matrix Inversion - Solutions

### Ex 1. 

**Problem:**

Find the inverse matrix using the formula for a $2\times2$ matrix

$$
A=\begin{pmatrix}2 & 1\\ 5 & 3\end{pmatrix}
\qquad
B=\begin{pmatrix}0 & 1\\ 1 & 0\end{pmatrix}
\qquad
C=\begin{pmatrix}4 & 7\\ 2 & 6\end{pmatrix}
$$

**Solution:**

Formula for inverse of $2\times2$ matrix $A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$:
$$
A^{-1} = \frac{1}{\det(A)} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix}
$$

**A:**
$$
A=\begin{pmatrix}2 & 1\\ 5 & 3\end{pmatrix}, \quad \det(A) = 6 - 5 = 1
$$
$$
A^{-1} = \frac{1}{1} \begin{pmatrix} 3 & -1 \\ -5 & 2 \end{pmatrix} = \begin{pmatrix} 3 & -1 \\ -5 & 2 \end{pmatrix}
$$

**B:**
$$
B=\begin{pmatrix}0 & 1\\ 1 & 0\end{pmatrix}, \quad \det(B) = 0 - 1 = -1
$$
$$
B^{-1} = \frac{1}{-1} \begin{pmatrix} 0 & -1 \\ -1 & 0 \end{pmatrix} = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix} = B
$$

**C:**
$$
C=\begin{pmatrix}4 & 7\\ 2 & 6\end{pmatrix}, \quad \det(C) = 24 - 14 = 10
$$
$$
C^{-1} = \frac{1}{10} \begin{pmatrix} 6 & -7 \\ -2 & 4 \end{pmatrix} = \begin{pmatrix} 0.6 & -0.7 \\ -0.2 & 0.4 \end{pmatrix}
$$

### Ex 2. 

**Problem:**

For the matrices

$$
A=\begin{pmatrix}1 & 2\\ 2 & 5\end{pmatrix}
\quad
B=\begin{pmatrix}12& 5\\ 7 & 3\end{pmatrix}
\quad
C=\begin{pmatrix}1 & 2 & 3\\ 0 & 1 & 4\\ 5 & 6 & 0\end{pmatrix}
\quad
D=\begin{pmatrix}2 & 0 & 1\\ 1 & 3 & 0\\ 0 & 4 & 5\end{pmatrix}
$$

calculate the inverse matrices using the methods:

- augmenting with the identity matrix and performing Gauss-Jordan elimination,
- using the formula with cofactor matrices (adjugate matrix)

So for each matrix provide two methods of calculating the inverse matrix (if it exists).

**Solution:**

**Matrix A and B** solved similarly to Ex 1.

$A^{-1} = \begin{pmatrix} 5 & -2 \\ -2 & 1 \end{pmatrix}$

$B^{-1} = \frac{1}{36-35} \begin{pmatrix} 3 & -5 \\ -7 & 12 \end{pmatrix} = \begin{pmatrix} 3 & -5 \\ -7 & 12 \end{pmatrix}$

**Matrix C:**
$$
C=\begin{pmatrix}1 & 2 & 3\\ 0 & 1 & 4\\ 5 & 6 & 0\end{pmatrix}
$$
$\det(C) = 1(0-24) - 2(0-20) + 3(0-5) = -24 + 40 - 15 = 1$.

Cofactor matrix:
$$
\begin{pmatrix}
-24 & 20 & -5 \\
18 & -15 & 4 \\
5 & -4 & 1
\end{pmatrix}
$$
Inverse (transpose of cofactors / det):
$$
C^{-1} = \begin{pmatrix} -24 & 18 & 5 \\ 20 & -15 & -4 \\ -5 & 4 & 1 \end{pmatrix}
$$

**Matrix D:**
$$
D=\begin{pmatrix}2 & 0 & 1\\ 1 & 3 & 0\\ 0 & 4 & 5\end{pmatrix}
$$
$\det(D) = 2(15-0) + 1(4-0) = 30+4=34$.
Inverse:
$$
D^{-1} = \frac{1}{34} \begin{pmatrix} 15 & 4 & -3 \\ -5 & 10 & 1 \\ 4 & -8 & 6 \end{pmatrix}
$$

### Ex 3. 

**Problem:**

Check if the matrix

$$
H=\begin{pmatrix}1 & 2 & 3\\ 2 & 4 & 6\\ 0 & 1 & 1\end{pmatrix}
$$

is invertible. Justify the answer (use the determinant). Could this have been noticed without calculating the determinant? What would have to happen for the matrix to be invertible?

**Solution:**

$$
H=\begin{pmatrix}1 & 2 & 3\\ 2 & 4 & 6\\ 0 & 1 & 1\end{pmatrix}
$$
Observe row 2 is $2 \times$ row 1 ($R_2 = 2R_1$).
Therefore, the rows are linearly dependent, so $\det(H) = 0$.
The matrix is **not invertble** (singular).
This could be noticed without calculating the determinant. For a matrix to be invertible, its rows (and columns) must be linearly independent.

### Ex 4. 

**Problem:**

For a matrix $A$ satisfying $A^{2}=I$ (so-called involution), show that $A^{-1}=A$. Give an example of a non-trivial $2\times2$ matrix satisfying this condition (other than $I$ and $-I$). How many such matrices are there?

**Solution:**

If $A^2 = I$, then multiplying by $A^{-1}$ gives $A = A^{-1}$.
Example: $A = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$. Check $A^2 = I$.
Other examples: reflection matrices. Infinitely many.

### Ex 5. 

**Problem:**

Calculate the inverse of the diagonal matrix $D=\operatorname{diag}(2,5,-3,1)$, if it exists. Discuss the condition for the existence of an inverse for a diagonal matrix.

**Solution:**

$$
D=\operatorname{diag}(2,5,-3,1)
$$
$$
D^{-1} = \operatorname{diag}(\frac{1}{2}, \frac{1}{5}, -\frac{1}{3}, 1)
$$
Condition: All diagonal elements must be non-zero.

### Ex 6. 

**Problem:**

Solve the matrix equations:

a) 

$$
\begin{bmatrix} 2 & 5 \\\ 1 & 3 \end{bmatrix} \cdot X = \begin{bmatrix} 4 & -6 \\\ 2 & 1 \end{bmatrix}
$$

b) 

$$
\begin{bmatrix} 2 & 1 \\\ 5 & 3 \end{bmatrix} \cdot X = \begin{bmatrix} 1 & 2 \\\ 3 & 4 \end{bmatrix}
$$

c) 

$$
X \cdot \begin{bmatrix} 1 & 1 & -1 \\\ 2 & 1 & 0 \\\ 1 & -1 & 1 \end{bmatrix} = \begin{bmatrix} 1 & -3 & 3 \\\ 4 & 3 & 2 \\\ 1 & -2 & 5 \end{bmatrix}
$$

d) 

$$
\begin{bmatrix} 3 & 2 & 3 \\\ 1 & 1 & 2 \\\ 3 & 2 & 4 \end{bmatrix} \cdot X = \begin{bmatrix} 1 & 2 & 3 \\\ 1 & -1 & 2 \\\ 2 & 2 & 4 \end{bmatrix}
$$

**Solution:**

**a)**
$$
\begin{bmatrix} 2 & 5 \\\ 1 & 3 \end{bmatrix} X = \begin{bmatrix} 4 & -6 \\\ 2 & 1 \end{bmatrix}
$$
$X = A^{-1}B$. $A^{-1} = \begin{bmatrix} 3 & -5 \\\ -1 & 2 \end{bmatrix}$.
$$
X = \begin{bmatrix} 3 & -5 \\\ -1 & 2 \end{bmatrix} \begin{bmatrix} 4 & -6 \\\ 2 & 1 \end{bmatrix} = \begin{bmatrix} 12-10 & -18-5 \\\ -4+4 & 6+2 \end{bmatrix} = \begin{bmatrix} 2 & -23 \\\ 0 & 8 \end{bmatrix}
$$

**b)**
$$
\begin{bmatrix} 2 & 1 \\\ 5 & 3 \end{bmatrix} X = \begin{bmatrix} 1 & 2 \\\ 3 & 4 \end{bmatrix}
$$
$A^{-1} = \begin{bmatrix} 3 & -1 \\\ -5 & 2 \end{bmatrix}$.
$$
X = \begin{bmatrix} 3 & -1 \\\ -5 & 2 \end{bmatrix} \begin{bmatrix} 1 & 2 \\\ 3 & 4 \end{bmatrix} = \begin{bmatrix} 0 & 2 \\\ 1 & -2 \end{bmatrix}
$$

**c)**
$$
X A = B \implies X = B A^{-1}
$$
$A = \begin{bmatrix} 1 & 1 & -1 \\\ 2 & 1 & 0 \\\ 1 & -1 & 1 \end{bmatrix}$. Determine $A^{-1}$ (Ex 2 style). $\det(A)=2$.
$A^{-1} = \frac{1}{2} \begin{bmatrix} 1 & 0 & 1 \\\ -2 & 2 & -2 \\\ -3 & 2 & -1 \end{bmatrix}$.
$$
X = \begin{bmatrix} 1 & -3 & 3 \\\ 4 & 3 & 2 \\\ 1 & -2 & 5 \end{bmatrix} \cdot \frac{1}{2} \begin{bmatrix} 1 & 0 & 1 \\\ -2 & 2 & -2 \\\ -3 & 2 & -1 \end{bmatrix} = \frac{1}{2} \begin{bmatrix} -2 & 0 & 4 \\\ -8 & 10 & -4 \\\ -10 & 6 & 0 \end{bmatrix} = \begin{bmatrix} -1 & 0 & 2 \\\ -4 & 5 & -2 \\\ -5 & 3 & 0 \end{bmatrix}
$$

**d)**
$$
A X = B \implies X = A^{-1} B
$$
$A = \begin{bmatrix} 3 & 2 & 3 \\\ 1 & 1 & 2 \\\ 3 & 2 & 4 \end{bmatrix}$. $\det(A)=1$.
$A^{-1} = \begin{bmatrix} 0 & -2 & 1 \\\ 2 & 3 & -3 \\\ -1 & 0 & 1 \end{bmatrix}$.
$$
X = \begin{bmatrix} 0 & -2 & 1 \\\ 2 & 3 & -3 \\\ -1 & 0 & 1 \end{bmatrix} \begin{bmatrix} 1 & 2 & 3 \\\ 1 & -1 & 2 \\\ 2 & 2 & 4 \end{bmatrix} = \begin{bmatrix} 0 & 4 & 0 \\\ -1 & -5 & 0 \\\ 1 & 0 & 1 \end{bmatrix}
$$
