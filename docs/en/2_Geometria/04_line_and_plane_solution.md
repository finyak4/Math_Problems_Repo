## Line and Plane in Space - Solutions

### Ex 1. 

**Problem:**

Check if the line given parametrically

$$\ell: \; x=1+2t,\; y= -1+t,\; z=3- t$$

intersects the plane $\pi: 2x-y+z-4=0$. If so, provide the intersection point.

**Solution:**

Line $\ell$: $x=1+2t, y=-1+t, z=3-t$.
Plane $\pi$: $2x-y+z-4=0$.

Substitute line equations into plane equation:
$$
\begin{aligned}
2(1+2t) - (-1+t) + (3-t) - 4 &= 0 \\\
2 + 4t + 1 - t + 3 - t - 4 &= 0 \\\
2t + 2 = 0 \implies 2t = -2 \implies t &= -1
\end{aligned}
$$
Since there is a unique solution for $t$, they intersect at a single point.
Coordinates:
$$
x = 1 + 2(-1) = -1
$$
$$
y = -1 + (-1) = -2
$$
$$
z = 3 - (-1) = 4
$$
Intersection point: $P(-1, -2, 4)$.

### Ex 2. 

**Problem:**

$\star$ Calculate the distance of point $G(2,-1,0)$ from the line passing through points $H(0,0,0)$ and $I(1,1,1)$.

**Solution:**

Distance of $G(2,-1,0)$ from line through $H(0,0,0)$ and $I(1,1,1)$.
Line direction vector $\vec{u} = \vec{HI} = [1, 1, 1]$.
Vector from point on line (H) to G: $\vec{v} = \vec{HG} = [2, -1, 0]$.

Formula:
$$
d = \frac{\|\vec{v} \times \vec{u}\|}{\|\vec{u}\|}
$$
Cross product:
$$
\begin{aligned}
\vec{v} \times \vec{u} &= \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\\ 2 & -1 & 0 \\\ 1 & 1 & 1 \end{vmatrix} \\\
&= \mathbf{i}(-1-0) - \mathbf{j}(2-0) + \mathbf{k}(2-(-1)) = [-1, -2, 3]
\end{aligned}
$$
Norm of cross product: $\sqrt{1+4+9} = \sqrt{14}$.
Norm of direction: $\|\vec{u}\| = \sqrt{1+1+1} = \sqrt{3}$.
$$
d = \frac{\sqrt{14}}{\sqrt{3}} = \sqrt{\frac{14}{3}}
$$

### Ex 3. 

**Problem:**

$\star$ Consider the system of a line and a plane dependent on parameter $\lambda$:

$$\ell(\lambda): x=\lambda+t,\; y=1+2t,\; z=2-t$$

   and

$$\pi: x - (\lambda-1) y + z - 3 = 0$$

Determine the values of $\lambda$ for which the line is parallel to the plane, contained in the plane, or intersects it at a single point.

**Solution:**

Line $\ell(\lambda): x=\lambda+t, y=1+2t, z=2-t \implies \vec{v}=[1, 2, -1]$, point $L(\lambda, 1, 2)$.
Plane $\pi: x - (\lambda-1)y + z - 3 = 0 \implies \vec{n}=[1, -(\lambda-1), 1]$.

**Check direction (parallelism):**
$$
\vec{v} \cdot \vec{n} = 1(1) + 2(-(\lambda-1)) + (-1)(1) = 1 - 2\lambda + 2 - 1 = 2 - 2\lambda
$$
If $\vec{v} \cdot \vec{n} \neq 0$ ($\lambda \neq 1$): Line intersects plane at a single point.
If $\vec{v} \cdot \vec{n} = 0$ ($\lambda = 1$): Line is parallel to the plane.

**Check containment for $\lambda = 1$:**
If $\lambda = 1$, check if point $L(1, 1, 2)$ lies on the plane $x + z - 3 = 0$ (since $(\lambda-1)y = 0$).
$1 + 2 - 3 = 0$. Yes.
So for $\lambda = 1$, the line is **contained** in the plane.

**Summary:**

- **Parallel (no intersection):** Never.

- **Contained:** For $\lambda = 1$.

- **Intersects at single point:** For $\lambda \neq 1$.
