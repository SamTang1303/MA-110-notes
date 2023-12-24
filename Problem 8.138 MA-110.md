---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.138 MA-110

> [!problem] Problem 8.138
> Let $a(x),b(x),f(x),g(x) \in R[x]$, where $R$ is an integral domain. Suppose that $a(x)f(x)+b(x)g(x)=1$. Prove that $\gcd(f(x),g(x))=1$. (We say that such polynomials $f(x)$ and $g(x)$ are **relatively prime**.)

Let $a(x),b(x),f(x),g(x) \in R[x]$, where $R$ is an integral domain. Suppose that $a(x)f(x)+b(x)g(x)=1$. Let $u(x)=\gcd(f(x),g(x))$. Then, by definition
$$
\begin{align}
a(x)p(x)u(x) + b(x)q(x)u(x) &= 1 && \text{for some }p(x),q(x) \in  R[x]\\
u(x) (a(x)p(x)+b(x)q(x)) &= 1.
\end{align}
$$
Thus, $u(x)$ is a unit. [[Problem 8.131 MA-110|Problem 131]] shows that $u(x)$ must have degree zero. The only monic polynomial with degree zero is $1$, so $u(x)=\gcd(f(x),g(x))=1$.
