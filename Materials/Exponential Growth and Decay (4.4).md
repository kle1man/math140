## Section 4.4: Exponential Growth and Decay

### Lecture Notes

For exponential growth/decay problems, we'll use the function:

$$
f(t)=f(0)*e^{kt}
$$

where:
- $f(t)$ is the amount at a time $t$ (ending amount)
- $f(0)$ is the amount at time $t=0$ (starting amount)
- $k$ is the growth/decay constant
- $t$ is time

Exponential growth/decay problems usually require two steps:
1. Find $k$
2. Use $k$ in the function $f(t)$

$$
\
$$

### Examples

#### Regular Exponential Growth/Decay

##### p. 238, q. 4:

$f(t)=f(0)*e^{kt}$

$f(0)=3.15b (1962)$

$f(16)=4.238b (1978)$

$f(16)=f(0)*e^{16k}$

$4.238=3.15e^{16k}$

$\frac{4.238}{3.15}=e^{16k}$

$\ln{\frac{4.238}{3.15}}=\ln{e^{16k}}$

$k=\frac{1}{16}\ln{\frac{4.238}{3.15}}$

$f(t)=3.15b*e^{\frac{1}{16}\ln{\frac{4.238}{3.15}}}$

$f(38)=3.15b*e^{\frac{38}{16}\ln{\frac{4.238}{3.15}}}\text{ (answer)}$

$$
\
$$

##### p. 238, q. 8:

$\text{"amount... is proportional to the [rate]"}$

$f(t)=f(0)*e^{kt}$

$f(0)=4000$

$f(4)=500$

$500=4000e^{4k}$

$\frac{500}{4000}=e^{4k}$

$\frac{1}{8}=e^{4k}$

$\ln{\frac{1}{8}}=4k$

$k=\frac{1}{4}\ln{\frac{1}{8}}$

$f(t)=4000e^{\frac{t}{4}\ln{\frac{1}{8}}}$

$\text{Because the amount is proportional to the rate, }\frac{1}{2}f(0)=f(0)*e^{kt}$

$2000=4000e^{\frac{t}{4}\ln{\frac{1}{8}}}$

$\frac{1}{2}=e^{\frac{t}{4}\ln{\frac{1}{8}}}$

$\ln{\frac{1}{2}}=\frac{t}{4}\ln{\frac{1}{8}}$

$\frac{\ln{\frac{1}{2}}}{\ln{\frac{1}{8}}}=\frac{t}{4}$

$t=\frac{4\ln{\frac{1}{2}}}{\ln{\frac{1}{8}}}\text{ (answer)}$

$$
\
$$

#### Half-Life

##### p. 238, q. 10:

$f(t)=f(0)*e^{kt}$

$\text{In an example, we find the half-life of }C^{14}\text{ to be }5730\text{ years.}$

$\text{ii) percentage remaining: }\frac{\text{ending amount}}{\text{starting amount}}=\frac{f(5300)}{f(0)}$

$\text{i) Find }k\text{: }\frac{1}{2}f(0)=f(0)*e^{5730k}$

$\frac{1}{2}=e^{5730k}$

$\ln{\frac{1}{2}}=5730k$

$k=\frac{1}{5730}\ln{\frac{1}{2}}$

$f(t)=f(0)*e^{\frac{t}{5730}\ln{\frac{1}{2}}}$

$\frac{f(5300)}{f(0)}=\frac{f(0)*e^{\frac{5300}{5730}\ln{\frac{1}{2}}}}{f(0)}$

$=e^{\frac{530}{5730}\ln{\frac{1}{2}}}\text{ (answer)}$

$$
\
$$

##### p. 238, q. 14:

$f(t)=f(0)*e^{kt}$

$\frac{1}{2}f(0)=f(0)*e^{3.8k}\text{ "half-life is 3.8 days"}$

$\frac{1}{2}=e^{3.8k}$

$\ln{\frac{1}{2}}=3.8k$

$k=\frac{1}{3.8}\ln{\frac{1}{2}}$

$f(t)=f(0)*e^{\frac{t}{3.8}\ln{\frac{1}{2}}}$

$\text{How long it takes to change from }1.5*\text{"safe" to "safe"}$

$\text{If the safe amount is}f(0)\text{, the "50\% above" is }f(0)+0.5f(0)=1.5f(0)$

$\text{This is our starting amount and we want our ending amount to be "safe": }f(0)$

$f(0)=1.5f(0)*e^{\frac{t}{3.8}\ln{\frac{1}{2}}}$

$1=1.5e^{\frac{t}{3.8}\ln{\frac{1}{2}}}$

$\frac{1}{1.5}=e^{\frac{t}{3.8}\ln{\frac{1}{2}}}$

$\ln{\frac{2}{3}}=\frac{t}{3.8}\ln{\frac{1}{2}}$

$t=\frac{3.8\ln{\frac{2}{3}}}{\ln{1}{2}}\text{ (answer)}$

$$
\
$$

##### p. 238, q. 7:

$\text{a) }f(t)=f(0)*e^{kt}$

$\frac{1}{2}=e^{kt}$

$\ln{\frac{1}{2}}=kt$

$\ln{1}-\ln{2}=kt$

$t=\frac{-\ln{2}}{k}=h\text{ (answer) (solve for }k\text{, then simplify for question (b) below)}$

$\text{b) }f(t)=f(0)*e^{kt}$
