---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.131 MA-110

> [!problem] Problem 8.131
> Let $F$ be a field. Prove that the only units of $F[x]$ are the nonzero constants. (More generally, if $R$ is an integral domain, then any unit of $R[x]$ must have degree zero.)

Let $F$ be a field, and let $p(x)$ be a unit of $F[x]$. The zero polynomial has no inverse, so $p(x)$ must have a degree. Because $p(x)(p(x))^{-1}=1$, [[Problem 8.121 MA-110|Problem 121]] implies
$$
\deg(p) + \deg(p^{-1}) = \deg(1) = 0.
$$
This is only possible if both $p$ and $p^{-1}$ have degree zero, i.e., are non-zero constant polynomials.
