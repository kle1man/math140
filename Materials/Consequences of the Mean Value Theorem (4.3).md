## Section 4.3: Consequences of the Mean Value Theorem

### Lecture Notes

#### Antiderivatives

Given a function $f$, we say that $F$ is an *antiderivative* of $f$ if:

$$
F'(x)=f(x)
$$

$$
\
$$

#### Finding the intervals of a function increasing and decreasing

Steps:
1. Find the critical numbers of $f$ in $I$.
2. Draw a number line of the domain and only label the critical numbers (and holes in the domain).
3. Pick a test value $c$ in each interval on the number line. Find $f'(c)$.
4. Determine whether each $f'(c)$ is greater than or less than 0. If greater, the function is increasing. If less, the function is decreasing.

$$
\
$$

### Examples

#### Antiderivatives

##### p. 230, q. 1:

$\text{What function(s) have the derivative }0\text{?}$

$f(x)=C\text{ (answer)}$

$\text{Check with }f'(x)=0$

$$
\
$$

##### p. 230, q. 2:

$\text{What function(s) have the derivative }-2\text{?}$

$f(x)=-2(x)+C\text{ (answer)}$

$$
\
$$

##### p. 230, q. 3:

$\text{What function(s) have the derivative }3x\text{?}$

$f(x)=\frac{3}{2}(x^{2})+C\text{ (answer)}$

$$
\
$$

##### p. 230, q. 4:

$\text{What function(s) have the derivative }-6x+5\text{?}$

$f(x)=-6(\frac{x^{2}}{2})+5x+C\text{ (answer)}$

$$
\
$$

##### p. 230, q. 5:

$\text{What functions have the derivative }-x^{2}$

$f(x)=-(\frac{x^{3}}{3})+C$

$$
\
$$

##### p. 230, q. 8:

$\text{What function(s) have derivative }\csc^{2}{\pi x}\text{?}$

$\text{To answer this, try to guess different things that might work until you narrow it down:}$

$F(x)=\cot{x},f(x)=-\csc^{2}{x}$

$F(x)=-\cot{x},f(x)=\csc^{2}{x}$

$F(x)=-\cot{\pi x},f(x)=\pi\csc^{2}{\pi x}$

$F(x)=-\frac{-1}{\pi}\cot{\pi x},f(x)=\csc^{2}{\pi x}$

$f(x)=\frac{-1}{\pi}\cot{\pi x}+C\text{ (answer)}$

$$
\
$$

##### p. 230, q. 16:

$f'(x)=\frac{-3}{2}x^{2},f(-1)=\frac{-1}{2}$

$\text{Referencing back to q. 5 above: }f(x)=\frac{-3}{2}(\frac{x^{3}}{3})+C=\frac{-x^{3}}{2}+C$

$\frac{-1}{2}=f(-1)=\frac{1}{2}+C$

$C=-1$

$f(x)=\frac{-x^{3}}{2}-1\text{ (answer)}$

$$
\
$$

##### p. 230, q. 24:

$f''(x)=0,f'(2)=3,f(-1)=1$

$f'(x)=C_{1}$

$C_{1}=f'(2)=3$

$\text{So }C_{1}=3\text{ and }f'(x)=3$

$f(x)=3x+C_{2}$

$1=f(-1)=3(-1)+C_{2}$

$1=-3+C_{2}$

$C_{2}=4$

$f(x)=3x+4\text{ (answer)}$

$$
\
$$

#### Finding the intervals of a function increasing and decreasing

##### p. 230, q. 32:

$f(x)=4x^{3}-6x^{2}-9x$

###### i) Find the critical numbers of $f$ in $I$.

$f'(x)=12x^{2}-12x-9=3(4x^{2}-4x-3)=3(2x+1)(2x-3)$

$3(2x+1)(2x-3)=0$

$2x+1=0\text{ or }2x-3=0$

$\text{Critical numbers: }x=\frac{-1}{2},x=\frac{3}{2}$

###### ii) Draw a number line of the domain and only label the critical numbers (and holes in the domain).

<------$\frac{-1}{2}$------$\frac{3}{2}$------>

###### iii) Pick a test value $c$ in each interval on the number line. Find $f'(c)$.

$\text{Before }\frac{-1}{2},f'(-1).$

$\text{Between }\frac{-1}{2}\text{ and }\frac{3}{2},f'(0).$

$\text{After }\frac{3}{2},f'(2)$

###### iv) Determine whether each $f'(c)$ is greater than or less than 0. If greater, the function is increasing. If less, the function is decreasing.

$f'(-1)>0$

$f'(0)<0$

$f'(2)>0$
