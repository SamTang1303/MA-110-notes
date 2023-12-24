---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.141 MA-110

> [!problem] Problem 8.141
> Let $f(x)$ and $g(x)$ be nonzero polynomials in $F[x]$, where $F$ is a field. Let $I=(f(x))$. Suppose that $f(x)$ and $g(x)$ are relatively prime. Prove that $g(x)+I$ is a unit in the ring $F[x]/I$.

Let $f$ and $g$ be nonzero polynomials in $F[x]$, where $F$ is a field. Let $I=(f)$. Suppose that $f$ and $g$ are relatively prime.

By [[Theorem 8.9 MA-110|Theorem 8.9]], there exists some $a,b \in F[x]$ such that
$$
af + bg = 1 = \gcd(f,g).
$$
Therefore,
$$
\begin{align}
1+I &= (bg+af) + I \\
&=  bg+ I && \text{absorption} \\
&= (b+I)(g+I).
\end{align}
$$
Because $1+I$ is the unity of $F[x]/I$, this proves $g(x)+I$ is a unit.
