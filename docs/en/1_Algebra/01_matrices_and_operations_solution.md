## Matrices and Basic Operations - Solutions

### Ex 1.

**Problem:**

For the matrices

$$
A=\begin{pmatrix}1 & 2\\ 3 & 4\end{pmatrix} \quad \text{and} \quad B=\begin{pmatrix}0 & -1\\ 2 & 1\end{pmatrix}
$$

calculate $A+B$, $A-B$, $2A$, $3B-2A$, $A\cdot B$, and check if $A\cdot B = B\cdot A$.

**Solution:**

**1. Calculate $A+B$**

$$
A+B = \begin{pmatrix}1+0 & 2+(-1)\\\ 3+2 & 4+1\end{pmatrix} = \begin{pmatrix}1 & 1\\\ 5 & 5\end{pmatrix}
$$

**2. Calculate $A-B$**

$$
A-B = \begin{pmatrix}1-0 & 2-(-1)\\\ 3-2 & 4-1\end{pmatrix} = \begin{pmatrix}1 & 3\\\ 1 & 3\end{pmatrix}
$$

**3. Calculate $2A$**

$$
2A = \begin{pmatrix}2\cdot1 & 2\cdot2\\\ 2\cdot3 & 2\cdot4\end{pmatrix} = \begin{pmatrix}2 & 4\\\ 6 & 8\end{pmatrix}
$$

**4. Calculate $3B-2A$**

$$
3B = \begin{pmatrix}0 & -3\\\ 6 & 3\end{pmatrix}
$$

$$
3B-2A = \begin{pmatrix}0-2 & -3-4\\\ 6-6 & 3-8\end{pmatrix} = \begin{pmatrix}-2 & -7\\\ 0 & -5\end{pmatrix}
$$

**5. Calculate $A\cdot B$**

$$
A\cdot B = \begin{pmatrix}1\cdot0 + 2\cdot2 & 1\cdot(-1) + 2\cdot1\\\ 3\cdot0 + 4\cdot2 & 3\cdot(-1) + 4\cdot1\end{pmatrix} = \begin{pmatrix}4 & 1\\\ 8 & 1\end{pmatrix}
$$

**6. Check if $A\cdot B = B\cdot A$**

$$
B\cdot A = \begin{pmatrix}0\cdot1 + (-1)\cdot3 & 0\cdot2 + (-1)\cdot4\\\ 2\cdot1 + 1\cdot3 & 2\cdot2 + 1\cdot4\end{pmatrix} = \begin{pmatrix}-3 & -4\\\ 5 & 8\end{pmatrix}
$$
$$
A\cdot B = \begin{pmatrix}4 & 1\\\ 8 & 1\end{pmatrix} \neq \begin{pmatrix}-3 & -4\\\ 5 & 8\end{pmatrix}
$$
So, $A\cdot B \neq B\cdot A$.

### Ex 2.

**Problem:**

For the matrices

$$
A=\begin{pmatrix}1 & 0\\\ 0 & 2\end{pmatrix}, \quad B =\begin{pmatrix}2 & 0\\\ 0 & 4\end{pmatrix}, \quad C=\begin{pmatrix}4 & 0\\\ 0 & 8\end{pmatrix}, \quad D=\begin{pmatrix}8 & 0\\\ 0 & 16\end{pmatrix}
$$

check if $A\cdot B\cdot C\cdot D = B\cdot A\cdot D\cdot C = D\cdot C\cdot B\cdot A$.

**Solution:**

The product of diagonal matrices is commutative.
$$
\begin{aligned}
A\cdot B\cdot C\cdot D &= \operatorname{diag}(1\cdot2\cdot4\cdot8, 2\cdot4\cdot8\cdot16) \\\
&= \operatorname{diag}(64, 1024) = \begin{pmatrix}64 & 0\\\ 0 & 1024\end{pmatrix}
\end{aligned}
$$
The result is the same for any order.

### Ex 3.

**Problem:**

Given $C=\begin{pmatrix} 1 & 0 & 2\\\ -1 & 3 & 1\\\ 0 & 2 & -1 \end{pmatrix}$. Swap $R_1 \leftrightarrow R_3$, then $R_2 \leftarrow R_2 + 2R_1$.

**Solution:**

**Step 1:** $R_1 \leftrightarrow R_3$
$$
C' = \begin{pmatrix} 0 & 2 & -1\\\ -1 & 3 & 1\\\ 1 & 0 & 2 \end{pmatrix}
$$

**Step 2:** $R_2 \leftarrow R_2 + 2R_1$ (using new $R_1$)
$R_2 = (-1, 3, 1) + 2(0, 2, -1) = (-1, 7, -1)$.
$$
C'' = \begin{pmatrix} 0 & 2 & -1\\\ -1 & 7 & -1\\\ 1 & 0 & 2 \end{pmatrix}
$$

### Ex 4.

**Problem:**

$u=(1,-2,3)^{\top}$, $v=(2,0,-1)^{\top}$. Calculate $u+v$, $u-v$, $u\,v^{\top}$, $v\,u^{\top}$. Rank of $u\,v^{\top}$?

**Solution:**

**1. $u+v$ and $u-v$**
$$
u+v = \begin{pmatrix}3\\\ -2\\\ 2\end{pmatrix}, \quad u-v = \begin{pmatrix}-1\\\ -2\\\ 4\end{pmatrix}
$$

**2. $u\,v^{\top}$**
$$
u\,v^{\top} = \begin{pmatrix}1\\\ -2\\\ 3\end{pmatrix} \begin{pmatrix}2 & 0 & -1\end{pmatrix} = \begin{pmatrix} 2 & 0 & -1\\\ -4 & 0 & 2\\\ 6 & 0 & -3 \end{pmatrix}
$$
Rank is 1.

**3. $v\,u^{\top}$**
$$
v\,u^{\top} = \begin{pmatrix}2\\\ 0\\\ -1\end{pmatrix} \begin{pmatrix}1 & -2 & 3\end{pmatrix} = \begin{pmatrix} 2 & -4 & 6\\\ 0 & 0 & 0\\\ -1 & 2 & -3 \end{pmatrix}
$$

### Ex 5.

**Problem:**

$D=\operatorname{diag}(2,-3,5)$, $E=\operatorname{diag}(a,b,c)$. Show $DE=ED$. Calculate $D^3, D^{-1}$.

**Solution:**

$DE = \operatorname{diag}(2a, -3b, 5c) = ED$.
$D^3 = \operatorname{diag}(8, -27, 125)$.
$D^{-1} = \operatorname{diag}(0.5, -1/3, 0.2)$.

### Ex 6.

**Problem:**

$$
P=\begin{pmatrix}1 & 1 & 0\\\ 0 & 1 & 1\\\ 1 & 0 & 1\end{pmatrix}
$$
Calculate $P^2, P^3$. Pattern?

**Solution:**

**Calculate $P^2$:**
$$
P^2 = \begin{pmatrix}
1\cdot 1 + 1\cdot 0 + 0\cdot 1 & 1\cdot 1 + 1\cdot 1 + 0\cdot 0 & 1\cdot 0 + 1\cdot 1 + 0\cdot 1 \\\
0\cdot 1 + 1\cdot 0 + 1\cdot 1 & 0\cdot 1 + 1\cdot 1 + 1\cdot 0 & 0\cdot 0 + 1\cdot 1 + 1\cdot 1 \\\
1\cdot 1 + 0\cdot 0 + 1\cdot 1 & 1\cdot 1 + 0\cdot 1 + 1\cdot 0 & 1\cdot 0 + 0\cdot 1 + 1\cdot 1
\end{pmatrix}
$$
$$
= \begin{pmatrix}
1 & 2 & 1 \\\
1 & 1 & 2 \\\
2 & 1 & 1
\end{pmatrix}
$$

**Calculate $P^3$:**
$$
P^3 = P^2 P = \begin{pmatrix}
1 & 2 & 1\\\
1 & 1 & 2\\\
2 & 1 & 1
\end{pmatrix} \begin{pmatrix}
1 & 1 & 0\\\
0 & 1 & 1\\\
1 & 0 & 1
\end{pmatrix}
$$
Row 1: $1(1)+2(0)+1(1)=2$; $1(1)+2(1)+1(0)=3$; $1(0)+2(1)+1(1)=3$.
Row 2: $1(1)+1(0)+2(1)=3$; $1(1)+1(1)+2(0)=2$; $1(0)+1(1)+2(1)=3$.
Row 3: $2(1)+1(0)+1(1)=3$; $2(1)+1(1)+1(0)=3$; $2(0)+1(1)+1(1)=2$.

$$
P^3 = \begin{pmatrix}
2 & 3 & 3\\\
3 & 2 & 3\\\
3 & 3 & 2
\end{pmatrix}
$$
Pattern: $P^n$ involves sums of powers of permutation matrix $K$. $P=I+K$.

### Ex 7. 

**Problem:**

Calculate $R(\theta_1)R(\theta_2)$ where $R(\theta) = \begin{pmatrix} \cos\theta & -\sin\theta \\\ \sin\theta & \cos\theta \end{pmatrix}$.

**Solution:**

$$
R(\theta_1)R(\theta_2) = \begin{pmatrix} \cos\theta_1 & -\sin\theta_1 \\\ \sin\theta_1 & \cos\theta_1 \end{pmatrix} \begin{pmatrix} \cos\theta_2 & -\sin\theta_2 \\\ \sin\theta_2 & \cos\theta_2 \end{pmatrix}
$$

Matrix multiplication ($c_i = \cos\theta_i, s_i = \sin\theta_i$):
$$
= \begin{pmatrix}
c_1 c_2 - s_1 s_2 & -c_1 s_2 - s_1 c_2 \\\
s_1 c_2 + c_1 s_2 & -s_1 s_2 + c_1 c_2
\end{pmatrix}
$$

Using addition formulas:
$$
c_1 c_2 - s_1 s_2 = \cos(\theta_1+\theta_2)
$$
$$
s_1 c_2 + c_1 s_2 = \sin(\theta_1+\theta_2)
$$

Thus:
$$
R(\theta_1)R(\theta_2) = \begin{pmatrix}
\cos(\theta_1+\theta_2) & -\sin(\theta_1+\theta_2) \\\
\sin(\theta_1+\theta_2) & \cos(\theta_1+\theta_2)
\end{pmatrix} = R(\theta_1+\theta_2)
$$

### Ex 8.

**Problem:**

Show $R(\theta) = \exp(A)$ where $A = \begin{pmatrix}0 & -\theta\\\ \theta & 0\end{pmatrix}$.

**Solution:**

Powers of $A$:
$A^1 = A$
$A^2 = -\theta^2 I$
$A^3 = -\theta^2 A$
$A^4 = \theta^4 I$

Series expansion:
$$
\exp(A) = I + A + \frac{A^2}{2!} + \frac{A^3}{3!} + \frac{A^4}{4!} + \dots
$$

Split into even and odd terms:
$$
\exp(A) = \left(I + \frac{A^2}{2!} + \frac{A^4}{4!} + \dots\right) + \left(A + \frac{A^3}{3!} + \frac{A^5}{5!} + \dots\right)
$$
$$
= I \left(1 - \frac{\theta^2}{2!} + \frac{\theta^4}{4!} - \dots\right) + \frac{A}{\theta} \left(\theta - \frac{\theta^3}{3!} + \frac{\theta^5}{5!} - \dots\right)
$$

Identifying Taylor series for $\cos\theta$ and $\sin\theta$:
$$
= I \cos\theta + \begin{pmatrix}0 & -1\\\ 1 & 0\end{pmatrix} \sin\theta
$$
$$
= \begin{pmatrix}\cos\theta & 0\\\ 0 & \cos\theta\end{pmatrix} + \begin{pmatrix}0 & -\sin\theta\\\ \sin\theta & 0\end{pmatrix} = \begin{pmatrix}\cos\theta & -\sin\theta\\\ \sin\theta & \cos\theta\end{pmatrix}
$$

### Ex 9.

**Problem:**

Pauli matrices $\sigma_x, \sigma_y, \sigma_z$. Check relations.

**Solution:**

**1. Squares**
$\sigma_x^2 = I$, $\sigma_y^2 = I$, $\sigma_z^2 = I$. (Calculation straightforward).

**2. Products**
$\sigma_x \sigma_y = i\sigma_z$.
$\sigma_y \sigma_z = i\sigma_x$.
$\sigma_z \sigma_x = i\sigma_y$.

**3. Anticommutators**
$\{\sigma_i, \sigma_j\} = \sigma_i \sigma_j + \sigma_j \sigma_i$.
For $i \neq j$, e.g., $\sigma_x \sigma_y + \sigma_y \sigma_x = i\sigma_z + (-i\sigma_z) = 0$.
For $i = j$, $2\sigma_i^2 = 2I$.
Result: $2\delta_{ij}I$.
