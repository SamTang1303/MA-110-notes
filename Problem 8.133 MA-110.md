---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.133 MA-110

> [!problem] Problem 8.133
> In $\mathbb{Z}[x]$, prove that $(x,2)\neq(x+2)$, $(x,2)\neq (x)$, and $(x,2)\neq(2)$.

By the definition of a linear combination $2 =0 \cdot x + 1 \cdot 2 \in (x,2)$. But, no multiple of $x+2$ has degree less than $1$ (other than $0$) by [[Problem 8.121 MA-110|Problem 121]]. Therefore $2 \notin (x+2)$ and $(x+2)\neq(x,2)$.

For the same reason, $2 \notin (x)$.

Finally, $(2)$ is the set of all polynomials with integer coefficients multiplied by two. Thus the coefficients of all of its elements must be even. But $x+2 \in (x,2)$ has a coefficient of $1$ on the $x$ term. Thus $x+2 \notin (2)$ and $(2) \neq(x,2)$.
