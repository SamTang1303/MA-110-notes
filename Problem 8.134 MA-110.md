---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.134 MA-110

> [!problem] Problem 8.134
> Let $a,b,c \in R$, a commutative ring. Prove that if $a\mid b$ and $b\mid c$, then $a\mid c$. (This shows that the "$\mid$" relation is **transitive**.)

Let $a,b,c \in R$, a commutative ring. Then, for some $r,s \in R$
$$
\begin{align}
ar &= b \\
&\text{and} \\
bs &= c.
\end{align}
$$
Therefore
$$
\begin{align}
(ar)s &= c \\
a(rs) &= c.
\end{align}
$$
Thus, by [[Definition 8.7 MA-110|definition]], $a\mid c$.
