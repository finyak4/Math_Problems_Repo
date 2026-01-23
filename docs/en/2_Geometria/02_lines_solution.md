## Lines - Solutions

### Ex 1. 

**Problem:**

Write the equation of the line passing through points $P(1,2)$ and $Q(3,-1)$ in slope-intercept form and general form.

**Solution:**

Points $P(1,2)$ and $Q(3,-1)$.
Slope $m = \frac{-1-2}{3-1} = \frac{-3}{2} = -1.5$.
Equation:
$$
y - 2 = -\frac{3}{2}(x - 1)
$$
Slope-intercept form:
$$
y = -1.5x + 1.5 + 2 \implies y = -1.5x + 3.5
$$
General form ($Ax+By+C=0$):
Multiply by 2: $2y = -3x + 7 \implies 3x + 2y - 7 = 0$.

### Ex 2. 

**Problem:**

Find the parametric equation of the line perpendicular to the line from Ex 1 and passing through point $R(0,1)$.

**Solution:**

Line perpendicular to $l_1$ (slope $-3/2$) has slope $m' = \frac{-1}{-3/2} = \frac{2}{3}$.
Passes through $R(0,1)$.
Direction vector for slope $2/3$: $\vec{v} = [3, 2]$ (run 3, rise 2).
Parametric equation:
$$
\begin{cases}
x = 0 + 3t \\
y = 1 + 2t
\end{cases}
\quad t \in \mathbb{R}
$$

### Ex 3. 

**Problem:**

A line passes through point $A(1, 2)$ and is parallel to the line $y = 2x + 3$. Find the equation of this line.

**Solution:**

Parallel to $y = 2x + 3 \implies m=2$.
Through $A(1, 2)$.
$y - 2 = 2(x - 1) \implies y = 2x - 2 + 2 \implies y = 2x$.

### Ex 4. 

**Problem:**

For lines in general form $l_1: 2x-3y+1=0$ and $l_2: 4x-6y-5=0$, determine whether they are parallel, perpendicular, or intersect at a single point. If they have a common point, calculate its coordinates.

**Solution:**

$l_1: 2x-3y+1=0$. Normal $\vec{n_1}=[2, -3]$.
$l_2: 4x-6y-5=0$. Normal $\vec{n_2}=[4, -6]$.
Vectors are proportional ($\vec{n_2} = 2\vec{n_1}$), so lines are parallel.
Check if they are the same line:
$l_1 \times 2 \implies 4x - 6y + 2 = 0$.
$l_2$ is $4x - 6y - 5 = 0$.
Since $2 \neq -5$, the lines are **parallel and distinct** (no intersection).

### Ex 5. 

**Problem:**

Calculate the angle between the line $y = x + 3$ and the $Ox$ axis.

**Solution:**

Line $y = x + 3$. Slope $m=1$.
$\tan\alpha = 1 \implies \alpha = 45^\circ$ or $\frac{\pi}{4}$.

### Ex 6. 

**Problem:**

Provide a vector perpendicular to the line $x + y + 1 = 0$.

**Solution:**

$x + y + 1 = 0$.
A vector perpendicular to the line is the normal vector:
$\vec{n} = [1, 1]$.

### Ex 7. 

**Problem:**

$\star$ Find the distance of point $S(2,3)$ from the line $l: 3x-4y+5=0$.

**Solution:**

Distance of $S(2,3)$ from $3x-4y+5=0$.
$$
d = \frac{|Ax_0 + By_0 + C|}{\sqrt{A^2+B^2}} = \frac{|3(2) - 4(3) + 5|}{\sqrt{3^2+(-4)^2}}
$$
$$
= \frac{|6 - 12 + 5|}{\sqrt{9+16}} = \frac{|-1|}{\sqrt{25}} = \frac{1}{5}
$$

### Ex 8. 

**Problem:**

$\star$ Write the equation of the line passing through point $T(1,1)$ and forming an angle of $\pi/6$ with the OX axis. Also, provide the intersection point with the OY axis.

**Solution:**

Through $T(1,1)$, angle $30^\circ$ ($\pi/6$) with OX axis.
Slope $m = \tan(30^\circ) = \frac{\sqrt{3}}{3}$.
Equation:
$$
y - 1 = \frac{\sqrt{3}}{3}(x - 1) \implies y = \frac{\sqrt{3}}{3}x - \frac{\sqrt{3}}{3} + 1
$$
Intersection with OY axis (set $x=0$):
$$
y = 1 - \frac{\sqrt{3}}{3}
$$
Point: $(0, 1 - \frac{\sqrt{3}}{3})$.
