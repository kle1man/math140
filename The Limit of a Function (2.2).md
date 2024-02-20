## Section 2.2: The Limit of a Function

### Lecture Notes

Limits to know: $\lim_{x \to a}c=c$, $\lim_{x \to a}x=a$, $\lim_{x \to a}(mx+b)=ma+b$, and $\lim_{x \to a}|x|=|a|$, where $c$, $m$, and $b$ are constants.

The equation of the tangent line to $f$ at $(a, f(a))$ is 

$$
y-f(a)=m_a(x-a)
$$

where

$$
m_a=\lim_{x \to a}\frac{f(x)-f(a)}{x-a}
$$

If you ever forget the equation of a line, solve out the slope formula by multiplying the denominator on both sides:

$$
m=\frac{y_2-y_1}{x_2-x_1}
$$

When gravity is the only force acting on an object, its height is given by 

$$
h(t)=-4.9t^2+v_0t+h_0
$$

where $t$ is in seconds, $h(t)$ is in meters, the initial velocity $v(0)=v_0$, and the initial height $h(0)=h_0$.

### Examples

$\text{7) }\lim_{x \to \frac{3}{2}}|x|=|\frac{3}{2}|=\frac{3}{2}$

$\text{20) } f(x)=-x^2+4x$, $(-1,-5)=(a,f(a))$

$m_{-1}=\lim_{x \to -1}\frac{f(x)-f(-1)}{x-(-1)}=\lim_{x \to -1}\frac{-x^2+4x-(-5)}{x+1}=\lim_{x \to -1}\frac{-(x^2-4x-5)}{x+1}=\lim_{x \to -1}\frac{-(x+1)(x-5)}{x+1}=\lim_{x \to -1}-x+5=1+5=6$

$y-f(a)=m_a(x-a)$

$y-(-5)=6(x-(-1))$

$y+5=6(x+1)$

$\text{25)}$ $f(t)=-16t^2+8t+54$, $t_0=2$, $v(t_0)=\lim_{t \to t_0}\frac{f(t)-f(t_0)}{t-t_0}$

$v(2)=\lim_{t \to 2}\frac{-16t^2+8t+54-(16(2)^2+8(2)+54)}{t-2}=\lim_{t \to 2}\frac{-16t^2-(-16(2)^2)+8t-8(2)}{t-2}=\lim_{t \to 2}\frac{-16(t^2-2^2)+8(t-2)}{t-2}$

$\text{Then, using the difference of squares formula}$ $(x^2-a^2)=(x-a)(x+a):$ $\lim_{t \to 2}\frac{-16(t-2)(t+2)+8(t-2)}{t-2}=\lim_{t \to 2}\frac{(t-2)[-16(t+2)+8]}{t-2}=-16(2+2)+8=-64+8=-56$

$\text{37) Refer to ex. 4 on p.85 of the textbook:}$

$h(t)=-4.9t^2+v_0t+h_0$

$\text{"Thrown the balls downward with a speed of 6 m/s" means that}$ $v_0=-6$

$\text{So,}$ $h(t)=-4.9t^2+(-6)t+49$

$\text{a)}$ $v(2)=\lim_{t \to 2}\frac{h(t)-h(2)}{t-2}=\lim_{t \to 2}\frac{-4.9t^2-6t+49-(-4.9(2)^2-6(2)+49)}{t-2}=\lim_{t \to 2}\frac{-4.9(t^2-2^2)-6(t-2)}{t-2}=\lim_{t \to 2}\frac{-4.9(t-2)(t+2)-t(t-2)}{t-2}=-4.9(2+2)-6=-25.6$

$\text{The speed at time}$ $t_0$ $\text{is given by}$ $|v(t_0)|.$ $\text{So, the speed at time}$ $t_0=2$ $\text{is}$ $|-25.6|=25.6$ $\text{m/s.}$