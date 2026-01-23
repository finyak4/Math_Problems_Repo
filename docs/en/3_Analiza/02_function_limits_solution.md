## Function Limits - Solutions

### Ex 1.

**Problem 1)**
$$
\lim\limits_{x \to 3} \frac{27-x^3}{x-3}
$$
**Solution:**
$$
\lim_{x \to 3} \frac{-(x-3)(x^2+3x+9)}{x-3} = -(9+9+9) = -27
$$

**Problem 2)**
$$
\lim\limits_{x \to 3} \frac{x^2-4x+3}{2x-6}
$$
**Solution:**
$$
\lim_{x \to 3} \frac{(x-3)(x-1)}{2(x-3)} = \frac{3-1}{2} = 1
$$

**Problem 3)**
$$
\lim\limits_{x \to -1} \frac{x^3-1}{x+1}
$$
**Solution:**
Direct substitution: $\frac{-2}{0}$.
LHL: $\frac{-2}{0^-} = +\infty$. RHL: $\frac{-2}{0^+} = -\infty$.
Limit does not exist (infinity with different signs).
Note: If problem was $x^3+1$, it would be cancellable. As written ($x^3-1$), no cancellation.

**Problem 4)**
$$
\lim\limits_{x \to -2} \frac{x+2}{x^5+32}
$$
**Solution:**
Using derivative or factorization ($a^5+b^5 = (a+b)(a^4-a^3b...)$).
L'Hopital: $\frac{1}{5x^4} = \frac{1}{5(16)} = \frac{1}{80}$.

**Problem 5)**
$$
\lim\limits_{x \to 4} \frac{x^2-2x-8}{x^2-9x+20}
$$
**Solution:**
$$
\lim_{x \to 4} \frac{(x-4)(x+2)}{(x-4)(x-5)} = \frac{4+2}{4-5} = -6
$$

**Problem 6)**
$$
\lim\limits_{x \to -5} \frac{x^3+125}{2x^2-50}
$$
**Solution:**
$$
\lim_{x \to -5} \frac{(x+5)(x^2-5x+25)}{2(x-5)(x+5)} = \frac{25+25+25}{2(-10)} = \frac{75}{-20} = -3.75
$$

**Problem 7)**
$$
\lim\limits_{x \to -2} \frac{3x^2+5x-2}{4x^2+9x+2}
$$
**Solution:**
$$
\lim_{x \to -2} \frac{(x+2)(3x-1)}{(x+2)(4x+1)} = \frac{-6-1}{-8+1} = \frac{-7}{-7} = 1
$$

**Problem 8)**
$$
\lim\limits_{x \to 1} \frac{x^n-1}{x-1}
$$
**Solution:**
Derivative of $x^n$ at $x=1$ is $n$.

**Problem 9)**
$$
\lim\limits_{x \to 3} \frac{(x-3)(-1)^{[x]}}{x^2-9}
$$
**Solution:**
$$
\lim \frac{(-1)^{[x]}}{x+3}
$$
RHL ($x \to 3^+$): $\frac{-1}{6}$.
LHL ($x \to 3^-$): $\frac{1}{6}$.
Limit does not exist.

**Problem 10)**
$$
\lim\limits_{x \to 0} \frac{\sqrt[3]{1+mx}-1}{x}
$$
**Solution:**
Using approximation $(1+mx)^{1/3} \approx 1 + \frac{1}{3}mx$.
Limit is $m/3$.

**Problem 11)** Same as 8.

**Problem 12)**
$$
\lim\limits_{x \to 25} \frac{\sqrt{x}-5}{x-25}
$$
**Solution:**
$$
\lim \frac{1}{\sqrt{x}+5} = \frac{1}{10}
$$

**Problem 13)**
$$
\lim\limits_{x \to 0} \frac{\sqrt{x^2+1}-\sqrt{x+1}}{1-\sqrt{x+1}}
$$
**Solution:**
Use L'Hopital or conjugates.
L'H: $\frac{\frac{2x}{2\sqrt{x^2+1}} - \frac{1}{2\sqrt{x+1}}}{-\frac{1}{2\sqrt{x+1}}} = \frac{0 - 1/2}{-1/2} = 1$.

**Problem 14)**
$$
\lim\limits_{x \to 0} \frac{\sqrt{x^2+1}-1}{\sqrt{x^2+25}-5}
$$
**Solution:**
$\approx \frac{x^2/2}{x^2/10} = \frac{10}{2} = 5$.

**Problem 15)**
$$
\lim\limits_{x \to 0} \frac{\sin 3x}{4x}
$$
**Solution:**
$$
\frac{3}{4} \lim \frac{\sin 3x}{3x} = \frac{3}{4}
$$

**Problem 16)**
$$
\lim\limits_{x \to 0} \frac{4x}{3 \sin 2x}
$$
**Solution:**
$$
\frac{4}{3} \cdot \frac{1}{2} = \frac{2}{3}
$$

**Problem 17)**
$$
\lim\limits_{x \to +\infty} \frac{\sin x}{x}
$$
**Solution:**
Bounded function / Infinity = 0.

**Problem 18)**
$$
\lim\limits_{x \to \pi} \frac{\sin x}{x}
$$
**Solution:**
$$
\frac{0}{\pi} = 0
$$

**Problem 19)**
$$
\lim\limits_{x \to \frac{\pi}{2}} \frac{\cos x}{x-\frac{\pi}{2}}
$$
**Solution:**
L'Hopital: $\frac{-\sin x}{1} \to -1$.

**Problem 20)**
$$
\lim\limits_{x \to 0} \frac{\text{tg } x}{4x}
$$
**Solution:**
$$
\frac{1}{4}
$$

**Problem 21)**
$$
\lim\limits_{x \to \pi} \frac{8-x}{\sin x}
$$
**Solution:**
Numer $\to 8-\pi \neq 0$. Denom $\to 0$. Limit is $\infty$.

**Problem 22)**
$$
\lim\limits_{x \to 0} \frac{\sin 2x}{\sin 3x}
$$
**Solution:**
$$
\frac{2}{3}
$$

**Problem 23)**
$$
\lim\limits_{x \to 0} \frac{\text{tg } 2x}{\text{tg } x}
$$
**Solution:**
$2$.

**Problem 24)**
$$
\lim\limits_{x \to \frac{\pi}{2}} \frac{1+\cos x}{\sin^2 x}
$$
**Solution:**
$$
\frac{1+0}{1} = 1
$$

**Problem 25)**
$$
\lim\limits_{x \to \frac{\pi}{4}} \frac{\cos x - \cos \frac{\pi}{4}}{\sin x - \sin \frac{\pi}{4}}
$$
**Solution:**
L'Hopital: $\frac{-\sin x}{\cos x} = -\operatorname{tg} x \to -1$.

**Problem 26)**
$$
\lim\limits_{x \to 1} \frac{|\text{tg}(x-1)|}{(x-1)^2}
$$
**Solution:**
Let $t=x-1$. $\frac{|\operatorname{tg} t|}{t^2} \approx \frac{|t|}{t^2} = \frac{1}{|t|} \to \infty$.

**Problem 27)**
$$
\lim\limits_{x \to 0} \frac{\text{arctg } x}{x}
$$
**Solution:**
$1$.

**Problem 28)**
$$
\lim\limits_{x \to \frac{1}{2}} \frac{\arcsin(1-2x)}{4x^2-1}
$$
**Solution:**
Let $t=1-2x$. $4x^2-1 = (2x-1)(2x+1) = -t(2-t) \approx -2t$.
$\lim \frac{\arcsin t}{-2t} = -0.5$.

**Problem 29)**
$$
\lim\limits_{x \to 0} \frac{\sqrt{1+\sin x}}{x}
$$
**Solution:**
$\frac{1}{0} \to \infty$. (If problem was $\sqrt{1+\sin x}-1$, limit would be $1/2$).

**Problem 30)**
$$
\lim\limits_{x \to 0} (1-3x)^{\frac{1}{x}}
$$
**Solution:**
$e^{-3}$.

**Problem 31)**
$$
\lim\limits_{x \to 0} (1+kx)^{\frac{n}{x}}
$$
**Solution:**
$e^{kn}$.

### Ex 2.

**Problem:** Determine continuity.

1) $f(x) = \frac{x^2-25}{x+5}$ for $x \neq -5$ and $f(-5)=-10$.
**Solution:**
$\lim_{x \to -5} (x-5) = -10$. $f(-5)=-10$. **Continuous.**

2) $f(x) = \frac{\sin x}{x}$ for $x \neq 0$ and $f(0)=1$.
**Solution:**
Limit is $1$. **Continuous.**

3) $f(x) = \frac{\sin x}{|x|}$ for $x \neq 0$ and $f(0)=1$.
**Solution:**
RHL $1$, LHL $-1$. **Discontinuous** (Jump).

4) $f(x) = x + \frac{1}{x}$
**Solution:**
Infinite at $0$. **Discontinuous** (Infinite).

5) $f(x) = \frac{x^2-x^3}{|x-1|} = \frac{x^2(1-x)}{|x-1|}$
**Solution:**
Limit is $\pm 1$ ($x \to 1^- \implies 1$, $x \to 1^+ \implies -1$). **Discontinuous.**

6) $f(x) = x - [x]$
**Solution:**
Jumps at integers. **Discontinuous.**

7) $f(x) = [x] + [-x]$
**Solution:**
For integer $x$, value $0$. For non-integer, $-1$.
Discontinuous at integers.

8) $f(x) = \frac{\sqrt{1+x}-1}{x}$
**Solution:**
Limit is $1/2$. If $f(0)$ is not defined, it is a removable discontinuity. Can be defined as $1/2$.

9) $f(x) = x \sin \frac{\pi}{x}$
**Solution:**
Limit at $0$ is $0$. Define $f(0)=0$.

10) $f(x) = \frac{\sin^2 x}{1-\cos x}$
**Solution:**
Limit $1+\cos x \to 2$. Define $f(0)=2$.

11) $x \left[ \frac{1}{x} \right]$ at $x=0$.
**Solution:**
$\lim_{x \to 0} x(1/x - \{1/x\}) = 1 - 0 = 1$. Continuous if $f(0)=1$.

12) $x \frac{b}{x} \left[ \frac{x}{a} \right]$
**Solution:**
$\to b \cdot 0 = 0$.

13) $\frac{e^{\frac{1}{x}}-1}{e^{\frac{1}{x}}+1}$ at $x=0$.
**Solution:**
Jump (-1 to 1). Discontinuous.

14) $e^{\frac{1}{1-x^2}}$ at $x=1$.
**Solution:**
$e^{\infty}$ vs $e^{-\infty}$. Infinite/Zero. Discontinuous.

15) $x e^{\frac{1}{x}}$ at $x=0$.
**Solution:**
One side infinite. Discontinuous.

16) $\frac{x}{2x+e^{\frac{1}{x-1}}}$ at $x=1$.
**Solution:**
Discontinuous.
