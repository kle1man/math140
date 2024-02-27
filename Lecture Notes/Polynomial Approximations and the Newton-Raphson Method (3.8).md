## Section 3.8: Polynomial Approximations and the Newton-Raphson Method

### Lecture Notes

Given a function $f$ that is differentiable at $a$, we can approximate the function $f$ at a value $x$ near $a$ by using the tangent line (or linear) approximation

$$
f(x)\approx f(a)+f'(a)(x-a)\\
(f(a+h)\approx f(a)+f'(a)h)
$$

$$
\
$$

Given a function $f$, we can use the Newton-Raphson Method to approximate a solution to the equation $f(x)=0$:

Steps:

1. Find values $a$ and $b$ such that $f(a)<0<f(b)$ or $f(b)<0<f(a)$.
2. Pick any value $c_1$ in $(a,b)$. If $f(c_1)=0$, you're done. If $f'(c_1)=0$, you must reselect your $c_1$.
3. Find $g(c_1)$, where $g(x)=x-\frac{f(x)}{f'(x)}$.
4. Repeat step (3) with the new value $c_2$ to get $c_3=g(c_2)$.
5. Continue repeating this process where $c_2=g(c_1)$, $c_3=g(c_2)$, $c_4=g(c_3)$, ... , $c_{i+1}=g(c_i)$.
6. Stop once you get $c_{i+1}=c_i$ from your calculator (aka once terms start to repeat). Then $c_i$ is your answer.

$$
\
$$

We want to approximate $f(x+h)-f(x)$. This is given by the differential, denoted $df$,

$$
df=f'(x)h
$$

$$
\
$$

### Examples

$\text{3) }\sqrt[3]{29}=29^{\frac{1}{3}}$

$f(x)=x^{\frac{1}{3}}$

$f'(x)=\frac{1}{3}x^{\frac{-2}{3}}$

$f(x)\approx f(a)+f'(a)(x-a)$

$\sqrt[3]{29}\approx f(27)+f'(27)(29-27)$

$\sqrt[3]{29}\approx 27^{\frac{1}{3}}+\frac{1}{3}(27)^{\frac{-2}{3}}(2)=3+\frac{2}{3}(27^{\frac{1}{3}})^{-2}=3+\frac{2}{3}*\frac{1}{9}=3+\frac{2}{27}$

$$
\
\
$$

$\text{8) }\cot(\frac{11}{36}\pi)$

$f(x)=\cot(x)$

$f'(x)=-\csc^{2}$

$f(x)\approx f(a)+f'(a)(x-a)$

$\cot(\frac{11}{36}\pi)\approx \cot(\frac{\pi}{3})-\csc^{2}(\frac{\pi}{3})(\frac{11}{36}\pi-\frac{12}{36}\pi)$

$\cot(\frac{11}{36}\pi)\approx \frac{1}{\sqrt{3}}-\frac{4}{3}(\frac{-\pi}{36})=\frac{1}{\sqrt{3}}+\frac{4\pi}{108}=\frac{1}{\sqrt{3}}+\frac{\pi}{27}$

$$
\
\
$$

$\text{35) }x^{3}-3x-1=0\text{, }[1,2]$

$f(x)=x^{3}-3x-1\text{, }f'(x)=3x^{2}-3\text{, }g(x)=x-\frac{x^{3}-3x-1}{3x^{2}-3}\text{, } [1,2]=[a,b]$

$c_1=\frac{3}{2}\text{, }f'(c_1)\neq0$

$c_2=g(c_1)=g(\frac{3}{2})=\frac{3}{2}-\frac{(\frac{3}{2})^{3}-3(\frac{3}{2})-1}{3(\frac{3}{2})^{2}-3}=2.06666666$

$c_3=g(c_2)=1.90008756039$

$c_4=g(c_3)=1.8797199044$

$\text{...}$

$c_6=1.8793852416$

$c_7=1.8793852416$

$$
\
\
$$

$\text{57) }V=\frac{4}{3}\pi r^{3}(\frac{1}{2})=\frac{2}{3}\pi r^{3}\text{, }r=20\text{ft, }h=\frac{1}{100}\text{in}*\frac{1\text{ft}}{12\text{in}}=\frac{1}{1200}\text{ft}$

$\text{Approximate }V(r+h)-V(r)=v(20+\frac{1}{1200})-V(20)\text{ by }dV=V'(r)*h=V'(20)\frac{1}{1200}$

$V'(r)=\frac{2\pi}{3}3r^{2}=2\pi r^{2}$

$df=V'(20)\frac{1}{1200}=2\pi(20)^{2}*\frac{1}{1200}$
