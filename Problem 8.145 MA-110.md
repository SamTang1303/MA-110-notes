---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.145 MA-110

> [!problem] Problem 8.145
> It is easy to check that the ring $\mathbb{Z}_{3}$ is a field. Carry out the Euclidean algorithm using the polynomials $f(x)=x^{4}+2x^{3}+2x+1$ and $g(x)=x^{3}+2x^{2}+x+2$ in $\mathbb{Z}_{3}[x]$.

$$
\begin{align}
x^{4}+2x^{3}+2x+1 &= x(x^{3}+2x^{2}+x+2) -x^{2}+1 \\
x^{3}+2x^{2}+x+2 &= (-x-2)(-x^{2}+1) + 2x+4 \\
x^{3}+2x^{2}+x+2 &= (-x-2)(-x^{2}+1) + 2x+1 && \text{we are working in }\mathbb{Z}_{3}\\
-x^{2}+1 &= \left( -\frac{x}{2} +1 \right)(2x+1) - 3 \\
-x^{2}+1 &= \left( -\frac{x}{2} +1 \right)(2x+1) && \text{we are working in }\mathbb{Z}_{3} \\
\end{align}
$$
Thus the Euclidean algorithm tells us $\gcd(f,g)=2x+1$.
