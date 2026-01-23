## Planes - Solutions

### Ex 1. 

**Problem:**

Provide the general and normal equation of the plane passing through point $A(1,0,2)$ and with the normal vector $\mathbf{n}=[2,-1,1]$.

**Solution:**

Plane through $A(1,0,2)$ with normal $\vec{n}=[2,-1,1]$.
General equation:
$$
2(x-1) - 1(y-0) + 1(z-2) = 0
$$
$$
2x - 2 - y + z - 2 = 0 \implies 2x - y + z - 4 = 0
$$

### Ex 2. 

**Problem:**

Find the equation of the plane passing through points $A(1,0,0)$, $B(0,1,0)$, and $C(0,0,1)$.

**Solution:**

Points on axes: $A(1,0,0)$, $B(0,1,0)$, $C(0,0,1)$.
Segment form:
$$
\frac{x}{1} + \frac{y}{1} + \frac{z}{1} = 1
$$
General form:
$$
x + y + z - 1 = 0
$$

### Ex 3. 

**Problem:**

Determine the angle between the planes: $\pi_1: x+2y-2z+1=0$ and $\pi_2: 2x-y+z-3=0$.

**Solution:**

$\pi_1: x+2y-2z+1=0 \implies \vec{n_1}=[1, 2, -2]$.
$\pi_2: 2x-y+z-3=0 \implies \vec{n_2}=[2, -1, 1]$.

$$
\cos\phi = \frac{|\vec{n_1} \cdot \vec{n_2}|}{\|\vec{n_1}\| \|\vec{n_2}\|}
$$
Dot product: $1(2) + 2(-1) + (-2)(1) = 2 - 2 - 2 = -2$. Absolute value is 2.
Norms:
$\|\vec{n_1}\| = \sqrt{1+4+4} = \sqrt{9} = 3$.
$\|\vec{n_2}\| = \sqrt{4+1+1} = \sqrt{6}$.
$$
\cos\phi = \frac{2}{3\sqrt{6}} = \frac{\sqrt{6}}{9}
$$
$\phi = \arccos(\frac{\sqrt{6}}{9})$.

### Ex 4. 

**Problem:**

For the plane $\pi: x-2y+2z-4=0$, calculate the distance of point $P(3,0,1)$ from this plane.

**Solution:**

Distance of $P(3,0,1)$ from $x-2y+2z-4=0$.
$$
d = \frac{|1(3) - 2(0) + 2(1) - 4|}{\sqrt{1^2+(-2)^2+2^2}} = \frac{|3 + 2 - 4|}{\sqrt{9}} = \frac{1}{3}
$$

### Ex 5. 

**Problem:**

Find a vector perpendicular to the plane $x + y + z = 1$.

**Solution:**

Plane $x + y + z = 1$. Normal vector:
$$
\vec{n} = [1, 1, 1]
$$

### Ex 6. 

**Problem:**

A plane passes through point $A(1, 2, 3)$ and is parallel to the plane $2x + 3y + 4z = 5$. Find the equation of this plane.

**Solution:**

Parallel to $2x + 3y + 4z = 5$. Normal is same: $\vec{n}=[2, 3, 4]$.
Equation: $2x + 3y + 4z + D = 0$.
Passes through $A(1, 2, 3)$.
$2(1) + 3(2) + 4(3) + D = 0 \implies 2 + 6 + 12 + D = 0 \implies D = -20$.
Equation:
$$
2x + 3y + 4z - 20 = 0
$$

### Ex 7. 

**Problem:**

$\star$ Find the equation of the plane passing through point $D(1,1,1)$ and containing the line passing through points $E(0,0,0)$ and $F(1,2,3)$.

**Solution:**

Plane through $D(1,1,1)$ containing line through $E(0,0,0)$ and $F(1,2,3)$.
Vectors on plane:
$\vec{v_1} = \vec{EF} = [1, 2, 3]$.
$\vec{v_2} = \vec{ED} = [1, 1, 1]$.
Normal vector:
$$
\begin{aligned}
\vec{n} = \vec{v_1} \times \vec{v_2} &= \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 1 & 2 & 3 \\ 1 & 1 & 1 \end{vmatrix} \\
&= \mathbf{i}(2-3) - \mathbf{j}(1-3) + \mathbf{k}(1-2) = [-1, 2, -1]
\end{aligned}
$$
Equation using point E(0,0,0):
$-1(x-0) + 2(y-0) - 1(z-0) = 0 \implies -x + 2y - z = 0$.
Multiply by -1:
$$
x - 2y + z = 0
$$
Check D(1,1,1): $1 - 2(1) + 1 = 0$. Correct.
