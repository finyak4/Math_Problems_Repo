## Sequence Limits - Solutions

### Ex 1.

**Problem 1)**
$$
u_n = \frac{n}{n+1}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n}{n+1} = \lim_{n \to \infty} \frac{1}{1+1/n} = 1
$$

**Problem 2)**
$$
u_n = \frac{4n-3}{6-5n}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{4n-3}{6-5n} = \lim_{n \to \infty} \frac{4-3/n}{6/n-5} = -\frac{4}{5}
$$

**Problem 3)**
$$
u_n = \frac{n^2-1}{3-n^3}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n^2-1}{3-n^3} = \lim_{n \to \infty} \frac{1/n - 1/n^3}{3/n^3 - 1} = \frac{0}{-1} = 0
$$

**Problem 4)**
$$
u_n = \frac{2n^3-4n-1}{6n+3n^2-n^3}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{2n^3-4n-1}{-n^3+3n^2+6n} = \frac{2}{-1} = -2
$$

**Problem 5)**
$$
u_n = \frac{(n-1)(n+3)}{3n^2+5}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n^2+2n-3}{3n^2+5} = \frac{1}{3}
$$

**Problem 6)**
$$
u_n = \frac{(2n-1)^2}{(4n-1)(3n+2)}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{4n^2-4n+1}{12n^2+5n-2} = \frac{4}{12} = \frac{1}{3}
$$

**Problem 7)**
$$
u_n = \frac{(2n-1)^3}{(4n-1)^2(1-5n)}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{8n^3+\dots}{(16n^2+\dots)(1-5n)} = \lim_{n \to \infty} \frac{8n^3}{-80n^3} = -\frac{1}{10}
$$

**Problem 8)**
$$
u_n = \frac{3}{n} - \frac{10}{\sqrt{n}}
$$
**Solution:**
$$
\lim_{n \to \infty} \left(\frac{3}{n} - \frac{10}{\sqrt{n}}\right) = 0 - 0 = 0
$$

**Problem 9)**
$$
u_n = \frac{(-1)^n}{2n-1}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{(-1)^n}{2n-1} = 0 \quad (\text{Bounded} / \infty)
$$

**Problem 10)**
$$
u_n = \left(\frac{2n-3}{3n+1}\right)^2
$$
**Solution:**
$$
\left(\lim_{n \to \infty} \frac{2n-3}{3n+1}\right)^2 = \left(\frac{2}{3}\right)^2 = \frac{4}{9}
$$

**Problem 11)**
$$
u_n = \left(\frac{5n-2}{3n-1}\right)^3
$$
**Solution:**
$$
\left(\frac{5}{3}\right)^3 = \frac{125}{27}
$$

**Problem 12)**
$$
u_n = \frac{(\sqrt{n}+3)^2}{n+1}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n+6\sqrt{n}+9}{n+1} = 1
$$

**Problem 13)**
$$
u_n = \frac{\sqrt{n}-2}{3n+5}
$$
**Solution:**
Degree of numerator is $1/2$, denominator is $1$. Limit is $0$.

**Problem 14)**
$$
u_n = \frac{n-10}{3}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n}{3} = +\infty
$$

**Problem 15)**
$$
u_n = \frac{(-0,8)^n}{2n-5}
$$
**Solution:**
Numerator $(-0.8)^n \to 0$. Denominator $\to \infty$. Limit is $0$.

**Problem 16)**
$$
u_n = \frac{2-5n-10n^2}{3n+15}
$$
**Solution:**
Degree $2$ over $1$. Coeffs $-10/0$. Limit is $-\infty$.

**Problem 17)**
$$
u_n = \frac{2n+(-1)^n}{n}
$$
**Solution:**
$$
\lim_{n \to \infty} \left(2 + \frac{(-1)^n}{n}\right) = 2 + 0 = 2
$$

**Problem 18)**
$$
u_n = \frac{\sqrt{1+2n^2}-\sqrt{1+4n^2}}{n}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n\sqrt{2+1/n^2}-n\sqrt{4+1/n^2}}{n} = \sqrt{2} - \sqrt{4} = \sqrt{2} - 2
$$

**Problem 19)**
$$
u_n = \sqrt{\frac{3n-2}{n+10}}
$$
**Solution:**
$$
\sqrt{\lim \frac{3n-2}{n+10}} = \sqrt{3}
$$

**Problem 20)**
$$
u_n = \sqrt[3]{\frac{n-1}{8n+10}}
$$
**Solution:**
$$
\sqrt[3]{\frac{1}{8}} = \frac{1}{2}
$$

**Problem 21)**
$$
u_n = \frac{\sqrt{n^2+4}}{3n-2}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n\sqrt{1+4/n^2}}{n(3-2/n)} = \frac{1}{3}
$$

**Problem 22)**
$$
u_n = \frac{n}{\sqrt[3]{n^3+1}}
$$
**Solution:**
$$
\lim_{n \to \infty} \frac{n}{n\sqrt[3]{1+1/n^3}} = 1
$$

**Problem 23)**
$$
u_n = \frac{n}{\sqrt[3]{8n^3-n}-n}
$$
**Solution:**
Factor highest power in denominator: $n(\sqrt[3]{8} - 1) = n(2-1) = n$.
$$
\lim_{n \to \infty} \frac{n}{2n-n} = 1
$$

**Problem 24)**
$$
u_n = \frac{1}{\sqrt{4n^2+7n}-2n}
$$
**Solution:**
Multiply by conjugate $\sqrt{4n^2+7n}+2n$:
$$
\frac{\sqrt{4n^2+7n}+2n}{4n^2+7n-4n^2} = \frac{2n+2n}{7n} = \frac{4}{7}
$$

**Problem 25)**
$$
u_n = \sqrt{n+2}-\sqrt{n}
$$
**Solution:**
$$
\frac{n+2-n}{\sqrt{n+2}+\sqrt{n}} = \frac{2}{\infty} = 0
$$

**Problem 26)**
$$
u_n = \sqrt{n^2+n}-n
$$
**Solution:**
$$
\frac{n^2+n-n^2}{\sqrt{n^2+n}+n} = \frac{n}{n+n} = \frac{1}{2}
$$

**Problem 27)**
$$
u_n = n-\sqrt{n^2+5n}
$$
**Solution:**
$$
\frac{n^2-(n^2+5n)}{n+\sqrt{n^2+5n}} = \frac{-5n}{2n} = -\frac{5}{2}
$$

**Problem 28)**
$$
u_n = \sqrt{3n^2+2n-5}-n\sqrt{3}
$$
**Solution:**
$$
\frac{3n^2+2n-5-3n^2}{\sqrt{3n^2+\dots}+n\sqrt{3}} = \frac{2n}{n\sqrt{3}+n\sqrt{3}} = \frac{2}{2\sqrt{3}} = \frac{1}{\sqrt{3}} = \frac{\sqrt{3}}{3}
$$

**Problem 29)**
$$
u_n = 3n-\sqrt{9n^2+6n-15}
$$
**Solution:**
$$
\frac{9n^2-9n^2-6n+15}{3n+\sqrt{9n^2+\dots}} = \frac{-6n}{6n} = -1
$$

**Problem 30)**
$$
u_n = \sqrt[3]{n^3+4n^2}-n
$$
**Solution:**
Using $a^3-b^3$:
$$
\approx \frac{n^3+4n^2-n^3}{3n^2} = \frac{4n^2}{3n^2} = \frac{4}{3}
$$

**Problem 31)**
$$
u_n = \sqrt[3]{n^2(2-\sqrt[3]{2n^3+5n^2-7})}
$$
**Solution:**
Inner term $\sqrt[3]{2n^3} \approx n\sqrt[3]{2}$.
So $2 - n\sqrt[3]{2} \to -\infty$.
Limit is $-\infty$.

**Problem 32)**
$$
u_n = \frac{4^{n}-1}{2^{2n}-7}
$$
**Solution:**
$$
\frac{4^n-1}{4^n-7} \to 1
$$

**Problem 33)**
$$
u_n = \frac{5 \cdot 3^{2n}-1}{4 \cdot 9^n+7}
$$
**Solution:**
$$
3^{2n} = 9^n. \quad \frac{5 \cdot 9^n}{4 \cdot 9^n} = \frac{5}{4}
$$

**Problem 34)**
$$
u_n = \frac{3 \cdot 2^{2n+2}-10}{5 \cdot 4^{n-1}+3}
$$
**Solution:**
$$
\frac{3 \cdot 4^n \cdot 4 - 10}{5 \cdot 4^n \cdot \frac{1}{4} + 3} = \frac{12 \cdot 4^n}{\frac{5}{4} \cdot 4^n} = \frac{12}{1.25} = 9.6
$$

**Problem 35)**
$$
u_n = \frac{-8^n-1}{7^{n+1}}
$$
**Solution:**
$(-8/7)^n \to -\infty$ (magnitude grows, sign strictly negative? No, $8^n/7^n \to \infty$, sign is negative). Limit $-\infty$.

**Problem 36)**
$$
u_n = \frac{2^{n+1}-3^{n+2}}{3^{n+2}}
$$
**Solution:**
$$
\frac{2^{n+1}}{3^{n+2}} - 1 \to 0 - 1 = -1
$$

**Problem 37)**
$$
u_n = (\frac{3}{2})^{n} \frac{2^{n+1}-1}{3^{n+1}-1}
$$
**Solution:**
$$
\frac{3^n}{2^n} \cdot \frac{2 \cdot 2^n}{3 \cdot 3^n} = \frac{3^n \cdot 2 \cdot 2^n}{2^n \cdot 3 \cdot 3^n} = \frac{2}{3}
$$

**Problem 38)**
$$
u_n = \sqrt[n]{3^n+2^n}
$$
**Solution:**
$$
3 \sqrt[n]{1+(2/3)^n} \to 3
$$

**Problem 39)**
$$
u_n = \sqrt[n]{10^n+9^n+8^n}
$$
**Solution:**
Limit is the max base: $10$.

**Problem 40)**
$$
u_n = \sqrt[n]{10^{100}-\frac{1}{10^{100}}}
$$
**Solution:**
$Constant^{1/n} \to 1$.

**Problem 41)**
$$
u_n = \sqrt[n]{(\frac{2}{3})^n+(\frac{3}{4})^n}
$$
**Solution:**
Max base is $3/4$. Limit is $3/4$.

**Problem 42)**
$$
u_n = \frac{1+2+...+n}{n^2}
$$
**Solution:**
$$
\frac{n(n+1)/2}{n^2} \to \frac{1}{2}
$$

**Problem 43)**
$$
u_n = \frac{1^2+2^2+...+n^2}{n^3}
$$
**Solution:**
Sum of squares $\approx n^3/3$. Limit is $1/3$.
