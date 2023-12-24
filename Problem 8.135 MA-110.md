---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.135 MA-110

> [!problem] Problem 8.135
> Let $a,b \in R$, an integral domain. Suppose $a\mid b$ and $b\mid a$. Show that $a=ub$ where $u$ is a unit in $R$.

Let $a,b \in R$, an integral domain. Suppose $a\mid b$ and $b\mid a$. By definition, $ar=b$ and $bs=a$ for some $r,s \in R$. Thus
$$
\begin{align}
(bs)r&=b \\
b(sr) &= b \\
sr &= 1 && \text{cancellation property}.
\end{align}
$$
Thus, both $r$ and $s$ are units.
