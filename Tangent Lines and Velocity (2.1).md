## Section 2.1: Tangent Lines and Velocity

### Lecture Notes

Given a function $f$, a secant line is a line through any two points $(a, f(a))$ and $(x, f(x))$. So given a fixed value $a$ and any other value $x$, the slope of the secant line through $(a,f(a))$ and $(x,f(x))$ is given by the difference quotient

$$
\frac{f(x)-f(a)}{x-a}
$$

$$
\begin{aligned}
\\
\end{aligned}
$$

If this difference quotient approaches a number as we allow $x$ to approach $a$, we say that the limit of $\frac{f(x)-f(a)}{x-a}$ is $L$ as $x$ approaches $a$ and denote this as

$$
\lim_{x \to a}\frac{f(x)-f(a)}{x-a}=L
$$

$$
\begin{aligned}
\\
\end{aligned}
$$

The tangent line to $f$ at the point $(a,f(a))$ is the line through $(a,f(a))$ with the slope $L$

$$
\begin{aligned}
\\
\end{aligned}
$$

Application: For an object traveling in a straight line with position $f(t)$ at time $t$, its average velocity from $t_0$ to $t$ is $\frac{f(t)-f(t_0)}{t-t_0}$. Its velocity is $v(t_0) = \lim_{t \to t_0}\frac{f(t)-f(t_0)}{t-t_0}$.

### Examples

$\text{p.78}$

$\text{ii) }\lim_{x \to -5}\frac{x^2+4x-5}{x+5}=\lim_{x \to -5}\frac{(x+5)(x-1)}{x+5}=\lim_{x \to -5}x-1=-5-1=-6$

$$
\begin{aligned}
\\
\end{aligned}
$$

$\text{15) }\lim_{x \to 0}3(\sin^2{x}+\cos^2{x})=3(1)=3$

$\text{The above uses the identity}$ $\sin^2{x}+\cos^2{x}=1$

$$
\begin{aligned}
\\
\end{aligned}
$$

$\text{17) }\lim_{x \to -1}-\frac{|x|}{x}=\lim_{x \to -1}-\frac{-x}{x}=\lim_{x \to -1}\frac{x}{x}=1$

$\text{The above holds because the absolute value of}$ $x$ $\text{is equal to}$ $-(x)$ $\text{when}$ $x$ $\text{is negative.}$