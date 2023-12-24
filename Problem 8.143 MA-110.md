---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.143 MA-110

> [!problem] Problem 8.143
> Apply the Euclidean algorithm to the polynomial $f(x)=x^{4}+x^{3}+x^{2}+x+1$ and $g(x)=x^{2}+1$ in $\mathbb{Q}[x]$. Why must this procedure always terminate?

$$
\begin{align}
x^{4}+x^{3}+x^{2}+x+1 &= (x^{2}+x)(x^{2}+1) +1\\
x^{2}+1 &= 1(x^{2}+1) + 0.
\end{align}
$$
Thus, we can express $1$ as a linear combination of $f$ and $g$:
$$
(x^{4}+x^{3}+x^{2}+x+1) - (x^{2}+x)(x^{2}+1) = 1.
$$
This implies $\gcd(f,g)=1$. The process described in the Euclidean Algorithm must terminate because the degree of the successive $r_{n}$'s must decrease with every step. Thus we will always get to the case where the remainder has degree zero, in which case the algorithm will terminate on the next step.
