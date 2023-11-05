---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.118 MA-110

> [!problem] Problem 8.118
>     Let $R$ be a commutative ring. Prove that, if $R$ has no zero divisors, then $R$ has the cancellation property.

Let $R$ be a commutative ring such that $R$ has no zero divisors. Let $a,b,r \in R$ with $r\neq0$ such that $ar=br$.
$$
\begin{align}
ar&= br \\
ar-br &= 0 \\
(a-b)r &= 0
\end{align}
$$
Because $(a-b)$ and $r$ cannot be zero divisors and $r\neq0$, the only way the equation above is possible is if $a-b=0$. This implies $a=b$, and the [[Definition 8.1 MA-110|cancellation property]] is satisfied.
