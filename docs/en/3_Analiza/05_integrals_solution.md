## Integrals - Solutions

### Ex 1. Calculate the integrals

**1)** $\int \frac{x\sqrt{x} - x\sqrt[4]{x}}{\sqrt[3]{x}} dx$
**Solution:**
$$ \int (x^{7/6} - x^{11/12}) dx = \frac{6}{13}x^{13/6} - \frac{12}{23}x^{23/12} $$

**2)** $\int (3+2\sqrt[4]{x})^3 dx$
**Solution:**
$$ 27x + \frac{216}{5}x^{5/4} + 24x^{3/2} + \frac{32}{7}x^{7/4} $$

**3)** $\int \frac{\sqrt{x}-2\sqrt[3]{x^2}+4\sqrt[6]{x^3}}{6\sqrt[3]{x}} dx$
**Solution:**
$$ \frac{1}{7}x^{7/6} - \frac{1}{2}x^{4/3} + \frac{2}{7}x^{7/6} = \frac{3}{7}x^{7/6} - \frac{1}{2}x^{4/3} $$

**4)** $\int \frac{3+5\sqrt[3]{x^2}}{\sqrt[3]{x^2}} dx$
**Solution:**
$$ \int (3x^{-2/3} + 5) dx = 9x^{1/3} + 5x $$

**5)** $\int \frac{dx}{\sqrt{3x+1}}$
**Solution:**
$$ \frac{2}{3}\sqrt{3x+1} $$

**6)** $\int \sqrt{a+bx} dx$
**Solution:**
Let $u = a+bx$. Then $du = b dx \implies dx = \frac{1}{b} du$.
$$ \int \sqrt{u} \frac{1}{b} du = \frac{1}{b} \int u^{1/2} du = \frac{1}{b} \frac{u^{3/2}}{3/2} = \frac{2}{3b} (a+bx)^{3/2} $$

**7)** $\int \frac{x dx}{\sqrt[3]{2x^2-1}}$
**Solution:**
Let $u = 2x^2-1$. Then $du = 4x dx \implies x dx = \frac{1}{4} du$.
$$ \int \frac{1/4 du}{u^{1/3}} = \frac{1}{4} \int u^{-1/3} du = \frac{1}{4} \cdot \frac{3}{2} u^{2/3} = \frac{3}{8} (2x^2-1)^{2/3} $$

**8)** $\int x \sqrt{1+x^2} dx$
**Solution:**
Let $u = 1+x^2$. Then $du = 2x dx \implies x dx = \frac{1}{2} du$.
$$ \int \sqrt{u} \frac{1}{2} du = \frac{1}{2} \cdot \frac{2}{3} u^{3/2} = \frac{1}{3} (1+x^2)^{3/2} $$

**9)** $\int \frac{x}{\sqrt{3-5x^2}} dx$
**Solution:**
Let $u = 3-5x^2$. Then $du = -10x dx \implies x dx = -\frac{1}{10} du$.
$$ \int \frac{-1/10 du}{\sqrt{u}} = -\frac{1}{10} \int u^{-1/2} du = -\frac{1}{10} \cdot 2u^{1/2} = -\frac{1}{5} \sqrt{3-5x^2} $$

**10)** $\int \frac{x-1}{\sqrt[3]{x+1}} dx$
**Solution:**
Let $t = x+1 \implies x = t-1$ and $dx = dt$.
$$ \int \frac{t-1-1}{\sqrt[3]{t}} dt = \int \frac{t-2}{t^{1/3}} dt = \int (t^{2/3} - 2t^{-1/3}) dt $$
$$ = \frac{3}{5}t^{5/3} - 2 \cdot \frac{3}{2}t^{2/3} = \frac{3}{5}(x+1)^{5/3} - 3(x+1)^{2/3} $$

**11)** $\int \frac{x}{\sqrt{x^2-6}} dx$
**Solution:**
Let $u = x^2-6 \implies du = 2x dx$.
$$ \frac{1}{2} \int u^{-1/2} du = \frac{1}{2} \cdot 2\sqrt{u} = \sqrt{x^2-6} $$

**12)** $\int \frac{x^2 dx}{\sqrt[3]{x^3+1}}$
**Solution:**
Let $u = x^3+1 \implies du = 3x^2 dx$.
$$ \frac{1}{3} \int u^{-1/3} du = \frac{1}{3} \cdot \frac{3}{2}u^{2/3} = \frac{1}{2}(x^3+1)^{2/3} $$

**13)** $\int e^{1/x} \frac{dx}{x^2}$
**Solution:**
$$ -e^{1/x} $$

**14)** $\int x e^{-x^2} dx$
**Solution:**
$$ -\frac{1}{2}e^{-x^2} $$

**15)** $\int \frac{dx}{2\cos^2 3x}$
**Solution:**
$$ \frac{1}{6}\operatorname{tg} 3x $$

**16)** $\int x \sin(2x^2+1) dx$
**Solution:**
$$ -\frac{1}{4}\cos(2x^2+1) $$

**17)** $\int \sin^3 x \cos x dx$
**Solution:**
$$ \frac{1}{4}\sin^4 x $$

**18)** $\int \frac{\cos x}{\sqrt{1+\sin x}} dx$
**Solution:**
$$ 2\sqrt{1+\sin x} $$

**19)** $\int \frac{\sin x}{a+b\cos x} dx$
**Solution:**
Let $u = a+b\cos x \implies du = -b\sin x dx \implies \sin x dx = -\frac{1}{b} du$.
$$ \int \frac{-1/b du}{u} = -\frac{1}{b} \ln|u| = -\frac{1}{b} \ln|a+b\cos x| $$

**20)** $\int \cos x \cdot e^{\sin x} dx$
**Solution:**
$$ e^{\sin x} $$

**21)** $\int \frac{x^3 dx}{\cos^2 x^4}$
**Solution:**
$$ \frac{1}{4}\operatorname{tg}(x^4) $$

**22)** $\int \frac{\operatorname{tg} x}{\cos^2 x} dx$
**Solution:**
$$ \frac{1}{2}\operatorname{tg}^2 x $$

**23)** $\int \frac{x^2 dx}{\cos^2(x^3+1)}$
**Solution:**
$$ \frac{1}{3}\operatorname{tg}(x^3+1) $$

**24)** $\int \frac{(\ln x)^2}{x} dx$
**Solution:**
$$ \frac{1}{3}(\ln x)^3 $$

**25)** $\int \frac{dx}{e^x+e^{-x}} = \int \frac{e^x}{e^{2x}+1} dx$
**Solution:**
$$ \operatorname{arctg}(e^x) $$

**26)** $\int \frac{e^x dx}{2e^x+1}$
**Solution:**
$$ \frac{1}{2}\ln(2e^x+1) $$

**27)** $\int x \ln(1+x^2) dx$
**Solution:**
$$ \frac{1}{2}((x^2+1)\ln(1+x^2) - x^2) $$

**28)** $\int \sqrt{2+\ln|x|} \frac{dx}{x}$
**Solution:**
Let $u = 2+\ln|x| \implies du = \frac{1}{x} dx$.
$$ \int \sqrt{u} du = \frac{2}{3}u^{3/2} = \frac{2}{3}(2+\ln|x|)^{3/2} $$

**29)** $\int 6^{1-x} dx$
**Solution:**
Let $u = 1-x \implies du = -dx$.
$$ \int 6^u (-du) = -\frac{6^u}{\ln 6} = -\frac{6^{1-x}}{\ln 6} $$

**30)** $\int \frac{dx}{x\sqrt{1-\ln^2|x|}}$
**Solution:**
Let $u = \ln|x| \implies du = \frac{dx}{x}$.
$$ \int \frac{du}{\sqrt{1-u^2}} = \arcsin u = \arcsin(\ln|x|) $$

**31)** $\int \frac{\ln|\operatorname{arctg} x|}{1+x^2} dx$
**Solution:**
Let $t = \operatorname{arctg} x \implies dt = \frac{dx}{1+x^2}$.
$$ \int \ln|t| dt = t\ln|t| - t = \operatorname{arctg} x (\ln|\operatorname{arctg} x| - 1) $$

**32)** $\int x e^{x^2}(x^2+1) dx$
**Solution:**
Let $t = x^2 \implies dt = 2x dx$. Then $\int \frac{1}{2} e^t (t+1) dt$.
Integration by parts: $u=t+1, dv=e^t dt \implies du=dt, v=e^t$.
$$ \frac{1}{2} ((t+1)e^t - \int e^t dt) = \frac{1}{2}(te^t + e^t - e^t) = \frac{1}{2} t e^t = \frac{1}{2} x^2 e^{x^2} $$

**33)** $\int \frac{x^2 dx}{\sqrt{1-x^6}}$
**Solution:**
Let $u = x^3 \implies du = 3x^2 dx$.
$$ \int \frac{1/3 du}{\sqrt{1-u^2}} = \frac{1}{3} \arcsin u = \frac{1}{3} \arcsin(x^3) $$

**34)** $\int \frac{dx}{(1+x^2)\operatorname{arctg} x}$
**Solution:**
Let $u = \operatorname{arctg} x \implies du = \frac{dx}{1+x^2}$.
$$ \int \frac{du}{u} = \ln|u| = \ln|\operatorname{arctg} x| $$

**35)** $\int \frac{(\pi - \arcsin x) dx}{\sqrt{1-x^2}}$
**Solution:**
Let $u = \arcsin x \implies du = \frac{dx}{\sqrt{1-x^2}}$.
$$ \int (\pi - u) du = \pi u - \frac{1}{2} u^2 = \pi \arcsin x - \frac{1}{2}(\arcsin x)^2 $$

**36)** $\int \frac{x dx}{x^4+1}$
**Solution:**
Let $u = x^2 \implies du = 2x dx$.
$$ \int \frac{1/2 du}{u^2+1} = \frac{1}{2} \operatorname{arctg} u = \frac{1}{2} \operatorname{arctg}(x^2) $$

**37)** $\int x^4(1+x^5)^3 dx$
**Solution:**
Let $u = 1+x^5 \implies du = 5x^4 dx$.
$$ \int u^3 \cdot \frac{1}{5} du = \frac{1}{5} \frac{u^4}{4} = \frac{1}{20}(1+x^5)^4 $$

**38)** $\int x^2 e^x dx$
**Solution:**
$$ e^x(x^2-2x+2) $$

**39)** $\int x^3 e^x dx$
**Solution:**
Integration by parts (tabular method):
$u=x^3 \to 3x^2 \to 6x \to 6 \to 0$
$dv=e^x dx \to e^x \to e^x \to e^x \to e^x \to e^x$
$$ x^3 e^x - 3x^2 e^x + 6x e^x - 6e^x = e^x(x^3-3x^2+6x-6) $$

**40)** $\int x^4 e^{2x} dx$
**Solution:**
Tabular integration:
$x^4 \xrightarrow{D} 4x^3 \xrightarrow{D} 12x^2 \xrightarrow{D} 24x \xrightarrow{D} 24 \xrightarrow{D} 0$
$e^{2x} \xrightarrow{I} \frac{1}{2}e^{2x} \xrightarrow{I} \frac{1}{4}e^{2x} \xrightarrow{I} \frac{1}{8}e^{2x} \xrightarrow{I} \frac{1}{16}e^{2x} \xrightarrow{I} \frac{1}{32}e^{2x}$
Sum: $+x^4(\frac{1}{2}e^{2x}) - 4x^3(\frac{1}{4}e^{2x}) + 12x^2(\frac{1}{8}e^{2x}) - 24x(\frac{1}{16}e^{2x}) + 24(\frac{1}{32}e^{2x})$
$$ e^{2x}(\frac{x^4}{2} - x^3 + \frac{3x^2}{2} - \frac{3x}{2} + \frac{3}{4}) $$

**41)** $\int x \cos x dx$
**Solution:**
$$ x\sin x + \cos x $$

**42)** $\int x^2 \cos x dx$
**Solution:**
Parts 1: $u=x^2, dv=\cos x dx \implies du=2x dx, v=\sin x$.
$= x^2 \sin x - \int 2x \sin x dx$.
Parts 2 for $\int x \sin x dx$: $u=x, dv=\sin x dx \implies du=dx, v=-\cos x$.
$\int x \sin x dx = -x \cos x - \int (-\cos x) dx = -x \cos x + \sin x$.
Total: $x^2 \sin x - 2(-x \cos x + \sin x) = x^2 \sin x + 2x \cos x - 2\sin x$.

**43)** $\int x^2 \sin 5x dx$
**Solution:**
Parts 1: $u=x^2, dv=\sin 5x dx \implies v=-\frac{1}{5}\cos 5x$.
$= -\frac{x^2}{5}\cos 5x + \frac{2}{5} \int x \cos 5x dx$.
Parts 2: $u=x, dv=\cos 5x dx \implies v=\frac{1}{5}\sin 5x$.
$\int x \cos 5x dx = \frac{x}{5}\sin 5x - \frac{1}{5} \int \sin 5x dx = \frac{x}{5}\sin 5x + \frac{1}{25}\cos 5x$.
Total: $-\frac{x^2}{5}\cos 5x + \frac{2}{5}(\frac{x}{5}\sin 5x + \frac{1}{25}\cos 5x) = -\frac{x^2}{5}\cos 5x + \frac{2x}{25}\sin 5x + \frac{2}{125}\cos 5x$.

**44)** $\int e^x \cos x dx$
**Solution:**
$$ \frac{e^x}{2}(\sin x + \cos x) $$

**45)** $\int e^{-2x} \sin 3x dx$
**Solution:**
Let $I = \int e^{-2x} \sin 3x dx$.
Parts 1: $u=e^{-2x}, dv=\sin 3x dx \implies du=-2e^{-2x}dx, v=-\frac{1}{3}\cos 3x$.
$I = -\frac{1}{3}e^{-2x}\cos 3x - \frac{2}{3} \int e^{-2x} \cos 3x dx$.
Parts 2 ($J = \int e^{-2x}\cos 3x dx$): $u=e^{-2x}, dv=\cos 3x dx \implies v=\frac{1}{3}\sin 3x$.
$J = \frac{1}{3}e^{-2x}\sin 3x + \frac{2}{3}I$.
Substitute J back: $I = -\frac{1}{3}e^{-2x}\cos 3x - \frac{2}{3}(\frac{1}{3}e^{-2x}\sin 3x + \frac{2}{3}I) = -\frac{1}{3}e^{-2x}\cos 3x - \frac{2}{9}e^{-2x}\sin 3x - \frac{4}{9}I$.
$I(1 + \frac{4}{9}) = -\frac{e^{-2x}}{9}(3\cos 3x + 2\sin 3x)$.
$\frac{13}{9}I = -\frac{e^{-2x}}{9}(3\cos 3x + 2\sin 3x) \implies I = -\frac{e^{-2x}}{13}(2\sin 3x + 3\cos 3x)$.

**46)** $\int e^x \cos^2 x dx$
**Solution:**
$$ \frac{e^x}{2} + \frac{e^x}{10}(\sin 2x + 2\cos 2x) $$

**47)** $\int \sqrt{x} \ln x dx$
**Solution:**
Parts: $u=\ln x, dv=x^{1/2}dx \implies du=\frac{1}{x}dx, v=\frac{2}{3}x^{3/2}$.
$\frac{2}{3}x^{3/2}\ln x - \int \frac{2}{3}x^{3/2} \cdot \frac{1}{x} dx = \frac{2}{3}x^{3/2}\ln x - \frac{2}{3} \int x^{1/2} dx$
$= \frac{2}{3}x^{3/2}\ln x - \frac{2}{3} \cdot \frac{2}{3}x^{3/2} = \frac{2}{3}x^{3/2}\ln x - \frac{4}{9}x^{3/2}$.

**48)** $\int (\ln |x|)^3 dx$
**Solution:**
$u=(\ln x)^3, dv=dx \implies du=3(\ln x)^2 \frac{1}{x} dx, v=x$.
$= x(\ln x)^3 - 3 \int (\ln x)^2 dx$.
For $\int (\ln x)^2 dx$: $u=(\ln x)^2, dv=dx \implies x(\ln x)^2 - 2\int \ln x dx = x(\ln x)^2 - 2(x\ln x - x)$.
Total: $x(\ln x)^3 - 3(x(\ln x)^2 - 2x\ln x + 2x) = x(\ln x)^3 - 3x(\ln x)^2 + 6x\ln x - 6x$.

**49)** $\int \frac{(\ln |x|)^2}{x^5} dx$
**Solution:**
$u=(\ln x)^2, dv=x^{-5}dx \implies du=\frac{2\ln x}{x}dx, v=-\frac{1}{4}x^{-4}$.
$= -\frac{1}{4x^4}(\ln x)^2 + \frac{1}{2} \int x^{-5} \ln x dx$.
Next part: $\int x^{-5}\ln x dx = -\frac{1}{4x^4}\ln x + \frac{1}{4}\int x^{-5}dx = -\frac{1}{4x^4}\ln x - \frac{1}{16x^4}$.
Total: $-\frac{(\ln x)^2}{4x^4} + \frac{1}{2}(-\frac{\ln x}{4x^4} - \frac{1}{16x^4}) = -\frac{1}{4x^4}(\ln^2 x + \frac{1}{2}\ln x + \frac{1}{8})$.

**50)** $\int \sqrt{x}(\ln|x|)^3 dx$
**Solution:**
Let $I_n = \int x^{1/2} (\ln x)^n dx$. Formula reduction or parts.
$u=(\ln x)^3, dv=x^{1/2}dx \implies v=\frac{2}{3}x^{3/2}$.
$= \frac{2}{3}x^{3/2}(\ln x)^3 - 2 \int x^{1/2}(\ln x)^2 dx$.
Using result from Ex 47 structure repeatedly:
$= \frac{2}{3}x^{3/2}((\ln x)^3 - 3(\ln x)^2 + \dots)$ Wait, coeffs:
$= \frac{2}{3}x^{3/2}(\ln x)^3 - 2 (\frac{2}{3}x^{3/2}(\ln x)^2 - \frac{4}{3} \int x^{1/2}\ln x dx)$
$= \frac{2}{3}x^{3/2}(\ln x)^3 - \frac{4}{3}x^{3/2}(\ln x)^2 + \frac{8}{3}(\frac{2}{3}x^{3/2}\ln x - \frac{4}{9}x^{3/2})$
$= \frac{2}{3}x^{3/2}((\ln x)^3 - 2(\ln x)^2 + \frac{8}{3}\ln x - \frac{32}{27})$.

**51)** $\int \frac{\ln|x|}{x^4} dx$
**Solution:**
$u=\ln x, dv=x^{-4}dx \implies v=-\frac{1}{3}x^{-3}$.
$= -\frac{1}{3x^3}\ln x - \int (-\frac{1}{3}x^{-3})\frac{1}{x} dx = -\frac{\ln x}{3x^3} + \frac{1}{3}\int x^{-4} dx$
$= -\frac{\ln x}{3x^3} - \frac{1}{9x^3} = -\frac{1}{3x^3}(\ln x + \frac{1}{3})$.

**52)** $\int \frac{(\ln x)^2}{\sqrt{x}} dx$
**Solution:**
$u=(\ln x)^2, dv=x^{-1/2}dx \implies v=2x^{1/2}$.
$= 2\sqrt{x}(\ln x)^2 - 4\int \frac{\ln x}{\sqrt{x}} dx$.
$= 2\sqrt{x}(\ln x)^2 - 4(2\sqrt{x}\ln x - 4\sqrt{x}) = 2\sqrt{x}(\ln^2 x - 4\ln x + 8)$.

**53)** $\int x^3 (\ln x)^2 dx$
**Solution:**
$u=(\ln x)^2, dv=x^3 dx \implies v=\frac{x^4}{4}$.
$= \frac{x^4}{4}(\ln x)^2 - \frac{1}{2} \int x^3 \ln x dx$.
$\int x^3 \ln x dx = \frac{x^4}{4}\ln x - \frac{x^4}{16}$.
$= \frac{x^4}{4}(\ln x)^2 - \frac{x^4}{8}\ln x + \frac{x^4}{32} = \frac{x^4}{4}(\ln^2 x - \frac{1}{2}\ln x + \frac{1}{8})$.

**54)** $\int x^n \ln x dx, n \neq -1$
**Solution:**
$u=\ln x, dv=x^n dx \implies v=\frac{x^{n+1}}{n+1}$.
$= \frac{x^{n+1}}{n+1}\ln x - \int \frac{x^{n+1}}{n+1} \frac{1}{x} dx = \frac{x^{n+1}}{n+1}\ln x - \frac{1}{n+1} \int x^n dx$
$= \frac{x^{n+1}}{n+1}\ln x - \frac{x^{n+1}}{(n+1)^2} = \frac{x^{n+1}}{n+1}(\ln x - \frac{1}{n+1})$.

**55)** $\int \frac{2x-13}{(x-5)^2} dx$
**Solution:**
$$ 2\ln|x-5| + \frac{3}{x-5} $$

**56)** $\int \frac{3x+1}{(x+2)^2} dx$
**Solution:**
Let $u = x+2 \implies x = u-2, dx = du$.
$$ \int \frac{3(u-2)+1}{u^2} du = \int \frac{3u-5}{u^2} du = \int (\frac{3}{u} - 5u^{-2}) du $$
$$ = 3\ln|u| - 5(\frac{-1}{u}) = 3\ln|x+2| + \frac{5}{x+2} $$

**57)** $\int \frac{dx}{2x^2-2x+5}$
**Solution:**
$$ \frac{1}{3} \operatorname{arctg} \frac{2x-1}{3} $$

**58)** $\int \frac{dx}{3x^2+2x+1}$
**Solution:**
$3x^2+2x+1 = 3(x^2 + \frac{2}{3}x + \frac{1}{3}) = 3((x+\frac{1}{3})^2 + \frac{2}{9})$.
$\int \frac{dx}{3((x+1/3)^2 + 2/9)} = \frac{1}{3} \int \frac{dx}{(x+1/3)^2 + (\sqrt{2}/3)^2}$.
Using $\int \frac{du}{u^2+a^2} = \frac{1}{a}\operatorname{arctg}\frac{u}{a}$:
$= \frac{1}{3} \cdot \frac{1}{\sqrt{2}/3} \operatorname{arctg}(\frac{x+1/3}{\sqrt{2}/3}) = \frac{1}{\sqrt{2}} \operatorname{arctg}(\frac{3x+1}{\sqrt{2}})$.

**59)** $\int \frac{dx}{13-6x+x^2}$
**Solution:**
$x^2-6x+13 = (x-3)^2 + 4 = (x-3)^2 + 2^2$.
$$ \int \frac{dx}{(x-3)^2+2^2} = \frac{1}{2} \operatorname{arctg}(\frac{x-3}{2}) $$

**60)** $\int \frac{3dx}{9x^2-6x+2}$
**Solution:**
$9x^2-6x+2 = (3x-1)^2 + 1$.
Let $u = 3x-1 \implies du = 3dx$.
$$ \int \frac{du}{u^2+1} = \operatorname{arctg} u = \operatorname{arctg}(3x-1) $$

**61)** $\int \frac{x+1}{x^2-x+1} dx$
**Solution:**
Isolate derivative of denominator $(2x-1)$ in numerator:
$x+1 = \frac{1}{2}(2x-1) + \frac{3}{2}$.
$$ \frac{1}{2} \int \frac{2x-1}{x^2-x+1} dx + \frac{3}{2} \int \frac{dx}{x^2-x+1} $$
1st part: $\frac{1}{2}\ln(x^2-x+1)$.
2nd part: $x^2-x+1 = (x-1/2)^2 + 3/4$.
$\frac{3}{2} \int \frac{dx}{(x-1/2)^2 + (\sqrt{3}/2)^2} = \frac{3}{2} \cdot \frac{2}{\sqrt{3}} \operatorname{arctg}(\frac{x-1/2}{\sqrt{3}/2}) = \sqrt{3}\operatorname{arctg}(\frac{2x-1}{\sqrt{3}})$.
Total: $\frac{1}{2}\ln(x^2-x+1) + \sqrt{3}\operatorname{arctg}(\frac{2x-1}{\sqrt{3}})$.

**62)** $\int \frac{4x-1}{2x^2-2x+1} dx$
**Solution:**
Derivative of denom: $4x-2$. Numerator: $4x-1 = (4x-2) + 1$.
$$ \int \frac{4x-2}{2x^2-2x+1} dx + \int \frac{dx}{2x^2-2x+1} $$
1st: $\ln(2x^2-2x+1)$.

2nd: $2(x^2-x+1/2) = 2((x-1/2)^2 + 1/4)$.
$\int \frac{dx}{2((x-1/2)^2 + 1/4)} = \frac{1}{2} \cdot \frac{1}{1/2} \operatorname{arctg}(\frac{x-1/2}{1/2}) = \operatorname{arctg}(2x-1)$.
Total: $\ln(2x^2-2x+1) + \operatorname{arctg}(2x-1)$.

**63)** $\int \frac{2x-1}{x^2-2x+5} dx$
**Solution:**
Derivative denom: $2x-2$. Num: $2x-1 = (2x-2)+1$.
$$ \int \frac{2x-2}{x^2-2x+5} dx + \int \frac{dx}{(x-1)^2+4} $$
$= \ln(x^2-2x+5) + \frac{1}{2}\operatorname{arctg}(\frac{x-1}{2})$.

**64)** $\int \frac{2x-10}{x^2-2x+10} dx$
**Solution:**
Derivative denom: $2x-2$. Num: $2x-10 = (2x-2) - 8$.
$$ \int \frac{2x-2}{x^2-2x+10} dx - 8 \int \frac{dx}{(x-1)^2+9} $$
$= \ln(x^2-2x+10) - 8 \cdot \frac{1}{3} \operatorname{arctg}(\frac{x-1}{3}) = \ln(x^2-2x+10) - \frac{8}{3}\operatorname{arctg}(\frac{x-1}{3})$.

**65)** $\int \frac{2x-20}{x^2-8x+25} dx$
**Solution:**
Derivative denom: $2x-8$. Num: $2x-20 = (2x-8)-12$.
$$ \int \frac{2x-8}{x^2-8x+25} dx - 12 \int \frac{dx}{(x-4)^2+9} $$
$= \ln(x^2-8x+25) - 12 \cdot \frac{1}{3}\operatorname{arctg}(\frac{x-4}{3}) = \ln(x^2-8x+25) - 4\operatorname{arctg}(\frac{x-4}{3})$.

**66)** $\int \frac{3x+4}{x^2+4x+8} dx$
**Solution:**
Derivative denom: $2x+4$. Num: $3x+4 = \frac{3}{2}(2x+4) - 2$.
$$ \frac{3}{2} \int \frac{2x+4}{x^2+4x+8} dx - 2 \int \frac{dx}{(x+2)^2+4} $$
$= \frac{3}{2}\ln(x^2+4x+8) - 2 \cdot \frac{1}{2}\operatorname{arctg}(\frac{x+2}{2}) = \frac{3}{2}\ln(x^2+4x+8) - \operatorname{arctg}(\frac{x+2}{2})$.

**67)** $\int \frac{x+6}{x^2-3} dx$
**Solution:**
$\int \frac{x}{x^2-3} dx + 6 \int \frac{dx}{x^2-3}$.
1st: $\frac{1}{2}\ln|x^2-3|$.
2nd: $6 \cdot \frac{1}{2\sqrt{3}} \ln|\frac{x-\sqrt{3}}{x+\sqrt{3}}| = \sqrt{3} \ln|\frac{x-\sqrt{3}}{x+\sqrt{3}}|$.
Total: $\frac{1}{2}\ln|x^2-3| + \sqrt{3}\ln|\frac{x-\sqrt{3}}{x+\sqrt{3}}|$.

**68)** $\int \frac{x+6}{x^2+3} dx$
**Solution:**
$\int \frac{x}{x^2+3} dx + 6 \int \frac{dx}{x^2+3}$.
$= \frac{1}{2}\ln(x^2+3) + 6 \cdot \frac{1}{\sqrt{3}} \operatorname{arctg}(\frac{x}{\sqrt{3}}) = \frac{1}{2}\ln(x^2+3) + 2\sqrt{3}\operatorname{arctg}(\frac{x}{\sqrt{3}})$.

**69)** $\int \frac{6x}{x^2+4x+13} dx$
**Solution:**
Derivative denom: $2x+4$. Num: $6x = 3(2x+4) - 12$.
$$ 3 \int \frac{2x+4}{x^2+4x+13} dx - 12 \int \frac{dx}{(x+2)^2+9} $$
$= 3\ln(x^2+4x+13) - 12 \cdot \frac{1}{3}\operatorname{arctg}(\frac{x+2}{3}) = 3\ln(x^2+4x+13) - 4\operatorname{arctg}(\frac{x+2}{3})$.

**70)** $\int \frac{10x-44}{x^2-4x+20} dx$
**Solution:**
Derivative denom: $2x-4$. Num: $10x-44 = 5(2x-4) - 44 + 20 = 5(2x-4) - 24$.
$$ 5 \int \frac{2x-4}{x^2-4x+20} dx - 24 \int \frac{dx}{(x-2)^2+16} $$
$= 5\ln(x^2-4x+20) - 24 \cdot \frac{1}{4} \operatorname{arctg}(\frac{x-2}{4}) = 5\ln(x^2-4x+20) - 6\operatorname{arctg}(\frac{x-2}{4})$.

**71)** $\int \frac{4x-5}{x^2-6x+10} dx$
**Solution:**
$$ 2\ln(x^2-6x+10) + 7\operatorname{arctg}(x-3) $$

**72)** $\int \frac{5x}{2+3x} dx$
**Solution:**
Divide: $\frac{5x}{3x+2} = \frac{5}{3} \frac{3x}{3x+2} = \frac{5}{3} \frac{(3x+2)-2}{3x+2} = \frac{5}{3}(1 - \frac{2}{3x+2})$.
$$ \int \frac{5}{3}(1 - \frac{2}{3x+2}) dx = \frac{5}{3}(x - 2 \cdot \frac{1}{3}\ln|3x+2|) = \frac{5}{3}x - \frac{10}{9}\ln|3x+2| $$

**73)** $\int \frac{x^2}{5x^2+12} dx$
**Solution:**
Divide: $\frac{x^2}{5x^2+12} = \frac{1}{5} \frac{5x^2}{5x^2+12} = \frac{1}{5} \frac{(5x^2+12)-12}{5x^2+12} = \frac{1}{5}(1 - \frac{12}{5x^2+12})$.
$\int \frac{1}{5} dx - \frac{12}{5} \int \frac{dx}{5x^2+12}$.
2nd int: $\int \frac{dx}{5(x^2 + 12/5)} = \frac{1}{5} \cdot \frac{1}{\sqrt{12/5}} \operatorname{arctg}(\frac{x}{\sqrt{12/5}}) = \frac{1}{5} \cdot \frac{\sqrt{5}}{2\sqrt{3}} \operatorname{arctg}(\frac{x\sqrt{5}}{2\sqrt{3}})$.
Total: $\frac{x}{5} - \frac{12}{5} \cdot \frac{\sqrt{5}}{2\sqrt{15}}\operatorname{arctg}(\dots) = \frac{x}{5} - \frac{2\sqrt{15}}{25}\operatorname{arctg}(\frac{x\sqrt{15}}{6})$.

**74)** $\int \frac{2x^2+7x+20}{x^2+6x+25} dx$
**Solution:**
Divide: $\frac{2(x^2+6x+25) - 12x - 50 + 7x + 20}{x^2+6x+25} = 2 + \frac{-5x-30}{x^2+6x+25} = 2 - 5\frac{x+6}{x^2+6x+25}$.
$\int 2 dx - 5 \int \frac{x+6}{x^2+6x+25} dx$.
For fraction: $x+6 = \frac{1}{2}(2x+6) + 3$.
$-5 \int (\frac{1}{2}\frac{2x+6}{denom} + \frac{3}{(x+3)^2+16}) dx$.
$- \frac{5}{2}\ln(x^2+6x+25) - 15 \cdot \frac{1}{4} \operatorname{arctg}(\frac{x+3}{4})$.
Total: $2x - 2.5\ln(x^2+6x+25) - 3.75\operatorname{arctg}(\frac{x+3}{4})$.

**75)** $\int \frac{7x^2+7x-176}{x^3-9x^2+6x+56} dx$
**Solution:**
Factor denominator: $W(-2)=0 \implies (x+2)$ is a factor.
$x^3-9x^2+6x+56 = (x+2)(x^2-11x+28) = (x+2)(x-4)(x-7)$.
Partial fractions: $\frac{7x^2+7x-176}{(x+2)(x-4)(x-7)} = \frac{A}{x+2} + \frac{B}{x-4} + \frac{C}{x-7}$.
$A(x-4)(x-7) + B(x+2)(x-7) + C(x+2)(x-4) = 7x^2+7x-176$.
$x=-2: 54A = -162 \implies A=-3$.
$x=4: -18B = -36 \implies B=2$.
$x=7: 27C = 216 \implies C=8$.
$$ -3\ln|x+2| + 2\ln|x-4| + 8\ln|x-7| $$

**76)** $\int \frac{x^3-4x^2+1}{(x-2)^4} dx$
**Solution:**
Let $u=x-2 \implies x=u+2$.
Numerator: $(u+2)^3 - 4(u+2)^2 + 1 = (u^3+6u^2+12u+8) - 4(u^2+4u+4) + 1 = u^3+2u^2-4u-7$.
$$ \int \frac{u^3+2u^2-4u-7}{u^4} du = \int (u^{-1} + 2u^{-2} - 4u^{-3} - 7u^{-4}) du $$
$$ = \ln|u| - \frac{2}{u} + \frac{2}{u^2} + \frac{7}{3u^3} = \ln|x-2| - \frac{2}{x-2} + \frac{2}{(x-2)^2} + \frac{7}{3(x-2)^3} $$

**77)** $\int \frac{3x^2-5x+2}{x^3-2x^2+3x-6} dx$
**Solution:**
Denom: $x^2(x-2)+3(x-2) = (x-2)(x^2+3)$.
$\frac{3x^2-5x+2}{(x-2)(x^2+3)} = \frac{A}{x-2} + \frac{Bx+C}{x^2+3}$.
$A(x^2+3) + (Bx+C)(x-2) = 3x^2-5x+2$.
$x=2: 7A = 4 \implies A=4/7$.
Coeff $x^2$: $A+B=3 \implies B=17/7$.
Const: $3A-2C=2 \implies 12/7 - 2 = 2C \implies C=-1/7$.
$$ \int (\frac{4/7}{x-2} + \frac{17x-1}{7(x^2+3)}) dx = \frac{4}{7}\ln|x-2| + \frac{17}{14}\ln(x^2+3) - \frac{1}{7\sqrt{3}}\operatorname{arctg}\frac{x}{\sqrt{3}} $$

**78)** $\int \frac{2x+1}{(x^2+1)^2} dx$
**Solution:**
Split: $\int \frac{2x}{(x^2+1)^2} dx + \int \frac{dx}{(x^2+1)^2}$.
1st: $u=x^2+1 \implies du=2x dx$. $\int u^{-2} du = -u^{-1} = -\frac{1}{x^2+1}$.
2nd: Reduction formula or trig sub $x=\operatorname{tg} t$.
$\int \frac{dx}{(x^2+1)^2} = \frac{x}{2(x^2+1)} + \frac{1}{2}\operatorname{arctg} x$.
Total: $-\frac{1}{x^2+1} + \frac{x}{2(x^2+1)} + \frac{1}{2}\operatorname{arctg} x$.

**79)** $\int \frac{x^3+2x-6}{x^2-x-2} dx$
**Solution:**
Divide: $x^3+2x-6 = x(x^2-x-2) + x^2 + 2x + 2x - 6 = x(x^2-x-2) + x^2 + 4x - 6$
$= x(denom) + (x^2-x-2) + x + 2 + 4x - 6 + 2$ wait.
$x^3 \div (x^2-x-2) = x$. Remainder $x^2+2x$.
$(x^2+2x+2x-6) \div (denom) = 1$. Rem $5x-4$?
Actually: $x^3+2x-6 = (x+1)(x^2-x-2) + 5x-4$.
$\int (x+1) dx + \int \frac{5x-4}{(x-2)(x+1)} dx$.
Partial fractions: $\frac{5x-4}{(x-2)(x+1)} = \frac{A}{x-2} + \frac{B}{x+1}$.
$A(x+1)+B(x-2)=5x-4$.
$x=2 \implies 3A=6 \implies A=2$.
$x=-1 \implies -3B=-9 \implies B=3$.
$\int \frac{2}{x-2} + \frac{3}{x+1}$.
Total: $\frac{x^2}{2} + x + 2\ln|x-2| + 3\ln|x+1|$.
(Note: $2\ln|x-2| + 3\ln|x+1| = \ln|x-2|^2|x+1|^3$).

**80)** $\int \frac{2x^3-19x^2+58x-42}{x^2-8x+16} dx$
**Solution:**
Denom is $(x-4)^2$. Let $u=x-4 \implies x=u+4$.
Num: $2(u+4)^3 - 19(u+4)^2 + 58(u+4) - 42 = 2u^3 + 5u^2 + 2u + 14$.
$$ \int \frac{2u^3+5u^2+2u+14}{u^2} du = \int (2u+5+\frac{2}{u}+14u^{-2}) du $$
$$ = u^2 + 5u + 2\ln|u| - \frac{14}{u} = (x-4)^2 + 5(x-4) + 2\ln|x-4| - \frac{14}{x-4} $$

**81)** $\int \frac{x^4}{x^2+1} dx$
**Solution:**
$x^4 = x^4-1+1 = (x^2-1)(x^2+1)+1$.
$$ \int (x^2-1+\frac{1}{x^2+1}) dx = \frac{x^3}{3} - x + \operatorname{arctg} x $$

**82)** $\int \frac{72x^6}{3x^2+2} dx$
**Solution:**
Polynomial division: $72x^6 \div (3x^2+2) = 24x^4 - 16x^2 + \frac{32}{3}$, Remainder $-64/3$.
$$ \int (24x^4 - 16x^2 + \frac{32}{3}) dx - \frac{64}{3} \int \frac{dx}{3x^2+2} $$
$$ = \frac{24}{5}x^5 - \frac{16}{3}x^3 + \frac{32}{3}x - \frac{64}{3} \frac{1}{\sqrt{3}\sqrt{2}} \operatorname{arctg}(\frac{x\sqrt{3}}{\sqrt{2}}) $$
$$ = \frac{24}{5}x^5 - \frac{16}{3}x^3 + \frac{32}{3}x - \frac{32\sqrt{6}}{9} \operatorname{arctg}(\frac{x\sqrt{6}}{2}) $$

**83)** $\int \frac{2x^4-10x^3+21x^2-20x+5}{x^2-3x+2} dx$
**Solution:**
Division: $(2x^4-10x^3+21x^2-20x+5) \div (x^2-3x+2) = 2x^2-4x+5$, Rem $3x-5$.
$\int (2x^2-4x+5) dx + \int \frac{3x-5}{(x-1)(x-2)} dx$.
$$ \frac{2}{3}x^3 - 2x^2 + 5x + \int (\frac{2}{x-1} + \frac{1}{x-2}) dx = \frac{2}{3}x^3 - 2x^2 + 5x + 2\ln|x-1| + \ln|x-2| $$

**84)** $\int \sqrt{2x+1} dx$
**Solution:**
$$ \frac{1}{3}(2x+1)^{3/2} $$

**85)** $\int \frac{dx}{\sqrt{3+4x}}$
**Solution:**
Let $u=3+4x \implies du=4dx$.
$$ \frac{1}{4} \int u^{-1/2} du = \frac{1}{4} \cdot 2\sqrt{u} = \frac{1}{2}\sqrt{3+4x} $$

**86)** $\int \frac{dx}{\sqrt[3]{3x-4}}$
**Solution:**
Let $u=3x-4 \implies du=3dx$.
$$ \int \frac{1/3 du}{u^{1/3}} = \frac{1}{3} \cdot \frac{3}{2} u^{2/3} = \frac{1}{2}(3x-4)^{2/3} $$

**87)** $\int \frac{dx}{\sqrt[5]{(2x+1)^3}}$
**Solution:**
Let $u=2x+1 \implies du=2dx$.
$$ \frac{1}{2} \int u^{-3/5} du = \frac{1}{2} \cdot \frac{5}{2} u^{2/5} = \frac{5}{4}(2x+1)^{2/5} $$

**88)** $\int x \sqrt[3]{x-4} dx$
**Solution:**
$$ \frac{3}{7}(x-4)^{7/3} + 3(x-4)^{4/3} $$

**89)** $\int x \sqrt[3]{3x-1} dx$
**Solution:**
Let $u=3x-1 \implies x=\frac{u+1}{3}, dx=\frac{1}{3}du$.
$$ \int \frac{u+1}{3} u^{1/3} \frac{1}{3} du = \frac{1}{9} \int (u^{4/3} + u^{1/3}) du = \frac{1}{9} (\frac{3}{7}u^{7/3} + \frac{3}{4}u^{4/3}) $$
$$ = \frac{1}{21}(3x-1)^{7/3} + \frac{1}{12}(3x-1)^{4/3} $$

**90)** $\int x \sqrt{2+3x} dx$
**Solution:**
Let $u=2+3x \implies x=\frac{u-2}{3}$.
$$ \frac{1}{9} \int (u-2)u^{1/2} du = \frac{1}{9} (\frac{2}{5}u^{5/2} - \frac{4}{3}u^{3/2}) = \frac{2}{45}(2+3x)^{5/2} - \frac{4}{27}(2+3x)^{3/2} $$

**91)** $\int x \sqrt{1-5x} dx$
**Solution:**
Let $u=1-5x \implies x=\frac{1-u}{5}, dx=-\frac{1}{5}du$.
$$ -\frac{1}{25} \int (1-u)u^{1/2} du = -\frac{1}{25}(\frac{2}{3}u^{3/2} - \frac{2}{5}u^{5/2}) = \frac{2}{125}(1-5x)^{5/2} - \frac{2}{75}(1-5x)^{3/2} $$

**92)** $\int x \sqrt[3]{x-4} dx$
**Solution:**
Same technique as 88, 89. Let $u=x-4 \implies x=u+4$.
$$ \int (u+4)u^{1/3} du = \frac{3}{7}u^{7/3} + 3u^{4/3} = \frac{3}{7}(x-4)^{7/3} + 3(x-4)^{4/3} $$

**93)** $\int \frac{x dx}{\sqrt[4]{2x+3}}$
**Solution:**
Let $u=2x+3 \implies x=\frac{u-3}{2}, dx=\frac{1}{2}du$.
$$ \frac{1}{4} \int (u-3)u^{-1/4} du = \frac{1}{4} (\frac{4}{7}u^{7/4} - 4u^{3/4}) = \frac{1}{7}(2x+3)^{7/4} - (2x+3)^{3/4} $$

**94)** $\int \frac{x^2 dx}{\sqrt[3]{x+2}}$
**Solution:**
Let $u=x+2 \implies x=u-2$.
$$ \int (u-2)^2 u^{-1/3} du = \int (u^{5/3} - 4u^{2/3} + 4u^{-1/3}) du $$
$$ = \frac{3}{8}(x+2)^{8/3} - \frac{12}{5}(x+2)^{5/3} + 6(x+2)^{2/3} $$

**95)** $\int \frac{x^2+1}{\sqrt{3x+1}} dx$
**Solution:**
$u=3x+1 \implies x=\frac{u-1}{3}$.
$$ \frac{1}{3} \int (\frac{(u-1)^2}{9}+1) u^{-1/2} du = \frac{1}{27} \int (u^2-2u+10)u^{-1/2} du $$
$$ = \frac{1}{27} (\frac{2}{5}u^{5/2} - \frac{4}{3}u^{3/2} + 20u^{1/2}) \quad \text{where } u=3x+1 $$

**96)** $\int x^2 \sqrt[4]{2x+3} dx$
**Solution:**
$u=2x+3$. $x=\frac{u-3}{2}$.
$$ \frac{1}{8} \int (u-3)^2 u^{1/4} du = \frac{1}{8} \int (u^{9/4} - 6u^{5/4} + 9u^{1/4}) du $$
$$ = \frac{1}{8} (\frac{4}{13}u^{13/4} - \frac{24}{9}u^{9/4} + \frac{36}{5}u^{5/4}) \quad \text{where } u=2x+3 $$

**97)** $\int \frac{dx}{x\sqrt{x+a}}$
**Solution:**
$u = \sqrt{x+a} \implies x=u^2-a, dx=2u du$.
$$ \int \frac{2u du}{(u^2-a)u} = 2 \int \frac{du}{u^2-a} $$
Case $a>0$: $\frac{1}{\sqrt{a}} \ln|\frac{\sqrt{x+a}-\sqrt{a}}{\sqrt{x+a}+\sqrt{a}}|$.
Case $a<0$ (let $a=-b^2$): $\frac{2}{b} \operatorname{arctg}\frac{\sqrt{x-b^2}}{b}$.

**98)** $\int \frac{dx}{x\sqrt{x-a}}$
**Solution:**
$u=\sqrt{x-a} \implies x=u^2+a$.
$$ \int \frac{2u du}{(u^2+a)u} = 2 \int \frac{du}{u^2+a} = \frac{2}{\sqrt{a}} \operatorname{arctg}\frac{\sqrt{x-a}}{\sqrt{a}} \quad (\text{if } a>0) $$

**99)** $\int \frac{\sqrt{x}}{x-1} dx$
**Solution:**
$t=\sqrt{x} \implies x=t^2, dx=2t dt$.
$$ \int \frac{t \cdot 2t}{t^2-1} dt = 2 \int (1+\frac{1}{t^2-1}) dt = 2t + \ln|\frac{t-1}{t+1}| = 2\sqrt{x} + \ln|\frac{\sqrt{x}-1}{\sqrt{x}+1}| $$

**100)** $\int \frac{\sqrt{x+1}}{x} dx$
**Solution:**
$t=\sqrt{x+1} \implies x=t^2-1, dx=2t dt$.
$$ \int \frac{t \cdot 2t}{t^2-1} dt = 2\sqrt{x+1} + \ln|\frac{\sqrt{x+1}-1}{\sqrt{x+1}+1}| $$

**101)** $\int \frac{1+\sqrt{x}}{1-\sqrt{x}} dx$
**Solution:**
$t=\sqrt{x} \implies dx=2t dt$.
$$ \int \frac{1+t}{1-t} 2t dt = \int \frac{-2t^2-2t}{t-1} dt = \int (-2t - 4 - \frac{6}{t-1}) dt $$
$$ = -t^2 - 4t - 6\ln|t-1| = -x - 4\sqrt{x} - 6\ln|\sqrt{x}-1| $$

**102)** $\int \frac{dx}{(x+1)\sqrt{1-x}}$
**Solution:**
$t=\sqrt{1-x} \implies x=1-t^2, dx=-2t dt$.
$$ \int \frac{-2t dt}{(2-t^2)t} = -2 \int \frac{dt}{2-t^2} = - \frac{1}{\sqrt{2}} \ln|\frac{\sqrt{2}+t}{\sqrt{2}-t}| = \frac{1}{\sqrt{2}} \ln|\frac{\sqrt{2}-\sqrt{1-x}}{\sqrt{2}+\sqrt{1-x}}| $$

**103)** $\int \sqrt{1+\sqrt{x}} dx$
**Solution:**
$t=\sqrt{1+\sqrt{x}} \implies \sqrt{x}=t^2-1 \implies x=(t^2-1)^2, dx=2(t^2-1)2t dt$.
$$ \int t \cdot 4t(t^2-1) dt = 4 \int (t^5-t^3) dt = 4(\frac{t^6}{6} - \frac{t^4}{4}) = \frac{2}{3}(1+\sqrt{x})^3 - (1+\sqrt{x})^2 $$

**104)** $\int \frac{\sqrt[3]{x} dx}{x+\sqrt[6]{x^5}}$
**Solution:**
$x=t^6 \implies dx=6t^5 dt$. $\sqrt[3]{x}=t^2, \sqrt[6]{x^5}=t^5$.
$$ \int \frac{t^2 \cdot 6t^5}{t^6+t^5} dt = 6 \int \frac{t^7}{t^5(t+1)} dt = 6 \int \frac{t^2}{t+1} dt $$
$$ 6 \int (t-1+\frac{1}{t+1}) dt = 6(\frac{t^2}{2}-t+\ln|t+1|) = 3\sqrt[3]{x} - 6\sqrt[6]{x} + 6\ln|\sqrt[6]{x}+1| $$

**105)** $\int \frac{dx}{x\sqrt{x+2}}$
**Solution:**
$t=\sqrt{x+2} \implies x=t^2-2, dx=2t dt$.
$$ \int \frac{2t dt}{(t^2-2)t} = 2 \int \frac{dt}{t^2-2} = \frac{1}{\sqrt{2}} \ln|\frac{t-\sqrt{2}}{t+\sqrt{2}}| = \frac{1}{\sqrt{2}} \ln|\frac{\sqrt{x+2}-\sqrt{2}}{\sqrt{x+2}+\sqrt{2}}| $$

**106)** $\int \cos 5x \cos 7x dx$
**Solution:**
Product to sum: $\cos A \cos B = \frac{1}{2}[\cos(A-B) + \cos(A+B)]$.
$\cos 5x \cos 7x = \frac{1}{2}(\cos(-2x) + \cos 12x) = \frac{1}{2}(\cos 2x + \cos 12x)$.
$$ \frac{1}{2} \int (\cos 2x + \cos 12x) dx = \frac{1}{2}(\frac{\sin 2x}{2} + \frac{\sin 12x}{12}) = \frac{\sin 2x}{4} + \frac{\sin 12x}{24} $$

**107)** $\int \sin 3x \cos 2x dx$
**Solution:**
$\sin A \cos B = \frac{1}{2}[\sin(A-B) + \sin(A+B)]$.
$\sin 3x \cos 2x = \frac{1}{2}(\sin x + \sin 5x)$.
$$ \frac{1}{2} \int (\sin x + \sin 5x) dx = \frac{1}{2}(-\cos x - \frac{1}{5}\cos 5x) = -\frac{\cos x}{2} - \frac{\cos 5x}{10} $$

**108)** $\int \cos 2x \cos 3x dx$
**Solution:**
Same as 106. $\cos 2x \cos 3x = \frac{1}{2}(\cos x + \cos 5x)$.
$$ \frac{1}{2} \int (\cos x + \cos 5x) dx = \frac{1}{2}(\sin x + \frac{1}{5}\sin 5x) = \frac{\sin x}{2} + \frac{\sin 5x}{10} $$

**109)** $\int \sin x \cos 3x dx$
**Solution:**
$\sin x \cos 3x = \frac{1}{2}(\sin(-2x) + \sin 4x) = \frac{1}{2}(-\sin 2x + \sin 4x)$.
$$ \frac{1}{2} \int (-\sin 2x + \sin 4x) dx = \frac{1}{2}(\frac{1}{2}\cos 2x - \frac{1}{4}\cos 4x) = \frac{\cos 2x}{4} - \frac{\cos 4x}{8} $$

**110)** $\int \cos 2x \sin 4x dx$
**Solution:**
$\sin 4x \cos 2x = \frac{1}{2}(\sin 2x + \sin 6x)$.
$$ \frac{1}{2} \int (\sin 2x + \sin 6x) dx = -\frac{\cos 2x}{4} - \frac{\cos 6x}{12} $$

**111)** $\int \sin 2x \sin 5x dx$
**Solution:**
$\sin A \sin B = \frac{1}{2}[\cos(A-B) - \cos(A+B)]$.
$\sin 2x \sin 5x = \frac{1}{2}(\cos(-3x) - \cos 7x) = \frac{1}{2}(\cos 3x - \cos 7x)$.
$$ \frac{1}{2} \int (\cos 3x - \cos 7x) dx = \frac{1}{2}(\frac{\sin 3x}{3} - \frac{\sin 7x}{7}) = \frac{\sin 3x}{6} - \frac{\sin 7x}{14} $$

**112)** $\int \cos x \cos 3x dx$
**Solution:**
$\frac{1}{2}(\cos 2x + \cos 4x)$.
$$ \frac{1}{2}(\frac{\sin 2x}{2} + \frac{\sin 4x}{4}) = \frac{\sin 2x}{4} + \frac{\sin 4x}{8} $$

**113)** $\int \sin 3x \sin x dx$
**Solution:**
$\frac{1}{2}(\cos 2x - \cos 4x)$.
$$ \frac{1}{2}(\frac{\sin 2x}{2} - \frac{\sin 4x}{4}) = \frac{\sin 2x}{4} - \frac{\sin 4x}{8} $$

**114)** $\int \sin 5x \sin 2x dx$
**Solution:**
See 111 (identities are commutative).
$$ \frac{\sin 3x}{6} - \frac{\sin 7x}{14} $$

**115)** $\int \sin^3 x dx$
**Solution:**
$\sin^3 x = \sin x (1-\cos^2 x)$. Let $u=\cos x, du=-\sin x dx$.
$$ \int -(1-u^2) du = -u + \frac{u^3}{3} = -\cos x + \frac{1}{3}\cos^3 x $$

**116)** $\int \sin^4 x dx$
**Solution:**
$\sin^4 x = (\frac{1-\cos 2x}{2})^2 = \frac{1}{4}(1 - 2\cos 2x + \cos^2 2x)$.
$\cos^2 2x = \frac{1+\cos 4x}{2}$.
$\int \frac{1}{4}(1 - 2\cos 2x + \frac{1}{2} + \frac{1}{2}\cos 4x) dx = \int (\frac{3}{8} - \frac{1}{2}\cos 2x + \frac{1}{8}\cos 4x) dx$.
$$ \frac{3}{8}x - \frac{1}{4}\sin 2x + \frac{1}{32}\sin 4x $$

**117)** $\int \cos^4 x dx$
**Solution:**
$(\frac{1+\cos 2x}{2})^2 = \frac{1}{4}(1 + 2\cos 2x + \cos^2 2x)$.
$\cos^2 2x = \frac{1+\cos 4x}{2}$.
$$ \int (\frac{3}{8} + \frac{1}{2}\cos 2x + \frac{1}{8}\cos 4x) dx = \frac{3}{8}x + \frac{1}{4}\sin 2x + \frac{1}{32}\sin 4x $$

**118)** $\int \cos^5 x dx$
**Solution:**
$\cos^4 x \cos x = (1-\sin^2 x)^2 \cos x$. $u=\sin x$.
$\int (1-u^2)^2 du = \int (1-2u^2+u^4) du = u - \frac{2}{3}u^3 + \frac{1}{5}u^5$.
$$ \sin x - \frac{2}{3}\sin^3 x + \frac{1}{5}\sin^5 x $$

**119)** $\int \sin^5 x dx$
**Solution:**
$\sin^4 x \sin x = (1-\cos^2 x)^2 \sin x$. $u=\cos x$.
$\int -(1-u^2)^2 du = -u + \frac{2}{3}u^3 - \frac{1}{5}u^5$.
$$ -\cos x + \frac{2}{3}\cos^3 x - \frac{1}{5}\cos^5 x $$

**120)** $\int \operatorname{tg}^5 x dx$
**Solution:**
$\int \operatorname{tg}^3 x (\sec^2 x - 1) dx = \int \operatorname{tg}^3 x \sec^2 x dx - \int \operatorname{tg}^3 x dx$.
1st: $\frac{1}{4}\operatorname{tg}^4 x$.
2nd: $\int \operatorname{tg} x (\sec^2 x - 1) dx = \frac{1}{2}\operatorname{tg}^2 x - \int \operatorname{tg} x dx = \frac{1}{2}\operatorname{tg}^2 x + \ln|\cos x|$.
Total: $\frac{1}{4}\operatorname{tg}^4 x - \frac{1}{2}\operatorname{tg}^2 x - \ln|\cos x|$.

**121)** $\int \operatorname{ctg}^4 x dx$
**Solution:**
$\int \operatorname{ctg}^2 x (\csc^2 x - 1) dx = \int \operatorname{ctg}^2 x \csc^2 x dx - \int \operatorname{ctg}^2 x dx$.
1st: $-\frac{1}{3}\operatorname{ctg}^3 x$.
2nd: $\int (\csc^2 x - 1) dx = -\operatorname{ctg} x - x$.
Total: $-\frac{1}{3}\operatorname{ctg}^3 x + \operatorname{ctg} x + x$.

**122)** $\int \operatorname{ctg}^6 x dx$
**Solution:**
$\int \operatorname{ctg}^4 x (\csc^2 x - 1) dx = -\frac{1}{5}\operatorname{ctg}^5 x - \int \operatorname{ctg}^4 x dx$.
From 121: $\int \operatorname{ctg}^4 x dx = -\frac{1}{3}\operatorname{ctg}^3 x + \operatorname{ctg} x + x$.
Total: $-\frac{1}{5}\operatorname{ctg}^5 x + \frac{1}{3}\operatorname{ctg}^3 x - \operatorname{ctg} x - x$.

**123)** $\int \sin^3 x \cos^4 x dx$
**Solution:**
$\sin x(1-\cos^2 x)\cos^4 x$. $u=\cos x$.
$\int -(1-u^2)u^4 du = \int (u^6 - u^4) du = \frac{1}{7}u^7 - \frac{1}{5}u^5$.
$$ \frac{1}{7}\cos^7 x - \frac{1}{5}\cos^5 x $$

**124)** $\int \sin^7 x \cos^6 x dx$
**Solution:**
$\sin x(1-\cos^2 x)^3 \cos^6 x$. $u=\cos x$.
$\int -(1-u^2)^3 u^6 du = \int -(1-3u^2+3u^4-u^6)u^6 du$.
$\int (-u^6+3u^8-3u^{10}+u^{12}) du = -\frac{1}{7}u^7 + \frac{1}{3}u^9 - \frac{3}{11}u^{11} + \frac{1}{13}u^{13}$.
$$ -\frac{1}{7}\cos^7 x + \frac{1}{3}\cos^9 x - \frac{3}{11}\cos^{11} x + \frac{1}{13}\cos^{13} x $$

**125)** $\int \sin^4 x \cos^2 x dx$
**Solution:**
$\sin^4 x \cos^2 x = (\sin x \cos x)^2 \sin^2 x = \frac{1}{4}\sin^2 2x \frac{1-\cos 2x}{2} = \frac{1}{8}(\sin^2 2x - \sin^2 2x \cos 2x)$.
$\sin^2 2x = \frac{1-\cos 4x}{2}$.
$\int \frac{1}{8}(\frac{1}{2} - \frac{1}{2}\cos 4x - \sin^2 2x \cos 2x) dx$.
$$ \frac{1}{16}x - \frac{1}{32}\sin 4x - \frac{1}{48}\sin^3 2x $$

**126)** $\int \sin^2 x \cos^2 x dx$
**Solution:**
$\frac{1}{4}\sin^2 2x = \frac{1}{8}(1-\cos 4x)$.
$$ \frac{1}{8}x - \frac{1}{32}\sin 4x $$

**127)** $\int \sin^3 x \cos^3 x dx$
**Solution:**
$(\sin x \cos x)^3 \frac{\sin x \cos x}{\sin x \cos x}$? No.
Substitute $u=\sin x \implies \cos^3 x = (1-u^2)\cos x$.
$\int u^3 (1-u^2) du = \frac{1}{4}u^4 - \frac{1}{6}u^6 = \frac{1}{4}\sin^4 x - \frac{1}{6}\sin^6 x$.

**128)** $\int \sin^4 x \cos^5 x dx$
**Solution:**
$u=\sin x$. $\cos^4 x = (1-u^2)^2$.
$\int u^4 (1-2u^2+u^4) du = \frac{1}{5}u^5 - \frac{2}{7}u^7 + \frac{1}{9}u^9$.
$$ \frac{1}{5}\sin^5 x - \frac{2}{7}\sin^7 x + \frac{1}{9}\sin^9 x $$

**129)** $\int \frac{\cos x}{\sin^8 x} dx$
**Solution:**
$u=\sin x, du=\cos x dx$.
$\int u^{-8} du = -\frac{1}{7}u^{-7} = -\frac{1}{7\sin^7 x}$.

**130)** $\int \sin x \operatorname{tg} x dx$
**Solution:**
$\int \frac{\sin^2 x}{\cos x} dx = \int \frac{1-\cos^2 x}{\cos x} dx = \int (\sec x - \cos x) dx$.
$$ \ln|\sec x + \operatorname{tg} x| - \sin x = \ln|\frac{1+\sin x}{\cos x}| - \sin x $$

**131)** $\int \frac{\cos x}{\sqrt[3]{\sin^2 x}} dx$
**Solution:**
$u=\sin x, du=\cos x dx$.
$\int u^{-2/3} du = 3u^{1/3} = 3\sqrt[3]{\sin x}$.

**132)** $\int \frac{\sin x}{\sqrt[3]{1+2\cos x}} dx$
**Solution:**
$u=1+2\cos x \implies du=-2\sin x dx$.
$-\frac{1}{2} \int u^{-1/3} du = -\frac{1}{2} \cdot \frac{3}{2} u^{2/3} = -\frac{3}{4}(1+2\cos x)^{2/3}$.

**133)** $\int \frac{\sin 2x}{\sqrt{1+\cos^2 x}} dx$
**Solution:**
$\sin 2x = 2\sin x \cos x$.
Let $u=1+\cos^2 x \implies du = 2\cos x (-\sin x) dx = -\sin 2x dx$.
$$ \int \frac{-du}{\sqrt{u}} = -2\sqrt{u} = -2\sqrt{1+\cos^2 x} $$

**134)** $\int \frac{\sin 2x}{1+\sin^2 x} dx$
**Solution:**
$u=1+\sin^2 x \implies du = 2\sin x \cos x dx = \sin 2x dx$.
$$ \int \frac{du}{u} = \ln|u| = \ln(1+\sin^2 x) $$

**135)** $\int \frac{\sin 2x}{\sqrt{1-\sin^4 x}} dx$
**Solution:**
Let $u=\sin^2 x \implies du=\sin 2x dx$.
$\int \frac{du}{\sqrt{1-u^2}} = \arcsin u = \arcsin(\sin^2 x)$.

**136)** $\int \frac{dx}{e^{2x}-1}$
**Solution:**
Let $u=e^{2x}-1 \implies du=2e^{2x}dx = 2(u+1)dx \implies dx=\frac{du}{2(u+1)}$.
$$ \int \frac{du}{u \cdot 2(u+1)} = \frac{1}{2} \int (\frac{1}{u} - \frac{1}{u+1}) du = \frac{1}{2}(\ln|u| - \ln|u+1|) $$
$$ = \frac{1}{2}\ln|\frac{e^{2x}-1}{e^{2x}}| = \frac{1}{2}\ln|e^{2x}-1| - x $$

**137)** $\int \frac{dx}{e^x+e^{-x}}$
**Solution:**
Multiply by $e^x/e^x$: $\int \frac{e^x}{e^{2x}+1} dx$. Let $t=e^x, dt=e^x dx$.
$$ \int \frac{dt}{t^2+1} = \operatorname{arctg} t = \operatorname{arctg}(e^x) $$

**138)** $\int \sqrt{e^x+1} dx$
**Solution:**
Let $t=\sqrt{e^x+1} \implies t^2=e^x+1 \implies e^x=t^2-1$.
$2t dt = e^x dx \implies dx = \frac{2t dt}{t^2-1}$.
$$ \int t \frac{2t}{t^2-1} dt = 2 \int (1 + \frac{1}{t^2-1}) dt = 2t + \ln|\frac{t-1}{t+1}| $$
$$ = 2\sqrt{e^x+1} + \ln|\frac{\sqrt{e^x+1}-1}{\sqrt{e^x+1}+1}| $$

**139)** $\int \frac{e^x-1}{e^x+1} dx$
**Solution:**
$\frac{e^x-1}{e^x+1} = \frac{e^x+1-2}{e^x+1} = 1 - \frac{2}{e^x+1}$.
$\int (1 - \frac{2e^{-x}}{1+e^{-x}}) dx = x - 2 \int \frac{e^{-x}}{1+e^{-x}} dx$.
$$ x + 2\ln(1+e^{-x}) $$

**140)** $\int \frac{dx}{\sqrt{3+2e^x}}$
**Solution:**
$t=\sqrt{3+2e^x} \implies t^2=3+2e^x \implies e^x=(t^2-3)/2$.
$2t dt = 2e^x dx \implies dx = \frac{t dt}{e^x} = \frac{t dt}{(t^2-3)/2} = \frac{2t}{t^2-3} dt$.
$$ \int \frac{1}{t} \frac{2t}{t^2-3} dt = 2 \int \frac{dt}{t^2-3} = 2 \cdot \frac{1}{2\sqrt{3}} \ln|\frac{t-\sqrt{3}}{t+\sqrt{3}}| $$
$$ = \frac{1}{\sqrt{3}} \ln|\frac{\sqrt{3+2e^x}-\sqrt{3}}{\sqrt{3+2e^x}+\sqrt{3}}| $$

**141)** $\int e^x \sqrt{1+e^x} dx$
**Solution:**
$u=1+e^x \implies du=e^x dx$.
$$ \int \sqrt{u} du = \frac{2}{3}u^{3/2} = \frac{2}{3}(1+e^x)^{3/2} $$

**142)** $\int \frac{e^x}{(e^x-1)^2} dx$
**Solution:**
$u=e^x-1 \implies du=e^x dx$.
$$ \int \frac{du}{u^2} = -\frac{1}{u} = -\frac{1}{e^x-1} $$

**143)** $\int (e^x+e^{-x})^2 dx$
**Solution:**
$(e^x+e^{-x})^2 = e^{2x} + 2 + e^{-2x}$.
$$ \int (e^{2x} + 2 + e^{-2x}) dx = \frac{1}{2}e^{2x} + 2x - \frac{1}{2}e^{-2x} $$

**144)** $\int \frac{e^x}{e^{2x}+5} dx$
**Solution:**
$t=e^x, dt=e^x dx$.
$$ \int \frac{dt}{t^2+5} = \frac{1}{\sqrt{5}} \operatorname{arctg}\frac{t}{\sqrt{5}} = \frac{1}{\sqrt{5}} \operatorname{arctg}\frac{e^x}{\sqrt{5}} $$

**145)** $\int \frac{4e^x+6e^{-x}}{9e^x-4e^{-x}} dx$
**Solution:**
Multiply by $e^x/e^x$: $\int \frac{4e^{2x}+6}{9e^{2x}-4} dx$. Let $t=e^{2x}, dt=2e^{2x}dx$.
Or separate: denom derivative is $9e^x+4e^{-x}$. Not obvious.
Use coefficients $4e^x+6e^{-x} = A(9e^x-4e^{-x}) + B(9e^x+4e^{-x})$.
$4 = 9A+9B \implies 36A+36B=16$.
$6 = -4A+4B \implies -36A+36B=54$.
$72B=70 \implies B=35/36$.
$9A = 4-9(35/36) = 4 - 35/4 = -19/4 \implies A=-19/36$.
$$ \int (-\frac{19}{36} + \frac{35}{36} \frac{D'}{D}) dx = -\frac{19}{36}x + \frac{35}{36}\ln|9e^x-4e^{-x}| $$

**146)** $\int \frac{dx}{e^x+e^{2x}}$
**Solution:**
$t=e^x \implies dx=dt/t$.
$$ \int \frac{dt/t}{t+t^2} = \int \frac{dt}{t^2(1+t)} = \int (\frac{1}{t^2} - \frac{1}{t} + \frac{1}{1+t}) dt $$
Check: $\frac{1+t-t(1+t)+t^2}{t^2(1+t)} = \frac{1}{t^2(1+t)}$. Correct.
$$ -\frac{1}{t} - \ln|t| + \ln|1+t| = -e^{-x} - x + \ln(1+e^x) $$

**147)** $\int \frac{e^x}{(e^x+a)^2} dx$
**Solution:**
$u=e^x+a \implies du=e^x dx$.
$$ \int \frac{du}{u^2} = -\frac{1}{u} = -\frac{1}{e^x+a} $$

**148)** $\int \frac{e^x dx}{\sqrt{3-5e^{2x}}}$
**Solution:**
$u=e^x \sqrt{5}$.
$$ \int \frac{du/\sqrt{5}}{\sqrt{3-u^2}} = \frac{1}{\sqrt{5}} \arcsin(\frac{u}{\sqrt{3}}) = \frac{1}{\sqrt{5}} \arcsin(\frac{\sqrt{5}e^x}{\sqrt{3}}) $$

**149)** $\int \frac{dx}{\sqrt{e^{2x}+4e^x+1}}$
**Solution:**
$t=e^x$.
$\int \frac{dt}{t\sqrt{t^2+4t+1}}$. Let $u=1/t$. Or use substitution.
If $u=1/t$, $dt=-du/u^2$. $t^2+4t+1 = \frac{1}{u^2} + \frac{4}{u} + 1 = \frac{1+4u+u^2}{u^2}$.
$\int \frac{-du/u^2}{(1/u) \frac{\sqrt{1+4u+u^2}}{u}} = -\int \frac{du}{\sqrt{u^2+4u+1}}$.
$-\ln|u+2+\sqrt{u^2+4u+1}| = -\ln|\frac{1}{e^x}+2+\sqrt{\frac{1}{e^{2x}}+\frac{4}{e^x}+1}|$.
Simpler: $-\ln|\frac{1+2e^x+\sqrt{1+4e^x+e^{2x}}}{e^x}| = x - \ln(1+2e^x+\sqrt{1+4e^x+e^{2x}})$.

**150)** $\int x^3 e^{-x} dx$
**Solution:**
Tabular parts:
$x^3 \to 3x^2 \to 6x \to 6 \to 0$.
$e^{-x} \to -e^{-x} \to e^{-x} \to -e^{-x} \to e^{-x}$.
$$ -x^3 e^{-x} - 3x^2 e^{-x} - 6x e^{-x} - 6e^{-x} = -e^{-x}(x^3+3x^2+6x+6) $$

**151)** $\int \frac{dx}{x \ln x}$
**Solution:**
$$ \ln|\ln x| $$

**152)** $\int \ln(x^2+1) dx$
**Solution:**
Parts: $u=\ln(x^2+1), dv=dx \implies du=\frac{2x}{x^2+1}dx, v=x$.
$x\ln(x^2+1) - \int \frac{2x^2}{x^2+1} dx = x\ln(x^2+1) - 2 \int (1-\frac{1}{x^2+1}) dx$.
$$ x\ln(x^2+1) - 2x + 2\operatorname{arctg} x $$

**153)** $\int (\ln|x|)^2 dx$
**Solution:**
Parts: $u=(\ln x)^2, dv=dx$.
$$ x(\ln x)^2 - 2 \int \ln x dx = x(\ln x)^2 - 2(x\ln x - x) = x(\ln x)^2 - 2x\ln x + 2x $$

**154)** $\int \ln(x+\sqrt{x^2+1}) dx$
**Solution:**
Parts: $u=\ln(x+\sqrt{x^2+1})$, $dv=dx$.
$du = \frac{1}{x+\sqrt{x^2+1}}(1+\frac{x}{\sqrt{x^2+1}}) dx = \frac{1}{\sqrt{x^2+1}} dx$.
$$ x\ln(x+\sqrt{x^2+1}) - \int \frac{x}{\sqrt{x^2+1}} dx = x\ln(x+\sqrt{x^2+1}) - \sqrt{x^2+1} $$

**155)** $\int \ln|2-5x| dx$
**Solution:**
$u=\ln|2-5x|, dv=dx$.
$x\ln|2-5x| - \int \frac{-5x}{2-5x} dx = x\ln|2-5x| - \int (1 - \frac{2}{2-5x}) dx$.
$= x\ln|2-5x| - x + 2(-\frac{1}{5}\ln|2-5x|)$ ... wait.
Alternative: Let $t=2-5x, dt=-5dx$.
$-\frac{1}{5} \int \ln|t| dt = -\frac{1}{5}(t\ln|t|-t) = -\frac{1}{5}((2-5x)\ln|2-5x| - (2-5x))$.
$$ (x-2/5)\ln|2-5x| - x $$

**156)** $\int \frac{dx}{x(1+\ln^2|x|)}$
**Solution:**
$u=\ln x, du=dx/x$.
$$ \int \frac{du}{1+u^2} = \operatorname{arctg}(\ln|x|) $$

**157)** $\int x^2 \ln|x| dx$
**Solution:**
Parts: $u=\ln x, dv=x^2 dx$.
$$ \frac{x^3}{3}\ln x - \int \frac{x^3}{3}\frac{1}{x} dx = \frac{x^3}{3}\ln x - \frac{1}{9}x^3 $$

**158)** $\int (4+3x^2)\ln|x| dx$
**Solution:**
Parts: $u=\ln x, dv=(4+3x^2)dx \implies v=4x+x^3$.
$(4x+x^3)\ln x - \int (4x+x^3)\frac{1}{x} dx = (4x+x^3)\ln x - \int (4+x^2) dx$.
$$ (4x+x^3)\ln|x| - 4x - \frac{x^3}{3} $$

**159)** $\int x^3 \ln(x^2+3) dx$
**Solution:**
Let $t=x^2+3 \implies x^2=t-3, 2x dx=dt$.
$\int \frac{t-3}{2} \ln t dt = \frac{1}{2} \int (t\ln t - 3\ln t) dt$.
$\int t\ln t = \frac{t^2}{2}\ln t - \frac{t^2}{4}$. $\int \ln t = t\ln t - t$.
$\frac{1}{2}(\frac{t^2}{2}\ln t - \frac{t^2}{4} - 3t\ln t + 3t) = \frac{1}{4}(x^2+3)^2\ln(x^2+3) - \frac{1}{8}(x^2+3)^2 - \frac{3}{2}(x^2+3)\ln(x^2+3) + \frac{3}{2}(x^2+3)$.

**160)** $\int x a^x dx$
**Solution:**
$$ \frac{a^x}{\ln a}(x - \frac{1}{\ln a}) $$
