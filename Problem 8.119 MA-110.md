---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.119 MA-110

> [!problem] Problem 8.119
> Prove that every [[Definition 8.4 MA-110|field]] is an [[Definition 8.3 MA-110|integral domain]].

Let $F$ be a field. Let $a,b,r \in F$ with $r\neq0$ and suppose $ar=br$. Since $F$ is a field, $r^{-1} \in F$ exist.
$$
\begin{align}
ar&=br \\
arr^{-1}&= brr^{-1} \\
a&= b.
\end{align}
$$
Therefore $F$ satisfies the [[Definition 8.1 MA-110|cancellation property]] and is an integral domain.
