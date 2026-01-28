## Vectors - Solutions

### Ex 1. 

**Problem:**

For vectors in space

$$
\mathbf{u}=[1,2,-1]\quad\text{and}\quad\mathbf{v}=[2,-1,3]
$$

calculate $\mathbf{u}+\mathbf{v}$, $\mathbf{u}-\mathbf{v}$, the dot product $\mathbf{u}\cdot\mathbf{v}$, and the norms $\|\mathbf{u}\|$ and $\|\mathbf{v}\|$. Check if the vectors are orthogonal.

**Solution:**

**a) $\mathbf{u}+\mathbf{v}$**
$$
\mathbf{u}+\mathbf{v} = [1+2, 2+(-1), -1+3] = [3, 1, 2]
$$

**b) $\mathbf{u}-\mathbf{v}$**
$$
\mathbf{u}-\mathbf{v} = [1-2, 2-(-1), -1-3] = [-1, 3, -4]
$$

**c) $\mathbf{u}\cdot\mathbf{v}$**
$$
\mathbf{u}\cdot\mathbf{v} = 1\cdot2 + 2\cdot(-1) + (-1)\cdot3 = 2 - 2 - 3 = -3
$$
Since the dot product is not zero ($-3 \neq 0$), the vectors are **not orthogonal**.

**d) Norms**
$$
\|\mathbf{u}\| = \sqrt{1^2 + 2^2 + (-1)^2} = \sqrt{1 + 4 + 1} = \sqrt{6}
$$
$$
\|\mathbf{v}\| = \sqrt{2^2 + (-1)^2 + 3^2} = \sqrt{4 + 1 + 9} = \sqrt{14}
$$

### Ex 2. 

**Problem:**

For points $A(1,0,2)$, $B(3,-1,1)$, and $C(2,2,0)$, calculate vectors AB and AC and determine the angle between them.

**Solution:**

**Vectors:**
$$
\vec{AB} = B - A = [3-1, -1-0, 1-2] = [2, -1, -1]
$$
$$
\vec{AC} = C - A = [2-1, 2-0, 0-2] = [1, 2, -2]
$$

**Angle:**
$$
\cos\theta = \frac{\vec{AB} \cdot \vec{AC}}{\|\vec{AB}\| \|\vec{AC}\|}
$$
Dot product: $2\cdot1 + (-1)\cdot2 + (-1)\cdot(-2) = 2 - 2 + 2 = 2$.
Norms:
$\|\vec{AB}\| = \sqrt{4+1+1} = \sqrt{6}$.
$\|\vec{AC}\| = \sqrt{1+4+4} = \sqrt{9} = 3$.
$$
\cos\theta = \frac{2}{3\sqrt{6}} = \frac{2\sqrt{6}}{18} = \frac{\sqrt{6}}{9}
$$
$$
\theta = \arccos\left(\frac{\sqrt{6}}{9}\right)
$$

### Ex 3. 

**Problem:**

Calculate the cross product $\mathbf{u}\times\mathbf{v}$ for the vectors from Ex 1 and check if it is orthogonal to both vectors.

**Solution:**

$\mathbf{u}=[1,2,-1]$, $\mathbf{v}=[2,-1,3]$.

**Cross product:**
$$
\begin{aligned}
\mathbf{u}\times\mathbf{v} &= \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\\ 1 & 2 & -1 \\\ 2 & -1 & 3 \end{vmatrix} \\\
&= \mathbf{i}(6 - 1) - \mathbf{j}(3 - (-2)) + \mathbf{k}(-1 - 4) \\\
&= 5\mathbf{i} - 5\mathbf{j} - 5\mathbf{k} = [5, -5, -5]
\end{aligned}
$$

**Check orthogonality:**
$(\mathbf{u}\times\mathbf{v}) \cdot \mathbf{u} = 5(1) - 5(2) - 5(-1) = 5 - 10 + 5 = 0$.
$(\mathbf{u}\times\mathbf{v}) \cdot \mathbf{v} = 5(2) - 5(-1) - 5(3) = 10 + 5 - 15 = 0$.
Yes, it is orthogonal to both.

### Ex 4. 

**Problem:**

For vectors on the plane: $\mathbf{a}=[3,4]$ and $\mathbf{b}=[-4,3]$, calculate their dot product and check if they are perpendicular. Determine the projection of vector $\mathbf{a}$ onto $\mathbf{b}$.

**Solution:**

**Dot product:**
$\mathbf{a}\cdot\mathbf{b} = 3(-4) + 4(3) = -12 + 12 = 0$.
The vectors are **perpendicular**.

**Projection of $\mathbf{a}$ onto $\mathbf{b}$:**
Since they are perpendicular, the projection is the zero vector.
$$
\operatorname{proj}_{\mathbf{b}}\mathbf{a} = \frac{\mathbf{a}\cdot\mathbf{b}}{\|\mathbf{b}\|^2} \mathbf{b} = \frac{0}{25} \mathbf{b} = \mathbf{0}
$$

### Ex 5. 

**Problem:**

Calculate the length of the vector $\mathbf{c} = [1, 1]$ and find the unit vector of this vector.

**Solution:**

Length: $\|\mathbf{c}\| = \sqrt{1^2+1^2} = \sqrt{2}$.
Unit vector: $\hat{\mathbf{c}} = \frac{\mathbf{c}}{\|\mathbf{c}\|} = [\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}] = [\frac{\sqrt{2}}{2}, \frac{\sqrt{2}}{2}]$.

### Ex 6. 

**Problem:**

Calculate the length of the vector $\mathbf{c} = [1, 2, 3]$ and find the unit vector of this vector.

**Solution:**

Length: $\|\mathbf{c}\| = \sqrt{1+4+9} = \sqrt{14}$.
Unit vector: $\hat{\mathbf{c}} = [\frac{1}{\sqrt{14}}, \frac{2}{\sqrt{14}}, \frac{3}{\sqrt{14}}]$.

### Ex 7. 

**Problem:**

Calculate the area of the triangle spanned by vectors $[2, 1, 2]$ and $[-1, 1,1]$.

**Solution:**

Vectors $\mathbf{v}_1=[2, 1, 2]$ and $\mathbf{v}_2=[-1, 1, 1]$.
Area of triangle is $\frac{1}{2} \|\mathbf{v}_1 \times \mathbf{v}_2\|$.
$$
\begin{aligned}
\mathbf{v}_1 \times \mathbf{v}_2 &= \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\\ 2 & 1 & 2 \\\ -1 & 1 & 1 \end{vmatrix} \\\
&= \mathbf{i}(1-2) - \mathbf{j}(2-(-2)) + \mathbf{k}(2-(-1)) \\\
&= [-1, -4, 3]
\end{aligned}
$$
Norm: $\sqrt{(-1)^2 + (-4)^2 + 3^2} = \sqrt{1 + 16 + 9} = \sqrt{26}$.
Area = $\frac{\sqrt{26}}{2}$.

### Ex 8. 

**Problem:**

Calculate the angle in degrees between vectors $[4,2,1]$ and $[1,3,2]$.

**Solution:**

$\mathbf{a}=[4,2,1]$, $\mathbf{b}=[1,3,2]$.
$\mathbf{a}\cdot\mathbf{b} = 4(1) + 2(3) + 1(2) = 4+6+2 = 12$.
$\|\mathbf{a}\| = \sqrt{16+4+1} = \sqrt{21}$.
$\\|\mathbf{b}\| = \sqrt{1+9+4} = \sqrt{14}$.
$$
\cos\theta = \frac{12}{\sqrt{21}\sqrt{14}} = \frac{12}{\sqrt{3\cdot7 \cdot 2\cdot7}} = \frac{12}{7\sqrt{6}} = \frac{12\sqrt{6}}{42} = \frac{2\sqrt{6}}{7}
$$
$\theta = \arccos(\frac{2\sqrt{6}}{7})$.

### Ex 9. 

**Problem:**

Find the coordinates of the midpoint of the segment with endpoints $A(-1, 2)$ and $B(3, -2)$.

**Solution:**

$A(-1, 2)$ and $B(3, -2)$.
Midpoint $M = \frac{A+B}{2} = (\frac{-1+3}{2}, \frac{2-2}{2}) = (\frac{2}{2}, 0) = (1, 0)$.

### Ex 10. 

**Problem:**

For three-dimensional vectors: $\mathbf{a}=[a_x, a_y, a_z]$, $\mathbf{b}=[b_x, b_y, b_z]$, $\mathbf{c}=[c_x, c_y, c_z]$, prove that the following identity holds:

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c}) \mathbf{b} - (\mathbf{a} \cdot \mathbf{b}) \mathbf{c}.
$$

**Solution:**

To prove $\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c}) \mathbf{b} - (\mathbf{a} \cdot \mathbf{b}) \mathbf{c}$.

Consider the $i$-th component of the expression. We express the cross product using the Levi-Civita symbol $\epsilon_{ijk}$:

$$
\begin{aligned} (\mathbf{a} \times (\mathbf{b} \times \mathbf{c}))_i &= \sum_{j,k} \epsilon_{ijk} a_j (\mathbf{b} \times \mathbf{c})_k = \sum_{j,k} \epsilon_{ijk} a_j \left(\sum_{l,m} \epsilon_{klm} b_l c_m\right) \\\ &= \sum_{j,k,l,m} \epsilon_{ijk} \epsilon_{klm} a_j b_l c_m \\\ &= \sum_{j,l,m} (\delta_{il}\delta_{jm} - \delta_{im}\delta_{jl}) a_j b_l c_m \\\ &= \sum_{j,l,m} \delta_{il}\delta_{jm} a_j b_l c_m - \sum_{j,l,m} \delta_{im}\delta_{jl} a_j b_l c_m \\\ &= b_i \left(\sum_{j} a_j c_j\right) - c_i \left(\sum_{j} a_j b_j\right) \\\ &= (\mathbf{a}\cdot\mathbf{c}) b_i - (\mathbf{a}\cdot\mathbf{b}) c_i \end{aligned}
$$

This holds for all components $i$, so:
$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c}) \mathbf{b} - (\mathbf{a} \cdot \mathbf{b}) \mathbf{c}
$$
Q.E.D.

### Ex 11.  

**Problem:**

Find the most general form of a vector that is simultaneously perpendicular to

$$\mathbf{v}=[-1,3,0]\qquad and \qquad \mathbf{u}=[0,1,1]$$

**Solution:**

$\mathbf{v}=[-1,3,0]$, $\mathbf{u}=[0,1,1]$.
Vector perpendicular to both is parallel to their cross product.
$$
\begin{aligned}
\mathbf{n} = \mathbf{v} \times \mathbf{u} &= \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\\ -1 & 3 & 0 \\\ 0 & 1 & 1 \end{vmatrix} \\\
&= \mathbf{i}(3-0) - \mathbf{j}(-1-0) + \mathbf{k}(-1-0) = [3, 1, -1]
\end{aligned}
$$
Most general form: $k[3, 1, -1]$ for $k \in \mathbb{R}$.

### Ex 12.  

**Problem:**

For what values of parameters $p$ and $q$ are the vectors $\mathbf{a}=[1-p,3,-1]$ and $\mathbf{b}=[-2,4-q,2]$ parallel?

**Solution:**

$\mathbf{a}=[1-p,3,-1]$ and $\mathbf{b}=[-2,4-q,2]$.
Parallel if coordinates are proportional:
$$
\frac{1-p}{-2} = \frac{3}{4-q} = \frac{-1}{2}
$$
From $\frac{-1}{2}$: Ratio is $-0.5$.
$\frac{3}{4-q} = -0.5 \implies 3 = -2 + 0.5q \implies 5 = 0.5q \implies q=10$.
$\frac{1-p}{-2} = -0.5 \implies 1-p = 1 \implies p=0$.
Answer: $p=0, q=10$.

### Ex 13.  

**Problem:**

For what values of parameter $s$ are the vectors $\mathbf{p}=[s,2,1-s]$ and $\mathbf{q}=[s,1,-2]$ perpendicular?

**Solution:**

$\mathbf{p}=[s,2,1-s]$ and $\mathbf{q}=[s,1,-2]$.
Perpendicular $\iff \mathbf{p}\cdot\mathbf{q} = 0$.
$s(s) + 2(1) + (1-s)(-2) = 0$.
$s^2 + 2 - 2 + 2s = 0$.
$s^2 + 2s = 0 \implies s(s+2) = 0$.
$s=0$ or $s=-2$.

### Ex 14.  

**Problem:**

Prove that two vectors must have equal lengths if their sum is perpendicular to their difference.

**Solution:**

Prove $\|\mathbf{u}\| = \|\mathbf{v}\|$ if $(\mathbf{u}+\mathbf{v}) \perp (\mathbf{u}-\mathbf{v})$.
Proof:
$(\mathbf{u}+\mathbf{v}) \cdot (\mathbf{u}-\mathbf{v}) = 0$
$\mathbf{u}\cdot\mathbf{u} - \mathbf{u}\cdot\mathbf{v} + \mathbf{v}\cdot\mathbf{u} - \mathbf{v}\cdot\mathbf{v} = 0$
$\|\mathbf{u}\|^2 - \|\mathbf{v}\|^2 = 0$
$\|\mathbf{u}\|^2 = \|\mathbf{v}\|^2 \implies \|\mathbf{u}\| = \|\mathbf{v}\|$.

### Ex 15.  

**Problem:**

$\star$ We have 2 people (A and B) walking according to the formulas:

A: $(4,5)+(1,-2) t$

B: $(1,-8)+(2,4) t$

where $t$ denotes time. For what $t$ will the people be closest to each other?

**Solution:**

Positions: $P_A(t) = (4+t, 5-2t)$, $P_B(t) = (1+2t, -8+4t)$.
Vector $\vec{BA} = P_A - P_B = (3-t, 13-6t)$.
Squared distance $D^2(t) = (3-t)^2 + (13-6t)^2$.
Minimize $f(t) = (3-t)^2 + (13-6t)^2$.
$f'(t) = 2(3-t)(-1) + 2(13-6t)(-6) = -2(3-t) - 12(13-6t)$
$= -6 + 2t - 156 + 72t = 74t - 162$.
Set $f'(t) = 0 \implies 74t = 162 \implies t = \frac{162}{74} = \frac{81}{37} \approx 2.19$.
Closest at $t = \frac{81}{37}$.
