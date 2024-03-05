## Section 4.1: Maximum and Minimum Values

### Lecture Notes

Given a function $f$, $c$ is a *critical number* of $f$ if $f'(c)=0$ or $c$ is in the domain of $f$ but $f'(c)$ is undefined.

$$
\
$$

A value $f(x)$ of a function $f$ is an *extreme value* if $f(x)$ is a maximum or minimum value of $f$.

To find extreme values on $[a,b]$:

1. Find all critical numbers $c$ in $[a,b]$.
2. Find $f(c)$ for all critical numbers $c$ in $(a,b)$.
3. Find $f(a)$ and $f(b)$.
4. The largest of all values in (2) and (3) is a *maximum*, while the smallest of all values in (2) and (3) is a *minimum*.

$$
\
$$

### Examples

#### Critical Numbers

##### p. 216, q. 6:

$g(x)=x-\frac{4}{x^{2}}=x-4x^{-2}$

$g'(x)=1+8x^{-3}=0$

$1+\frac{8}{x^{3}}$

$x^{3}+8=0$

$x^{3}=-8$

$x=-2\text{ (answer)}$

$\text{Note: 0 is not a critical number because 0 is not in the domain of }g$

$$
\
$$

##### p. 216, q. 16:

$f(x)=\frac{1}{e^{x}-1}$

$f'(x)=\frac{0*(e^{x}-1)-e^{x}}{(e^{x}-1)^{2}}$

$-e^{x}\neq 0\text{ and }e^{x}>0\text{, meaning that}-e^{x}<0$

$\text{Now that you have proven that the numerator cannot equal 0, check what could make the denominator undefined:}$

$e^{x}\text{ for }x=0\text{ could work, but doesn't because 0 isn't within the domain of }f(x)$

$\text{No critical numbers (answer)}$

$$
\
$$

#### Extreme Values

##### p. 216, q. 23:

$k(z)=\sqrt{1+z^{2}},[-2,3]$

$\text{Finding critical numbers:}$

$k(z)=(1+z^{2})^{\frac{1}{2}}$

$k'(z)=\frac{1}{2}(1+z^{2})^{\frac{-1}{2}}*(2z)$

$\frac{z}{\sqrt{1+z^{2}}}=0$

$z=0$

$\text{Finding }f(c)\text{ for all critical numbers }c\text{:}$

$k(0)=\sqrt{1+0}=1$

$\text{Finding }f(a)\text{ and }f(b)\text{:}$

$k(-2)=\sqrt{1+4}=\sqrt{5}\text{ and }k(3)=\sqrt{1+9}=\sqrt{10}$

$\text{Determining largest and smallest values, thus minimums and maximums:}$

$\sqrt{10}\text{ is a maximum (occurs at }x=3\text{) (answer)}$

$1\text{ is a minimum (occurs at }x=0\text{) (answer)}$

$$
\
$$

##### p. 216, q. 32:

$f(x)=e^{x}-e^{2x},[0,1]$

$\text{Finding critical numbers:}$

$f'(x)=e^{x}-2e^{2x}$

$e^{x}-2e^{2x}=0$

$\frac{e^{x}}{e^{2x}}=\frac{2e^{2x}}{e^{2x}}$

$e^{-x}=2$

$\ln{e^{-x}}=\ln{2}$

$-x=\ln{2}$

$x=-\ln{2}$

$\text{Finding }f(c)\text{ for all critical numbers }c\text{:}$

$c=-\ln{2}\text{ is not in the domain }[0,1]\text{. Thus, there is nothing to do for this step.}$

$\text{Finding }f(a)\text{ and }f(b)\text{:}$

$f(0)=e^{0}-e^{0}=0$

$f(1)=e^{1}-e^{2}<0$

$\text{Determining largest and smallest values, thus minimums and maximums:}$

$f(0)=0\text{ is a maximum (occurs at }x=0\text{) (answer)}$

$e-e^{2}\text{ is a minimum (occurs at }x=1\text{) (answer)}$

$$
\
$$

##### p. 216, q. 29:

$f(x)=\tan{\frac{x}{2}},(\frac{-\pi}{2},\frac{\pi}{6})$

$\text{Finding critical numbers:}$

$f'(x)=\sec^{2}{\frac{x}{2}}*(\frac{1}{2})=\frac{1}{2}\sec^{2}{\frac{x}{2}}$

$\frac{1}{2\cos^{2}{\frac{x}{2}}}\neq0$

$\text{When is }\cos{\theta}\text{ equal to 0? When }\theta=\frac{\pi}{2},\frac{3\pi}{2},\frac{-\pi}{2}.$

$\text{However, }x=\pi,x=3\pi,\text{ and }x=-\pi\text{ aren't within the domain. Thus, there are infinitely many critical values but none in }(\frac{-\pi}{2},\frac{\pi}{6}).$

$\text{Finding }f(c)\text{ for all critical numbers }c\text{:}$

$\text{There are no critical values, there is nothing to do for this step.}$

$\text{Finding }f(a)\text{ and }f(b)\text{:}$

$\text{The interval doesn't have any included endpoints, so there is nothing to do for this step as well.}$

$\text{Determining largest and smallest values, thus minimums and maximums:}$

$\text{On }(\frac{-\pi}{2},\frac{\pi}{6}),f'(x)\text{ is either always positive of always negative.}$

$\text{Test: }x=0, f'(0)=\frac{1}{2\cos^{2}{0}}=\frac{1}{2}>0\text{, so }f\text{ is always increasing on }(\frac{-\pi}{2},\frac{\pi}{6}).$

$\text{No extreme values on }(\frac{-\pi}{2},\frac{\pi}{6})\text{ (answer)}$

$$
\
$$

##### p. 216, q. 22:

$f(t)=t^{2}-\frac{4}{t},[1,3)$

$\text{Finding critical numbers:}$

$f(t)=t^{2}-4t^{-1}$

$f'(t)=2t+4t^{-2}$

$2t+\frac{4}{t^{2}}=0$

$2t^{3}+4=0$

$2t^{3}=-4$

$t^{3}=-2$

$t=2^{\frac{1}{3}}$

$\text{Finding }f(c)\text{ for all critical numbers }c\text{:}$

$c=2^{\frac{1}{3}}\text{ is not in the domain }[1,3)\text{, so there is nothing to do for this step.}$

$\text{Finding }f(a)\text{ and }f(b)\text{:}$

$f(1)=1-4=-3$

$\text{Note: the reason for not evaluating for }f(3)\text{ is because the endpoint is not inclusive.}$

$\text{Determining largest and smallest values, thus minimums and maximums:}$

$\text{To test whether }f(a)=f(1)=-3\text{ is the minimum, we can plug a number in:}$

$f(2)=4-2=2>-3\text{, meaning }f(1)\text{ is indeed the minimum.}$

$\text{Minimum: }(1,-3)\text{ (answer)}$
