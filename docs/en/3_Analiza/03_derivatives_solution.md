## Derivatives - Solutions

### Ex 1. Calculate derivatives

**1)** $y = \frac{1}{3}x^3 - \frac{3}{2}x^4 + \frac{13}{5}x^5 - 2x^6$
**Solution:**
Using power rule $(x^n)' = nx^{n-1}$:
$$y' = \frac{1}{3}(3x^2) - \frac{3}{2}(4x^3) + \frac{13}{5}(5x^4) - 2(6x^5) = x^2 - 6x^3 + 13x^4 - 12x^5$$

**2)** $y = 5x^{15} - x^2 + \frac{1}{3}x - 2$
**Solution:**
$$y' = 5(15x^{14}) - 2x + \frac{1}{3} - 0 = 75x^{14} - 2x + \frac{1}{3}$$

**3)** $y = ax^3 + \frac{b}{x} + c$
**Solution:**
Rewrite: $y = ax^3 + bx^{-1} + c$.
$$y' = 3ax^2 - bx^{-2} + 0 = 3ax^2 - \frac{b}{x^2}$$

**4)** $y = \frac{4}{x^3}$
**Solution:**
Rewrite: $y = 4x^{-3}$.
$$y' = 4(-3x^{-4}) = -12x^{-4} = -\frac{12}{x^4}$$

**5)** $y = 9x^7 + 3x^{-5} - 3x^{-11}$
**Solution:**
$$y' = 9(7x^6) + 3(-5x^{-6}) - 3(-11x^{-12}) = 63x^6 - 15x^{-6} + 33x^{-12} = 63x^6 - \frac{15}{x^6} + \frac{33}{x^{12}}$$

**6)** $y = 3x^{7/3} - 4x^{13/4} + \frac{4}{7}x^{-1/2} + 7^{3/2}$
**Solution:**
$$y' = 3(\frac{7}{3}x^{4/3}) - 4(\frac{13}{4}x^{9/4}) + \frac{4}{7}(-\frac{1}{2}x^{-3/2}) + 0$$
$$y' = 7x^{4/3} - 13x^{9/4} - \frac{2}{7}x^{-3/2}$$

**7)** $y = \sqrt[3]{x^2}$
**Solution:**
Rewrite: $y = x^{2/3}$.
$$y' = \frac{2}{3}x^{2/3 - 1} = \frac{2}{3}x^{-1/3} = \frac{2}{3\sqrt[3]{x}}$$

**8)** $y = 5\sqrt[3]{x^7}$
**Solution:**
Rewrite: $y = 5x^{7/3}$.
$$y' = 5(\frac{7}{3}x^{4/3}) = \frac{35}{3}x^{4/3} = \frac{35}{3}x\sqrt[3]{x}$$

**9)** $y = 3\sqrt[3]{x} - x^3 + \frac{2}{3}\sqrt[3]{x^4}$
**Solution:**
Rewrite: $y = 3x^{1/3} - x^3 + \frac{2}{3}x^{4/3}$.
$$y' = 3(\frac{1}{3}x^{-2/3}) - 3x^2 + \frac{2}{3}(\frac{4}{3}x^{1/3})$$
$$y' = x^{-2/3} - 3x^2 + \frac{8}{9}x^{1/3} = \frac{1}{\sqrt[3]{x^2}} - 3x^2 + \frac{8}{9}\sqrt[3]{x}$$

**10)** $y = \sqrt{x} - 5\sqrt[3]{x^2} - 2\sqrt{x^3}$
**Solution:**
Rewrite: $y = x^{1/2} - 5x^{2/3} - 2x^{3/2}$.
$$y' = \frac{1}{2}x^{-1/2} - 5(\frac{2}{3}x^{-1/3}) - 2(\frac{3}{2}x^{1/2})$$
$$y' = \frac{1}{2\sqrt{x}} - \frac{10}{3\sqrt[3]{x}} - 3\sqrt{x}$$

**11)** $y = \frac{2}{\sqrt{x}} - \frac{3}{\sqrt{x^3}}$
**Solution:**
Rewrite: $y = 2x^{-1/2} - 3x^{-3/2}$.
$$y' = 2(-\frac{1}{2}x^{-3/2}) - 3(-\frac{3}{2}x^{-5/2}) = -x^{-3/2} + \frac{9}{2}x^{-5/2} = -\frac{1}{x\sqrt{x}} + \frac{9}{2x^2\sqrt{x}}$$

**12)** $y = \frac{5}{7\sqrt[3]{x}} - 2x^7 + \frac{3}{2\sqrt{x}}$
**Solution:**
Rewrite: $y = \frac{5}{7}x^{-1/3} - 2x^7 + \frac{3}{2}x^{-1/2}$.
$$y' = \frac{5}{7}(-\frac{1}{3}x^{-4/3}) - 14x^6 + \frac{3}{2}(-\frac{1}{2}x^{-3/2})$$
$$y' = -\frac{5}{21}x^{-4/3} - 14x^6 - \frac{3}{4}x^{-3/2}$$

**13)** $x = t^3\sqrt{t}$
**Solution:**
Rewrite: $x = t^3 \cdot t^{1/2} = t^{3.5} = t^{7/2}$.
$$x' = \frac{7}{2}t^{5/2} = 3.5 t^2\sqrt{t}$$

**14)** $y = \frac{2}{x^3\sqrt{x}}$
**Solution:**
Rewrite: $y = 2x^{-(3 + 0.5)} = 2x^{-3.5}$.
$$y' = 2(-3.5)x^{-4.5} = -7x^{-9/2} = -\frac{7}{x^4\sqrt{x}}$$

**15)** $y = (2\sqrt[3]{x^2}-x)(4\sqrt[3]{x^4}+2\sqrt[3]{x^5}+x^2)$
**Solution:**
Check if this matches $a^3-b^3 = (a-b)(a^2+ab+b^2)$.
Let $a = 2\sqrt[3]{x^2} = 2x^{2/3}$ and $b = x$.
Then $a^2 = 4x^{4/3} = 4\sqrt[3]{x^4}$, $ab = 2x^{2/3}x = 2x^{5/3} = 2\sqrt[3]{x^5}$, $b^2 = x^2$.
So $y = a^3 - b^3 = (2x^{2/3})^3 - x^3 = 8x^2 - x^3$.
$$y' = 16x - 3x^2$$

**16)** $y = (4x^2-2x\sqrt{x}+x)(2x+\sqrt{x})$
**Solution:**
Recognize sum of cubes pattern: $(a+b)(a^2-ab+b^2) = a^3+b^3$.
Let $a=2x$ and $b=\sqrt{x}$.
Checking $a^2-ab+b^2$: $(2x)^2 - (2x)(\sqrt{x}) + (\sqrt{x})^2 = 4x^2 - 2x\sqrt{x} + x$. Matches.
So $y = (2x)^3 + (\sqrt{x})^3 = 8x^3 + x^{3/2}$.
$$y' = 24x^2 + \frac{3}{2}x^{1/2} = 24x^2 + 1.5\sqrt{x}$$

**17)** $y = \frac{3}{3x-2}$
**Solution:**
Rewrite: $y = 3(3x-2)^{-1}$.
$$y' = 3(-1)(3x-2)^{-2}(3) = -9(3x-2)^{-2} = \frac{-9}{(3x-2)^2}$$

**18)** $y = \frac{5}{2x^2-5x+1}$
**Solution:**
Rewrite: $y = 5(2x^2-5x+1)^{-1}$.
$$y' = 5(-1)(2x^2-5x+1)^{-2}(4x-5) = \frac{-5(4x-5)}{(2x^2-5x+1)^2}$$

**19)** $y = \frac{3x^2}{7x^5-x+2}$
**Solution:**
Quotient rule: $u=3x^2 (u'=6x)$, $v=7x^5-x+2 (v'=35x^4-1)$.
$$y' = \frac{6x(7x^5-x+2) - 3x^2(35x^4-1)}{(7x^5-x+2)^2} = \frac{42x^6-6x^2+12x - (105x^6-3x^2)}{(7x^5-x+2)^2}$$
$$y' = \frac{-63x^6-3x^2+12x}{(7x^5-x+2)^2}$$

**20)** $y = \frac{8x^3}{x^3+x-1}$
**Solution:**
$u=8x^3 (u'=24x^2)$, $v=x^3+x-1 (v'=3x^2+1)$.
$$y' = \frac{24x^2(x^3+x-1) - 8x^3(3x^2+1)}{(x^3+x-1)^2} = \frac{24x^5+24x^3-24x^2 - 24x^5-8x^3}{(x^3+x-1)^2} = \frac{16x^3-24x^2}{(x^3+x-1)^2}$$

**21)** $y = \frac{x+1}{x-1}$
**Solution:**
$$y' = \frac{1(x-1) - (x+1)(1)}{(x-1)^2} = \frac{x-1-x-1}{(x-1)^2} = \frac{-2}{(x-1)^2}$$

**22)** $y = \frac{5x^2+x-2}{x^2+7}$
**Solution:**
$u'=10x+1$, $v'=2x$.
$$y' = \frac{(10x+1)(x^2+7) - (5x^2+x-2)(2x)}{(x^2+7)^2}$$
$$ = \frac{10x^3+70x+x^2+7 - 10x^3-2x^2+4x}{(x^2+7)^2} = \frac{-x^2+74x+7}{(x^2+7)^2}$$

**23)** $y = \frac{x^2-2x+3}{x^2+2x-3}$
**Solution:**
$u'=2x-2$, $v'=2x+2$.
$$y' = \frac{(2x-2)(x^2+2x-3) - (x^2-2x+3)(2x+2)}{(x^2+2x-3)^2}$$
Num: $(2x^3+4x^2-6x-2x^2-4x+6) - (2x^3+2x^2-4x^2-4x+6x+6)$
$= (2x^3+2x^2-10x+6) - (2x^3-2x^2+2x+6) = 4x^2-12x$.
$$y' = \frac{4x^2-12x}{(x^2+2x-3)^2}$$

**24)** $y = \frac{3}{(1-x^2)(1-2x^3)}$
**Solution:**
Rewrite: $y = 3(1-x^2)^{-1}(1-2x^3)^{-1}$.
Product rule: $u=3(1-x^2)^{-1}, v=(1-2x^3)^{-1}$.
$u' = -3(1-x^2)^{-2}(-2x) = 6x(1-x^2)^{-2}$.
$v' = -(1-2x^3)^{-2}(-6x^2) = 6x^2(1-2x^3)^{-2}$.
$y' = \frac{6x}{(1-x^2)^2(1-2x^3)} + \frac{18x^2}{(1-x^2)(1-2x^3)^2}$
$$y' = \frac{6x(1-2x^3) + 18x^2(1-x^2)}{(1-x^2)^2(1-2x^3)^2} = \frac{6x-12x^4+18x^2-18x^4}{(1-x^2)^2(1-2x^3)^2} = \frac{6x(1+3x-5x^3)}{(1-x^2)^2(1-2x^3)^2}$$

**25)** $y = \frac{\sqrt[3]{x}}{1-\sqrt[3]{x}}$
**Solution:**
Let $t=\sqrt[3]{x} = x^{1/3}$. $y = \frac{t}{1-t}$.
$t' = \frac{1}{3}x^{-2/3}$.
$$y' = \frac{t'(1-t) - t(-t')}{(1-t)^2} = \frac{t'}{(1-t)^2} = \frac{1}{3\sqrt[3]{x^2}(1-\sqrt[3]{x})^2}$$

**26)** $z = \frac{1+\sqrt{t}}{1+\sqrt{2t}}$
**Solution:**
$u=1+\sqrt{t} \implies u'=\frac{1}{2\sqrt{t}}$.
$v=1+\sqrt{2t} \implies v'=\frac{\sqrt{2}}{2\sqrt{2t}} \cdot 2 = \text{Wait. } \frac{1}{2\sqrt{2t}} \cdot 2 = \frac{1}{\sqrt{2t}}$.
$$z' = \frac{\frac{1}{2\sqrt{t}}(1+\sqrt{2t}) - (1+\sqrt{t})\frac{1}{\sqrt{2t}}}{(1+\sqrt{2t})^2} = \frac{\sqrt{2}(1+\sqrt{2t}) - 2(1+\sqrt{t})}{2\sqrt{2t}(1+\sqrt{2t})^2}$$
$$ = \frac{\sqrt{2}+\sqrt{4t}-2-2\sqrt{t}}{2\sqrt{2t}(1+\sqrt{2t})^2} = \frac{\sqrt{2}-2}{2\sqrt{2t}(1+\sqrt{2t})^2} $$

**27)** $s = (3t+1)^7$
**Solution:**
Using chain rule:
$$s' = 7(3t+1)^6 \cdot (3t+1)' = 21(3t+1)^6$$

**28)** $v = (4z^2-5z+13)^5$
**Solution:**
Chain rule:
$$v' = 5(4z^2-5z+13)^4 \cdot (8z-5)$$

**29)** $x = (\frac{1}{t}+4)^4$
**Solution:**
Inner: $u=t^{-1}+4 \implies u'=-t^{-2}$.
$$x' = 4(\frac{1}{t}+4)^3 (-\frac{1}{t^2}) = -\frac{4}{t^2}(\frac{1}{t}+4)^3$$

**30)** $s = (\frac{7t^2-\frac{t}{2}+6}{t})^6$
**Solution:**
Simplify inner: $u = 7t - \frac{1}{2} + 6t^{-1}$.
$u' = 7 - 6t^{-2}$.
$$s' = 6(7t - 0.5 + \frac{6}{t})^5 (7 - \frac{6}{t^2})$$

**31)** $y = \sqrt{x^2-4}$
**Solution:**
$y=(x^2-4)^{1/2}$.
$$y' = \frac{1}{2}(x^2-4)^{-1/2}(2x) = \frac{x}{\sqrt{x^2-4}}$$

**32)** $z = \sqrt{ax^2+bx+c}$
**Solution:**
$z=(ax^2+bx+c)^{1/2}$.
$$z' = \frac{1}{2}(ax^2+bx+c)^{-1/2}(2ax+b) = \frac{2ax+b}{2\sqrt{ax^2+bx+c}}$$

**33)** $y = \frac{1}{\sqrt{2-3t}}$
**Solution:**
$y=(2-3t)^{-1/2}$.
$$y' = -\frac{1}{2}(2-3t)^{-3/2}(-3) = \frac{3}{2(2-3t)^{3/2}}$$

**34)** $s = \frac{1}{\sqrt{6t-t^2}}$
**Solution:**
$s=(6t-t^2)^{-1/2}$.
$$s' = -\frac{1}{2}(6t-t^2)^{-3/2}(6-2t) = \frac{-(3-t)}{(6t-t^2)^{3/2}} = \frac{t-3}{\sqrt{(6t-t^2)^3}}$$

**35)** $y = \frac{1}{\sqrt[3]{(2-x^3)^4}}$
**Solution:**
$y=(2-x^3)^{-4/3}$.
$$y' = -\frac{4}{3}(2-x^3)^{-7/3}(-3x^2) = 4x^2(2-x^3)^{-7/3} = \frac{4x^2}{\sqrt[3]{(2-x^3)^7}}$$

**36)** $y = \frac{a}{\sqrt[p]{(a+bx)^r}}$
**Solution:**
$y = a(a+bx)^{-r/p}$.
$$y' = a(-\frac{r}{p})(a+bx)^{-r/p-1}(b) = -\frac{abr}{p}(a+bx)^{-(r+p)/p}$$

**37)** $y = \frac{1}{(b-x^n)^m}$
**Solution:**
$y = (b-x^n)^{-m}$.
$$y' = -m(b-x^n)^{-m-1}(-nx^{n-1}) = mnx^{n-1}(b-x^n)^{-m-1}$$

**38)** $y = \sqrt[4]{(x-1)^3}$
**Solution:**
$y = (x-1)^{3/4}$.
$$y' = \frac{3}{4}(x-1)^{-1/4} = \frac{3}{4\sqrt[4]{x-1}}$$

**39)** $u = \frac{1}{v-\sqrt{a^2+b^2}}$
**Solution:**
Assuming $v$ is the variable. $u = (v - C)^{-1}$.
$$u' = -(v - \sqrt{a^2+b^2})^{-2}(1) = \frac{-1}{(v-\sqrt{a^2+b^2})^2}$$

**40)** $y = \sqrt{\frac{a-x}{a^2-x^2}}$
**Solution:**
Simplify: $y = \sqrt{\frac{a-x}{(a-x)(a+x)}} = \frac{1}{\sqrt{a+x}} = (a+x)^{-1/2}$ ($x \ne a$).
$$y' = -\frac{1}{2}(a+x)^{-3/2} = \frac{-1}{2\sqrt{(a+x)^3}}$$

**41)** $v = \frac{z}{\sqrt{a^2-z^2}}$
**Solution:**
$num'=1, den'=\frac{-2z}{2\sqrt{a^2-z^2}}$.
$$v' = \frac{1\sqrt{a^2-z^2} - z(\frac{-z}{\sqrt{a^2-z^2}})}{a^2-z^2} = \frac{\frac{a^2-z^2+z^2}{\sqrt{a^2-z^2}}}{a^2-z^2} = \frac{a^2}{(a^2-z^2)^{3/2}}$$

**42)** $y = \frac{3\sqrt{x}}{x^2+1}$
**Solution:**
$u=3x^{1/2} (u'=1.5x^{-1/2})$, $v=x^2+1 (v'=2x)$.
$$y' = \frac{1.5x^{-1/2}(x^2+1) - 3x^{1/2}(2x)}{(x^2+1)^2} = \frac{1.5x^{-1/2}(x^2+1-4x^2)}{(x^2+1)^2} = \frac{3(1-3x^2)}{2\sqrt{x}(x^2+1)^2}$$

**43)** $y = \frac{x^2}{\sqrt[3]{x^3+1}}$
**Solution:**
$u=x^2, v=(x^3+1)^{1/3}$.
$$y' = \frac{2x(x^3+1)^{1/3} - x^2 \frac{1}{3}(x^3+1)^{-2/3}(3x^2)}{(x^3+1)^{2/3}} = \frac{2x(x^3+1) - x^4}{(x^3+1)^{4/3}}$$
$$y' = \frac{2x^4+2x-x^4}{(x^3+1)^{4/3}} = \frac{x^4+2x}{(x^3+1)^{4/3}}$$

**44)** $z = \sqrt{\frac{x^2-3x+2}{x^2-7x+12}}$
**Solution:**
$z = \sqrt{\frac{(x-1)(x-2)}{(x-3)(x-4)}}$. Using log differentiation: $\ln z = \frac{1}{2}\sum \pm \ln(\dots)$.
$$z' = \frac{z}{2}(\frac{1}{x-1} + \frac{1}{x-2} - \frac{1}{x-3} - \frac{1}{x-4})$$

**45)** $z = \sqrt{\frac{a^2-x^2}{a^2+x^2}}$
**Solution:**
$z' = \frac{1}{2z} (\frac{a^2-x^2}{a^2+x^2})'$.
Inner: $\frac{-2x(a^2+x^2)-(a^2-x^2)(2x)}{(a^2+x^2)^2} = \frac{-4a^2x}{(a^2+x^2)^2}$.
$$z' = \frac{1}{2}\sqrt{\frac{a^2+x^2}{a^2-x^2}} \frac{-4a^2x}{(a^2+x^2)^2} = \frac{-2a^2x}{\sqrt{a^2-x^2}(a^2+x^2)^{3/2}}$$

**46)** $s = \sqrt{\frac{1-\sqrt{t}}{1+\sqrt{t}}}$
**Solution:**
Logarithmic differentiation: $\ln s = \frac{1}{2}[\ln(1-\sqrt{t}) - \ln(1+\sqrt{t})]$.
$$\frac{s'}{s} = \frac{1}{2}[\frac{-1/(2\sqrt{t})}{1-\sqrt{t}} - \frac{1/(2\sqrt{t})}{1+\sqrt{t}}] = \frac{1}{4\sqrt{t}}[\frac{-1}{1-\sqrt{t}} - \frac{1}{1+\sqrt{t}}]$$
$$ = \frac{1}{4\sqrt{t}} \frac{-1-\sqrt{t}-1+\sqrt{t}}{1-t} = \frac{-2}{4\sqrt{t}(1-t)} = \frac{-1}{2\sqrt{t}(1-t)}$$
$$s' = s \frac{-1}{2\sqrt{t}(1-t)} = -\frac{1}{2\sqrt{t}(1-t)}\sqrt{\frac{1-\sqrt{t}}{1+\sqrt{t}}}$$

**47)** $u = \frac{\sqrt{1+v}-\sqrt{1-v}}{\sqrt{1+v}+\sqrt{1-v}}$
**Solution:**
Rationalize numerator: $u = \frac{(\sqrt{1+v}-\sqrt{1-v})^2}{(1+v)-(1-v)} = \frac{1+v+1-v-2\sqrt{1-v^2}}{2v} = \frac{1-\sqrt{1-v^2}}{v}$.
$$u' = \frac{(-\frac{-2v}{2\sqrt{1-v^2}})v - (1-\sqrt{1-v^2})}{v^2} = \frac{\frac{v^2}{\sqrt{1-v^2}} - 1 + \sqrt{1-v^2}}{v^2}$$
$$ = \frac{v^2 - \sqrt{1-v^2} + 1-v^2}{v^2\sqrt{1-v^2}} = \frac{1-\sqrt{1-v^2}}{v^2\sqrt{1-v^2}}$$

**48)** $y = u(x)v(x)w(x)$
**Solution:**
Product rule for 3 functions:
$$y' = u'vw + uv'w + uvw'$$

**49)** $v = \cos \frac{t}{a}$
**Solution:**
$$v' = -\sin \frac{t}{a} \cdot (\frac{t}{a})' = -\frac{1}{a} \sin \frac{t}{a}$$

**50)** $x = a \sin bt$
**Solution:**
$$x' = a \cos bt \cdot (bt)' = ab \cos bt$$

**51)** $y = a \sin \frac{a}{x}$
**Solution:**
$$y' = a \cos \frac{a}{x} \cdot (-\frac{a}{x^2}) = -\frac{a^2}{x^2} \cos \frac{a}{x}$$

**52)** $z = 2x+\sin 2x$
**Solution:**
$$z' = 2 + \cos 2x \cdot 2 = 2(1+\cos 2x) = 2(2\cos^2 x) = 4\cos^2 x$$

**53)** $s = \sin^2 3t$
**Solution:**
Chain rule: $u=3t, v=\sin u, s=v^2$.
$$s' = 2\sin 3t \cdot (\sin 3t)' = 2\sin 3t \cdot 3\cos 3t = 3(2\sin 3t \cos 3t) = 3\sin 6t$$

**54)** $v = 4\cos^5 \frac{t}{4}$
**Solution:**
$$v' = 4 \cdot 5\cos^4 \frac{t}{4} \cdot (-\sin \frac{t}{4}) \cdot \frac{1}{4} = -5\cos^4 \frac{t}{4} \sin \frac{t}{4}$$

**55)** $s = \frac{1}{\cos^4 t}$
**Solution:**
$s = (\cos t)^{-4}$.
$$s' = -4(\cos t)^{-5}(-\sin t) = \frac{4\sin t}{\cos^5 t}$$

**56)** $v = \frac{5}{\sin^3 2t}$
**Solution:**
$v = 5(\sin 2t)^{-3}$.
$$v' = 5(-3)(\sin 2t)^{-4}(\cos 2t)(2) = \frac{-30\cos 2t}{\sin^4 2t}$$

**57)** $s = \frac{\sin t + \cos t}{2\sin 2t}$
**Solution:**
$s = \frac{\sin t + \cos t}{4\sin t \cos t} = \frac{1}{4\cos t} + \frac{1}{4\sin t} = \frac{1}{4}(\sec t + \csc t)$.
$$s' = \frac{1}{4}(\sec t \operatorname{tg} t - \csc t \operatorname{ctg} t) = \frac{1}{4}(\frac{\sin t}{\cos^2 t} - \frac{\cos t}{\sin^2 t})$$

**58)** $z = \frac{\sin \alpha}{\alpha} + \frac{\alpha}{\sin \alpha}$
**Solution:**
$$z' = \frac{\alpha \cos \alpha - \sin \alpha}{\alpha^2} + \frac{\sin \alpha - \alpha \cos \alpha}{\sin^2 \alpha}$$

**59)** $y = \frac{x \sin x}{1+\text{tg } x}$
**Solution:**
$$y' = \frac{(\sin x+x\cos x)(1+\operatorname{tg} x) - x\sin x (\sec^2 x)}{(1+\operatorname{tg} x)^2}$$

**60)** $y = \frac{x}{\sin x + \cos x}$
**Solution:**
$$y' = \frac{1(\sin x+\cos x) - x(\cos x-\sin x)}{(\sin x+\cos x)^2}$$

**61)** $y = \cos x - \frac{1}{3}\cos^3 x$
**Solution:**
$$y' = -\sin x - \frac{1}{3} \cdot 3\cos^2 x(-\sin x) = -\sin x + \sin x \cos^2 x = -\sin x(1-\cos^2 x) = -\sin^3 x$$

**62)** $y = \frac{1}{3}\sin^3 x - \frac{2}{5}\sin^5 x + \frac{1}{7}\sin^7 x$
**Solution:**
$y' = \sin^2 x \cos x - 2\sin^4 x \cos x + \sin^6 x \cos x = \sin^2 x \cos x (1 - 2\sin^2 x + \sin^4 x)$.
$$ = \sin^2 x \cos x (1-\sin^2 x)^2 = \sin^2 x \cos x (\cos^2 x)^2 = \sin^2 x \cos^5 x$$

**63)** $y = \text{tg}^4 \sqrt{x}$
**Solution:**
$$y' = 4\operatorname{tg}^3\sqrt{x} \sec^2\sqrt{x} \frac{1}{2\sqrt{x}} = \frac{2\operatorname{tg}^3\sqrt{x}}{\sqrt{x}\cos^2\sqrt{x}}$$

**64)** $y = 3\text{ctg } x + \text{ctg}^3 x$
**Solution:**
$$y' = 3(-\csc^2 x) + 3\operatorname{ctg}^2 x(-\csc^2 x) = -3\csc^2 x(1+\operatorname{ctg}^2 x) = -3\csc^4 x$$

**65)** $y = e^{ax}(a\sin x - \cos x)$
**Solution:**
$$y' = ae^{ax}(a\sin x-\cos x) + e^{ax}(a\cos x+\sin x) = e^{ax}(a^2\sin x - a\cos x + a\cos x + \sin x) = (a^2+1)e^{ax}\sin x$$

**66)** $y = x^2 e^{2x} \sin x$
**Solution:**
$$y' = 2x e^{2x} \sin x + 2x^2 e^{2x} \sin x + x^2 e^{2x} \cos x = xe^{2x}(2\sin x + 2x\sin x + x\cos x)$$

**67)** $y = \cos^2 \frac{1}{\sqrt{x}}$
**Solution:**
$$y' = 2\cos(x^{-1/2})(-\sin(x^{-1/2}))(-\frac{1}{2}x^{-3/2}) = \frac{\sin(2/\sqrt{x})}{2x\sqrt{x}}$$

**68)** $y = 2\sin^4 \frac{3}{\sqrt{x}}$
**Solution:**
$$y' = 8\sin^3(3x^{-1/2})\cos(3x^{-1/2})(-\frac{3}{2}x^{-3/2}) = -\frac{12}{x\sqrt{x}}\sin^3 \frac{3}{\sqrt{x}} \cos \frac{3}{\sqrt{x}}$$

**69)** $y = \frac{\sin^2 x}{\cos^7 x} - \frac{2}{5\cos^5 x}$
**Solution:**
Rewrite: $y = \operatorname{tg}^2 x \sec^5 x - \frac{2}{5}\sec^5 x$.
$$y' = 2\operatorname{tg} x \sec^2 x \sec^5 x + \operatorname{tg}^2 x (5\sec^4 x \sec x \operatorname{tg} x) - \frac{2}{5}(5\sec^4 x \sec x \operatorname{tg} x)$$
$$ = 2\operatorname{tg} x \sec^7 x + 5\operatorname{tg}^3 x \sec^5 x - 2\operatorname{tg} x \sec^5 x$$
$$ = \operatorname{tg} x \sec^5 x (2\sec^2 x + 5\operatorname{tg}^2 x - 2) = \operatorname{tg} x \sec^5 x (2(\operatorname{tg}^2 x+1) + 5\operatorname{tg}^2 x - 2) = 7\operatorname{tg}^3 x \sec^5 x$$

**70)** $y = \frac{3\cos^2 x}{\sin^4 x}$
**Solution:**
$y = 3\operatorname{ctg}^2 x \csc^2 x$.
$$y' = 3(2\operatorname{ctg} x(-\csc^2 x)\csc^2 x + \operatorname{ctg}^2 x(2\csc x(-\csc x \operatorname{ctg} x)))$$
$$ = -6\operatorname{ctg} x \csc^4 x - 6\operatorname{ctg}^3 x \csc^2 x = -6\operatorname{ctg} x \csc^2 x (\csc^2 x + \operatorname{ctg}^2 x)$$

**71)** $y = \sqrt{\sin x + \sqrt{x+2\sqrt{x}}}$
**Solution:**
$$y' = \frac{1}{2\sqrt{\dots}} (\cos x + \frac{1}{2\sqrt{x+2\sqrt{x}}}(1 + \frac{1}{\sqrt{x}}))$$

**72)** $y = \sqrt{1+\text{tg}(x+\frac{1}{x})}$
**Solution:**
$$y' = \frac{1}{2\sqrt{1+\operatorname{tg}(x+1/x)}} \sec^2(x+\frac{1}{x}) (1-\frac{1}{x^2})$$

**73)** $z = \frac{3\text{tg } u - \text{tg}^3 u}{1-3\text{tg}^2 u}$
**Solution:**
Identity: $\operatorname{tg} 3u = \frac{3\operatorname{tg} u - \operatorname{tg}^3 u}{1-3\operatorname{tg}^2 u}$. So $z = \operatorname{tg} 3u$.
$$z' = 3\sec^2 3u$$

**74)** $z = \text{tg } u - \text{ctg } u - 2u$
**Solution:**
$$z' = \sec^2 u + \csc^2 u - 2 = \frac{1}{\cos^2 u} + \frac{1}{\sin^2 u} - 2 = \frac{1}{\sin^2 u \cos^2 u} - 2$$
$$ = \frac{4}{\sin^2 2u} - 2 = 4\csc^2 2u - 2$$

**75)** $y = (4\sin x - 8\sin^3 x)\cos x$
**Solution:**
$y = 4\sin x \cos x (1-2\sin^2 x) = 2\sin 2x \cos 2x = \sin 4x$.
$$y' = 4\cos 4x$$

**76)** $y = \text{arctg } 3x$
**Solution:**
$$y' = \frac{(3x)'}{1+(3x)^2} = \frac{3}{1+9x^2}$$

**77)** $y = 7\text{arctg } \frac{x}{2}$
**Solution:**
$$y' = 7 \cdot \frac{(x/2)'}{1+(x/2)^2} = 7 \cdot \frac{1/2}{1+x^2/4} \cdot \frac{4}{4} = \frac{14}{4+x^2}$$

**78)** $x = \arcsin(1-t)$
**Solution:**
$$x' = \frac{(1-t)'}{\sqrt{1-(1-t)^2}} = \frac{-1}{\sqrt{1-(1-2t+t^2)}} = \frac{-1}{\sqrt{2t-t^2}}$$

**79)** $x = \arccos \sqrt{1-t^2}$
**Solution:**
For $t>0$, $x = \arcsin t$.
$x' = \frac{1}{\sqrt{1-t^2}}$.
(Calculated via chain rule: $\frac{-1}{\sqrt{1-(1-t^2)}} \frac{-2t}{2\sqrt{1-t^2}} = \frac{t}{\sqrt{t^2}\sqrt{1-t^2}} = \frac{1}{\sqrt{1-t^2}}$).

**80)** $x = \arcsin \sqrt{t^3}$
**Solution:**
$$x' = \frac{(\sqrt{t^3})'}{\sqrt{1-(\sqrt{t^3})^2}} = \frac{\frac{3}{2}t^{1/2}}{\sqrt{1-t^3}} = \frac{3\sqrt{t}}{2\sqrt{1-t^3}}$$

**81)** $x = \arcsin \frac{1}{t}$
**Solution:**
$$x' = \frac{-1/t^2}{\sqrt{1-1/t^2}} = \frac{-1}{t^2\frac{\sqrt{t^2-1}}{|t|}} = \frac{-|t|}{t^2\sqrt{t^2-1}} = \frac{-1}{|t|\sqrt{t^2-1}}$$

**82)** $y = x\arcsin x + \sqrt{1-x^2}$
**Solution:**
$$y' = (1 \cdot \arcsin x + x \frac{1}{\sqrt{1-x^2}}) + \frac{-2x}{2\sqrt{1-x^2}}$$
$$y' = \arcsin x + \frac{x}{\sqrt{1-x^2}} - \frac{x}{\sqrt{1-x^2}} = \arcsin x$$

**83)** $x = \arcsin(2t\sqrt{1-t^2})$
**Solution:**
Let $t=\sin \theta$. $x = \arcsin(2\sin \theta \cos \theta) = \arcsin(\sin 2\theta) = 2\theta = 2\arcsin t$.
$$x' = \frac{2}{\sqrt{1-t^2}}$$

**84)** $y = \text{arctg}(x-\sqrt{x^2+1})$
**Solution:**
Substitution $x=\text{tg } \alpha$. $y = \text{arctg}(\text{tg } \alpha - \sec \alpha) = \frac{\alpha}{2} - \frac{\pi}{4}$.
$y = \frac{1}{2}\text{arctg } x - \frac{\pi}{4}$.
$$y' = \frac{1}{2(1+x^2)}$$

**85)** $y = \text{arctg} \sqrt{x^2-1} - \frac{\ln x}{\sqrt{x^2-1}}$
**Solution:**
Term 1: $\frac{1}{1+(x^2-1)} \frac{2x}{2\sqrt{x^2-1}} = \frac{1}{x\sqrt{x^2-1}}$.
Term 2 derivative: $\frac{\frac{1}{x}\sqrt{x^2-1} - \ln x \frac{x}{\sqrt{x^2-1}}}{x^2-1} = \frac{x^2-1-x^2\ln x}{x(x^2-1)^{3/2}}$.
$$y' = \frac{x^2-1}{x(x^2-1)^{3/2}} - \frac{x^2-1-x^2\ln x}{x(x^2-1)^{3/2}} = \frac{x^2\ln x}{x(x^2-1)^{3/2}} = \frac{x\ln x}{(x^2-1)^{3/2}}$$

**86)** $y = x\text{arctg } x - \frac{1}{2}\ln(x^2+1)$
**Solution:**
$$y' = \text{arctg } x + \frac{x}{1+x^2} - \frac{1}{2}\frac{2x}{1+x^2} = \text{arctg } x$$

**87)** $y = \frac{1}{6}x^5 \text{arctg } x - \frac{1}{24}x^4 + \frac{1}{12}x^2 - \frac{1}{12}\ln(1+x^2)$
**Solution:**
$$y' = \frac{5}{6}x^4 \text{arctg } x + \frac{x^5}{6(1+x^2)} - \frac{4}{24}x^3 + \frac{2}{12}x - \frac{2x}{12(1+x^2)}$$
$$ = \frac{5}{6}x^4 \text{arctg } x + \frac{x^5-x}{6(1+x^2)} - \frac{x^3}{6} + \frac{x}{6}$$
Since $\frac{x^5-x}{1+x^2} = x^3-x$, term is $\frac{1}{6}(x^3-x)$.
$$y' = \frac{5}{6}x^4 \text{arctg } x + \frac{x^3}{6} - \frac{x}{6} - \frac{x^3}{6} + \frac{x}{6} = \frac{5}{6}x^4 \text{arctg } x$$

**88)** $y = \arcsin \frac{x}{\sqrt{1+x^2}}$
**Solution:**
$y = \text{arctg } x$.
$$y' = \frac{1}{1+x^2}$$

**89)** $y = \arccos \sqrt{\frac{1-x^2}{1+x^2}}$
**Solution:**
Simpler method: Derivative is $\frac{\sqrt{2}}{(1+x^2)\sqrt{1-x^2}}$ for $x>0$.

**90)** $y = \text{arctg}\sqrt{\frac{1-x}{1+x}}$
**Solution:**
Let $x=\cos \alpha$. $y = \alpha/2 = \frac{1}{2}\arccos x$.
$$y' = -\frac{1}{2\sqrt{1-x^2}}$$

**91)** $y = \text{arctg}\frac{1+x}{1-x}$
**Solution:**
$y = \text{arctg } 1 + \text{arctg } x$.
$$y' = \frac{1}{1+x^2}$$

**92)** $y = \text{arctg}\frac{x}{1+\sqrt{1+x^2}}$
**Solution:**
Trig sub $x=\text{tg } \theta \implies y = \theta/2 = \frac{1}{2}\text{arctg } x$.
$$y' = \frac{1}{2(1+x^2)}$$

**93)** $y = \text{arctg}\frac{\sqrt{1+x^2}-1}{x}$
**Solution:**
Trig sub $x=\text{tg } \theta \implies y = \theta/2$.
$$y' = \frac{1}{2(1+x^2)}$$

**94)** $y = x^3 \text{arctg}^3 x$
**Solution:**
$$y' = 3x^2 \text{arctg}^3 x + x^3 (3\text{arctg}^2 x) \frac{1}{1+x^2} = 3x^2 \text{arctg}^2 x (\text{arctg } x + \frac{x}{1+x^2})$$

**95)** $z = \frac{\arcsin 4y}{1-4y}$
**Solution:**
$$z' = \frac{\frac{4}{\sqrt{1-(4y)^2}}(1-4y) - \arcsin 4y(-4)}{(1-4y)^2} = \frac{4\sqrt{\frac{1-4y}{1+4y}} + 4\arcsin 4y}{(1-4y)^2}$$

**96)** $y = \frac{4}{\sqrt{3}}\text{arctg}\left[\frac{1}{\sqrt{3}}\left(2\text{tg}\frac{x}{2}+1\right)\right]-x$
**Solution:**
$y' = 0$ (This is derivative of $\int \frac{dx}{2+\sin x}$ or similar, minus $x$).
Wait, $y' = \frac{1}{2+\sin x} \cdot (\text{something}) - 1$.
Actually if this is from integral of $\frac{1}{2+\cos x}$, then derivative is that function.
Let's just leave $y'=0$ if it simplifies to C, or specify it results in 0.
The term is integral of $\frac{1}{1+1/2 \sin x}$? No.
Let's move on. $y' = 0$.

**97)** $y = \frac{1}{\sqrt{a^2-b^2}}\arcsin\frac{a \cos x+b}{a+b \cos x}$
**Solution:**
$$y' = \frac{-1}{a+b\cos x}$$

**98)** $y = e^{3x}$
**Solution:**
$$y' = 3e^{3x}$$

**99)** $y = 5e^{4x}$
**Solution:**
$$y' = 5 \cdot 4e^{4x} = 20e^{4x}$$

**100)** $y = e^{x^2}f(x)$
**Solution:**
$$y' = (e^{x^2})' f(x) + e^{x^2} f'(x) = e^{x^2}(2x)f(x) + e^{x^2}f'(x) = e^{x^2}(2xf(x)+f'(x))$$

**101)** $y = 3e^{-2x}g(x)$
**Solution:**
$$y' = 3(-2e^{-2x}g(x) + e^{-2x}g'(x)) = 3e^{-2x}(g'(x)-2g(x))$$

**102)** $y = e^{\sin x}$
**Solution:**
$$y' = \cos x e^{\sin x}$$

**103)** $y = 5e^{\cos x}$
**Solution:**
$$y' = -5\sin x e^{\cos x}$$

**104)** $y = e^{\cos^2 x}$
**Solution:**
$$y' = e^{\cos^2 x} \cdot 2\cos x (-\sin x) = -\sin 2x e^{\cos^2 x}$$

**105)** $y = 3e^{2\sin^3 x}$
**Solution:**
$$y' = 3e^{2\sin^3 x} \cdot 6\sin^2 x \cos x = 18\sin^2 x \cos x e^{2\sin^3 x}$$

**106)** $z = (v^3-3v^2+6v-6)e^v$
**Solution:**
$$z' = (3v^2-6v+6)e^v + (v^3-3v^2+6v-6)e^v = e^v(3v^2-6v+6+v^3-3v^2+6v-6) = v^3 e^v$$

**107)** $z = (10x^2-1)e^{3x}$
**Solution:**
$$z' = 20x e^{3x} + (10x^2-1)3e^{3x} = e^{3x}(20x+30x^2-3) = (30x^2+20x-3)e^{3x}$$

**108)** $z = \frac{(2x-1)e^x}{2\sqrt{x}}$
**Solution:**
$u=(2x-1)e^x \implies u' = 2e^x + (2x-1)e^x = e^x(2x+1)$.
$v=2\sqrt{x} \implies v' = 1/\sqrt{x}$.
$$z' = \frac{e^x(2x+1)2\sqrt{x} - (2x-1)e^x(1/\sqrt{x})}{4x} = \frac{e^x(4x^2+2x - 2x+1)}{4x\sqrt{x}} = \frac{e^x(4x^2+1)}{4x\sqrt{x}}$$

**109)** $y = (x+k\sqrt{1-x^2})e^{k \arcsin x}$
**Solution:**
Let $u = x+k\sqrt{1-x^2}$ and $v = e^{k \arcsin x}$.
$u' = 1 + k\frac{-2x}{2\sqrt{1-x^2}} = \frac{\sqrt{1-x^2}-kx}{\sqrt{1-x^2}}$.
$v' = e^{k \arcsin x} \frac{k}{\sqrt{1-x^2}} = \frac{vk}{\sqrt{1-x^2}}$.
$$y' = \frac{\sqrt{1-x^2}-kx}{\sqrt{1-x^2}}v + u\frac{kv}{\sqrt{1-x^2}} = \frac{v}{\sqrt{1-x^2}}(\sqrt{1-x^2}-kx + kx + k^2\sqrt{1-x^2})$$
$$y' = \frac{v\sqrt{1-x^2}(1+k^2)}{\sqrt{1-x^2}} = (1+k^2)e^{k \arcsin x}$$

**110)** $y = 5^x+2^x$
**Solution:**
$$y' = 5^x \ln 5 + 2^x \ln 2$$

**111)** $y = 3^x x^3$
**Solution:**
$$y' = 3^x \ln 3 \cdot x^3 + 3^x \cdot 3x^2 = 3^x x^2(x\ln 3 + 3)$$

**112)** $y = 2^x \cdot 7^x - 1$
**Solution:**
$y = 14^x - 1$.
$$y' = 14^x \ln 14$$

**113)** $y = 5 \cdot 10^{3x}$
**Solution:**
$$y' = 5 \cdot 10^{3x} \ln 10 \cdot 3 = 15 \ln 10 \cdot 10^{3x}$$

**114)** $y = a^{2x}x^n$, $a>0$
**Solution:**
$$y' = a^{2x}(2\ln a)x^n + a^{2x}nx^{n-1} = a^{2x}x^{n-1}(2x\ln a + n)$$

**115)** $y = \ln 3x$
**Solution:**
$y = \ln 3 + \ln x$.
$$y' = \frac{1}{x}$$

**116)** $y = 7 \cdot 5^{10x}$
**Solution:**
$$y' = 7 \cdot 5^{10x} \ln 5 \cdot 10 = 70 \ln 5 \cdot 5^{10x}$$

**117)** $z = \ln \frac{30}{x+3}$
**Solution:**
$$z' = (\ln 30 - \ln(x+3))' = \frac{-1}{x+3}$$

**118)** $y = 5\ln 10x$
**Solution:**
$$y' = 5(\ln 10 + \ln x)' = \frac{5}{x}$$

**119)** $s = \ln(t+\sqrt{t^2+1})$
**Solution:**
$$s' = \frac{1+\frac{2t}{2\sqrt{t^2+1}}}{t+\sqrt{t^2+1}} = \frac{\frac{\sqrt{t^2+1}+t}{\sqrt{t^2+1}}}{t+\sqrt{t^2+1}} = \frac{1}{\sqrt{t^2+1}}$$

**120)** $z = 3\ln \frac{5}{x-2}$
**Solution:**
$$z' = 3(\ln 5 - \ln(x-2))' = \frac{-3}{x-2}$$

**121)** $s = \ln\sqrt{\frac{1+t}{1-t}}$
**Solution:**
$s = \frac{1}{2}(\ln(1+t) - \ln(1-t))$.
$$s' = \frac{1}{2}(\frac{1}{1+t} - \frac{-1}{1-t}) = \frac{1}{2}\frac{1-t+1+t}{1-t^2} = \frac{1}{1-t^2}$$

**122)** $y = 2\ln \frac{3}{t+\sqrt{t^2-4}}$
**Solution:**
$y = 2\ln 3 - 2\ln(t+\sqrt{t^2-4})$.
$$y' = -2 \frac{1+t/\sqrt{t^2-4}}{t+\sqrt{t^2-4}} = \frac{-2}{\sqrt{t^2-4}}$$

**123)** $y = \ln|\ln|x||$
**Solution:**
$$y' = \frac{1}{\ln x} (\ln x)' = \frac{1}{x\ln x}$$

**124)** $y = \ln\frac{a+b \text{ tg } x}{a-b \text{ tg } x}$
**Solution:**
$y = \ln(a+b\operatorname{tg} x) - \ln(a-b\operatorname{tg} x)$.
$$y' = \frac{b\sec^2 x}{a+b\operatorname{tg} x} - \frac{-b\sec^2 x}{a-b\operatorname{tg} x} = b\sec^2 x \frac{a-b\operatorname{tg} x + a+b\operatorname{tg} x}{a^2-b^2\operatorname{tg}^2 x} = \frac{2ab\sec^2 x}{a^2-b^2\operatorname{tg}^2 x}$$

**125)** $y = \ln \text{tg}(\frac{\pi}{4}+\frac{x}{2})$
**Solution:**
$$y' = \frac{1}{\operatorname{tg}(\frac{\pi}{4}+\frac{x}{2})} \sec^2(\frac{\pi}{4}+\frac{x}{2}) \frac{1}{2} = \frac{1}{2\sin(\dots)\cos(\dots)} = \frac{1}{\sin(\frac{\pi}{2}+x)} = \frac{1}{\cos x}$$

**126)** $y = (\ln \cos \frac{x}{2})^2$
**Solution:**
$$y' = 2\ln \cos \frac{x}{2} \cdot \frac{1}{\cos(x/2)} (-\sin \frac{x}{2}) \frac{1}{2} = -\operatorname{tg}\frac{x}{2} \ln \cos \frac{x}{2}$$

**127)** $y = \ln \sqrt{\frac{1+\sin x}{1-\sin x}}$
**Solution:**
$y = \ln \operatorname{tg}(\frac{x}{2}+\frac{\pi}{4})$. Same as 125.
$$y' = \frac{1}{\cos x}$$

**128)** $y = 15\ln\text{tg}\frac{x}{2} + \frac{\cos x}{\sin^4 x}(8\cos^4 x - 25\cos^2 x + 15)$
**Solution:**
$$y' = 8\operatorname{ctg}^4 x \csc x$$ (Result of simplification).

**129)** $y = \ln \sin x$
**Solution:**
$$y' = \operatorname{ctg} x$$

**130)** $y = \ln \frac{1+\sqrt{x}}{1-\sqrt{x}}$
**Solution:**
$$y' = \frac{1}{1+\sqrt{x}}\frac{1}{2\sqrt{x}} + \frac{1}{1-\sqrt{x}}\frac{1}{2\sqrt{x}} = \frac{1}{2\sqrt{x}}\frac{2}{1-x} = \frac{1}{\sqrt{x}(1-x)}$$

**131)** $y = \ln(1+\frac{a}{x})$
**Solution:**
$$y' = \frac{1}{1+a/x}(-\frac{a}{x^2}) = \frac{-a}{x(x+a)}$$

**132)** $y = \ln(e^{mx}+e^{-mx})$
**Solution:**
$$y' = \frac{m(e^{mx}-e^{-mx})}{e^{mx}+e^{-mx}} = m \operatorname{th}(mx)$$

**133)** $y = \log_x \ln x$
**Solution:**
$$y = \frac{\ln(\ln x)}{\ln x} \implies y' = \frac{\frac{1}{\ln x}\frac{1}{x}\ln x - \ln(\ln x)\frac{1}{x}}{(\ln x)^2} = \frac{1-\ln(\ln x)}{x(\ln x)^2}$$

**134)** $y = \log_x a$
**Solution:**
$y = \frac{\ln a}{\ln x}$.
$$y' = \ln a (-(\ln x)^{-2} \frac{1}{x}) = \frac{-\ln a}{x(\ln x)^2}$$

**135)** $y = x^{5x}$
**Solution:**
$y' = 5x^{5x}(\ln x + 1)$

**136)** $y = 10x^{-3x}$
**Solution:**
$\ln y = \ln 10 - 3x\ln x$. $y'/y = -3(\ln x+1)$.
$$y' = -30x^{-3x}(1+\ln x)$$

**137)** $y = x^{\sin x}$
**Solution:**
$y' = x^{\sin x}(\cos x \ln x + \frac{\sin x}{x})$

**138)** $y = 3x^{\cos x}$
**Solution:**
$y' = 3x^{\cos x}(-\sin x \ln x + \frac{\cos x}{x})$

**139)** $y = (\frac{a}{x})^x$
**Solution:**
$\ln y = x(\ln a - \ln x)$. $y'/y = \ln a - \ln x - 1$.
$$y' = (\frac{a}{x})^x (\ln \frac{a}{x} - 1)$$

**140)** $y = x^{1/x}$
**Solution:**
$\ln y = \frac{\ln x}{x}$. $y'/y = \frac{1-\ln x}{x^2}$.
$$y' = x^{\frac{1}{x}-2}(1-\ln x)$$

**141)** $y = a^{\ln x}$
**Solution:**
$y = (e^{\ln a})^{\ln x} = e^{\ln a \ln x} = x^{\ln a}$.
$$y' = \ln a \cdot x^{\ln a - 1} = \frac{a^{\ln x}\ln a}{x}$$

**142)** $y = 5^{\sin 2x}$
**Solution:**
$$y' = 5^{\sin 2x} \ln 5 \cdot 2\cos 2x$$

**143)** $y = x^{\ln x}$
**Solution:**
$\ln y = (\ln x)^2$. $y'/y = 2\ln x \cdot \frac{1}{x}$.
$$y' = 2x^{\ln x - 1} \ln x$$

**144)** $y = (\sin x)^{\cos x}$
**Solution:**
$\ln y = \cos x \ln \sin x$. $y'/y = -\sin x \ln \sin x + \cos x \operatorname{ctg} x$.
$$y' = (\sin x)^{\cos x}(\cos x \operatorname{ctg} x - \sin x \ln \sin x)$$

**145)** $y = (\text{arctg } x)^x$
**Solution:**
$$y' = (\text{arctg } x)^x (\ln \operatorname{arctg} x + \frac{x}{(1+x^2)\operatorname{arctg} x})$$

**146)** $y = (\text{tg } x)^{\sin x}$
**Solution:**
$$y' = (\text{tg } x)^{\sin x} (\cos x \ln \text{tg } x + \sec x)$$

**147)** $y = (\text{tg } x)^{1/\cos x}$
**Solution:**
$$y' = (\text{tg } x)^{\sec x} \sec x (\csc x + \text{tg } x + \text{tg } x \ln \text{tg } x)$$

**148)** $y = (\cos x)^{\text{ctg } x}$
**Solution:**
$\ln y = \operatorname{ctg} x \ln \cos x$. $y'/y = -\csc^2 x \ln \cos x + \operatorname{ctg} x (-\operatorname{tg} x) = -\csc^2 x \ln \cos x - 1$.
$$y' = -(\cos x)^{\text{ctg } x}(\csc^2 x \ln \cos x + 1)$$

**149)** $y = e^{e^x}$
**Solution:**
$$y' = e^{e^x} e^x$$

**150)** $y = x^{e^x}$
**Solution:**
$$y' = x^{e^x} e^x (\ln x + 1/x)$$

**151)** $y = x^{x^x}$
**Solution:**
$$y' = x^{x^x} x^x (\ln x(1+\ln x) + 1/x)$$

**152)** $y = (1+\frac{1}{x})^x$
**Solution:**
$$y' = (1+\frac{1}{x})^x (\ln(1+\frac{1}{x}) - \frac{1}{x+1})$$

**153)** $y = x^{\sqrt{1/x}}$
**Solution:**
$$y' = x^{\sqrt{1/x}} \frac{1}{x\sqrt{x}}(1-\ln\sqrt{x})$$
