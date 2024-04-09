---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.185 MA-111

> [!problem] Problem 10.185
> Use the result of the previous problem to prove that if $p$ is a prime that divides $\left| G \right|$, then $G$ has an element of order $p$.

[[Problem 10.184 MA-111|Problem 184]] says that for a group $G$ with prime factor $p$, there exists a $p$-tuple of elements of $G$ $(g_{0},g_{1},\dots,g_{p-1})$ which is invariant under shifts and is not entirely comprised of the identity of $G$. For any $k \in \mathbb{Z}_{p}$, shifting by $k$ maps $g_{0}$ to $g_{k}$. Thus $g_{0}=g_{k}$ for all $k \in \mathbb{Z}_{p}$, and $(g_{0},g_{1},\dots g_{p-1})=(g_{0},g_{0},\dots,g_{0})$. By assumption, $g_{0}\neq e$, and $\prod_{i=0}^{p-1}g_{0}=g_{0}^{p}=e$. Because $p$ is prime, Theorem 10.1 part 3 implies $\left| g_{0} \right|=p$.

$k \in \mathbb{Z}_{p}$