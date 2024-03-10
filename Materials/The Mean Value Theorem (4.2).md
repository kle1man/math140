## Section 4.2: The Mean Value Theorem

### Lecture Notes

#### Mean Value Theorem (MVT)

Let $f$ be continuous on $[a,b]$ and differentiable on $(a,b)$. Then there is a number $c$ in $(a,b)$ such that:

$$
f'(c)=\frac{f(b)-f(a)}{b-a}
$$

$$
\
$$

#### Rolle's Theorem

Steps (given that $f$ is continuous on $[a,b]$ and differentiable on $(a,b) $):
1. Find the function values at the endpoints of the interval ($f(a)$ and $f(b)$). If $f(a)=f(b)$, Rolle's Theorem applies. If not, it doesn't.
2. If $f(a)=f(b)$, find the derivative of the function, $f'(x)$, and set it equal to $0$ to find the critical points.
3. If there's at least one critical point in the interval $(a,b)$, then there exists at least one point $c$ in $(a,b)$ where $f'(c)=0$, satisfying the conditions of Rolle's Theorem.

$$
\
$$

### Examples

#### Mean Value Theorem

##### p. 222, q. 6:

$f(x)=x^{3}-2,a=-3,b=3$

$f'(x)=3x^{2}$

$\frac{f(b)-f(a)}{b-a}=\frac{3^{3}-2-((-3)^{3}-2)}{3-(-3)}=\frac{27-2+27+2}{6}=\frac{54}{6}=9$

$\text{Find }c\text{ in }(-3,3)\text{ such that }f'(c)=9$

$3c^{2}=9$

$c^{2}=3$

$c=\pm\sqrt{3}\text{ (answer)}$

$$
\
$$

##### p. 222, q. 12:

$f(x)=\sin{\frac{\pi}{2}x},a=-1,b=1$

$\frac{f(b)-f(a)}{b-a}=\frac{\sin{\frac{\pi}{2}}-\sin{\frac{-\pi}{2}}}{1-(-1)}=\frac{1-(-1)}{1-(-1)}=1=m$

$\text{Approximate a solution to }f'(c)=m\text{ where, when }c\text{ is in }(-1,1),f'(c)-m=0$

$f'(x)=\cos{\frac{\pi}{2}x}*\frac{\pi}{2}$

$h(x)=f'(x)-m=\frac{\pi}{2}\cos{\frac{\pi}{2}x}-1\text{ on }[-1,1]$

$g(x)=x-\frac{h(x)}{h'(x)}$

$c_{1}=0$

$h'(x)=\frac{\pi}{2}(-\sin{\frac{\pi}{2}x}*\frac{\pi}{2})$

$h'(x)=\frac{-\pi^{2}}{4}\sin{\frac{\pi}{2}x}$

$h'(0)=0\text{, but we can't use }c_{1}=0$

$c_{1}=\frac{1}{2}$

$c_{2}=g(c_{1})=g(\frac{1}{2})=\frac{1}{2}-\frac{\frac{\pi}{2}\cos{\frac{\pi}{4}}-1}{\frac{-\pi^{2}}{4}\sin{\frac{\pi}{4}}}=c_{3}=g(c_{2})...$

$$
\
$$

#### Rolle's Theorem

##### p. 222, q. 22:

$f(x)=x\cos{x},[0,\frac{\pi}{2}],\text{ show that }\cot{x}=x\text{ has a solution in }(0,\frac{\pi}{2})$

$\text{i) Check that }f(0)=f(\frac{\pi}{2})$

$f(0)=0,f(\frac{\pi}{2})=\frac{\pi}{2}\cos{\frac{\pi}{2}}=0$

$\text{ii) Since }f(0)=f(\frac{\pi}{2})\text{, by Rolle's Theorem there is a value }c\text{ in }(0,\frac{\pi}{2})\text{ such that }f'(c)=0$

$f'(x)=\cos{x}-x\sin{x}$

$\cos{c}-c\sin{c}=0$

$\cos{c}=c\sin{c}$

$\frac{\cos{c}}{\sin{c}}=c$

$\cot{c}=c\text{ (answer)}$

$$
\
$$

#### Lower and Upper Bounds

##### p. 222, q. 18:

$33^{\frac{1}{5}}$

$\text{The question said to use the formula from q. 15: for }|f'(x)|\leq M\text{ with }a\leq x\leq b,f(a)-M(b-a)\leq f(b)\leq f(a)+M(b-a)$

$\text{* For our purposes, }M=f'(a)$

$\text{i) Find }M>0\text{ such that for all }x\text{ in }[a,b],|f'(x)|\leq M$

$f(x)=x^{\frac{1}{5}},a=32\text{ (since }f(32)\text{ is easily evaluated)},b=33$

$f'(x)=\frac{1}{5}x^{\frac{-4}{5}}=\frac{1}{5x^{\frac{4}{5}}}$

$M=f'(a)=f'(32)=\frac{1}{5(32)^{\frac{4}{5}}}=\frac{1}{5(32^{\frac{1}{5}})^{4}}=\frac{1}{5(2)^{4}}=\frac{1}{80}$

$f(a)-M(b-a)\leq f(b)\leq f(a)+M(b-a)$

$2-\frac{1}{80}(33-32)\leq 33^{\frac{1}{5}}\leq 2+\frac{1}{80}(33-32)$

$2-\frac{1}{80}\leq 33^{\frac{1}{5}}\leq 2+\frac{1}{80}\text{ (answer)}$

$$
\
$$

#### Estimating Distance

##### p. 222, q. 20:

$\sqrt{5}=5^{\frac{1}{2}},f(x)=x^{\frac{1}{2}},a=2.2^{2},b=5$

$\text{Find }M=f'(a)$

$f'(x)=\frac{1}{2}x^{\frac{-1}{2}}=\frac{1}{2\sqrt{x}}$

$M=f'(2.2^{2})=\frac{1}{2\sqrt{2.2^{2}}}=\frac{1}{2(2.2)}=\frac{1}{4.4}$

$\text{* Estimate how far }f(b)\text{ is from }f(a)\text{ using the identity }|f(b)-f(a)|\leq M(b-a)$

$|\sqrt{5}-\sqrt{2.2^{2}}|\leq \frac{1}{4.4}(5-2.2^{2})\text{ (answer)}$
