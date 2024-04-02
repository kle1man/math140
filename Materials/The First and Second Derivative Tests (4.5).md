## Section 4.5: The First and Second Derivative Tests

### Lecture Notes

#### First Derivative Test

A *relative maximum* of a function $f$ occurs at any point $c$ in the domain of $f$ where $f$ changes from increasing ($f'(x)>0$) to decreasing ($f'(x)<0$).

A *relative minimum* of a function $f$ occurs ta any point $c$ in the domain of $f$ where $f$ changes from decreasing ($f'(x)<0$) to increasing ($f'(x)>0$).

$$
\
$$

#### Second Derivative Test

If $f'(c)=0$ and $f''(c)<0$, then $f(c)$ is a *relative maximum*.

If $f'(c)=0$ and $f''(c)>0$, then $f(c)$ is a *relative minimum*.

$$
\
$$

### Examples

#### First Derivative Test

##### p. 246, q. 4:

$f(x)=\frac{x}{x^{3}-2}$

$f'(x)=\frac{x^{3}-2-x*3x^{2}}{(x^{3}-2)^{2}}=\frac{-2(1+x^{3})}{(x^{3}-2)^{2}}$

$x^{3}-2=0$

$x^{3}=2$

$x\neq\sqrt[3]{2}$

$x^{3}-2-3x^{3}=0$

$-2-2x^{3}=0$

$-2(1+x^{3})=0$

$x^{3}=-1$

$x=-1$

<----- $-1$ ----- $\sqrt[3]{2}$ ----->

$\text{Sample numbers between the critical points:}$

$f'(-2)>0$

$f'(0)<0$

$f'(2)<0$

$\text{Thus, there is a relative maximum at }x=-1\text{, due to the function changing from increasing to decreasing. (answer)}$

$$
\
$$

##### p. 246, q. 7:

$f(t)=\sin{t}+\frac{1}{2}t$

$f'(t)=\cos{t}+\frac{1}{2}$

$\cos{t}+\frac{1}{2}=0$

$\cos{t}=\frac{-1}{2}$

<----- $\frac{-2\pi}{3}$ ----- $\frac{2\pi}{3}$ ----- $\frac{4\pi}{3}$ ----- $\frac{8\pi}{3}$ ----->

$\text{Sample numbers between the critical points:}$

$f'(-\pi)=-1+\frac{1}{2}<0$

$f'(0)=1+\frac{1}{2}>0$

$f'(\pi)=-1+\frac{1}{2}<0$

$f'(2\pi)=1+\frac{1}{2}>0$

$\text{Relative max.: }\frac{2\pi}{3}+2\pi k\text{ (answer)}$

$\text{Relative min.: }\frac{-2\pi}{3}+2\pi k\text{ (answer)}$

$$
\
$$

#### Second Derivative Test

##### p. 246, q. 44:

$f(x)=x^{2}(x+3)^{2}$

$\text{Domain: all real numbers (as there is nothing that can be inputted into it to make it not exist)}$

$X\text{-intercept (plug 0 in for }y\text{): }0=x^{2}(x+3)^{2}$

$x^{2}=0\text{ or }(x+3)^{2}=0$

$x=0\text{ or }x=-3$

$Y\text{-intercept (plug 0 in for )}x\text{): }f(0)=0\text{, }(0,0)$

$f'(x)=2x(x+3)^{2}+x^{2}2(x+3)^{1}*(1)$

$f'(x)=(x+3)(2x(x+3)+2x^{2})=2x(x+3)(2x+3)$

$2x(x+3)(2x+3)=0$

$x=0, x=-3, x=\frac{-3}{2}$

$\text{Second derivative test:}$

$f''(x)=[2(x+3)+2x](2x+3)+2x(x+3)2=(4x+6)(2x+3)+4x^{2}+12x$

$f''(0)=6*3>0\text{, meaning that there is a relative min. at }x=0\text{ (answer)}$

$f''(-3)=-6*(-3)+36-36=18>0\text{, meaning that there is a relative min. at }x=-3\text{ (answer)}$

$f''(\frac{-3}{2})=(4(\frac{-3}{2})+6)(2(\frac{-3}{2})+3)+4(\frac{9}{4})+12(\frac{-3}{2})=(-6+6)+9-18=-9<0\text{, meaning that there is a relative max. at }x=\frac{-3}{2}\text{ (answer)}$

$\text{Note: Professor Williams recommends using the first derivative test instead.}$
