---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.197 MA-111

> [!problem] Problem 10.197
> Let $\left| G \right|=pq$, $p,q$ prime, $p<q$.
> 1. Show that if $p\nmid (q-1)$, there are only two proper nontrivial subgroups of $G$. In this case, what can be said about the group $G$?
> 2. Show that if $p\nmid (q-1)$, the above is not necessarily true. (i.e., Find a counterexample with more than two proper nontrivial subgroups.)

Let $\left| G \right|=pq$, $p,q$ prime, $p<q$, and $p \nmid (q-1)$. By Part 3 of [[Theorem 10.11 MA-111|The Sylow Theorems]], the number of subgroups of order $p$ must be either $1,p,q$ or $qp$.

1.

There cannot be $p$ or $pq$ Sylow $p$-subgroups because those are all congruent to 0 mod $p$. Further, there cannot be $q$ subgroups because $q$ is not congruent to 0 mod $p$ be assumption. Thus, there must be only one Sylow $p$-subgroup.

Arguing similarly will show that there are no Sylow $q$-subgroups of order $q$ or $pq$. Because $p<q$, $p \not\equiv 0 \text{ mod }q$, and there cannot be $p$ Sylow $q$-subgroups. Thus, there is only one Sylow $q$-subgroup.

Because of Lagrange's Theorem, the only possible subgroups are Sylow $p$-subgroups or Sylow $q$-subgroups. Therefore, there are only two non-trivial proper subgroups. 

2.

Consider the group $D_{3}=S_{3}$. This group is of order $6=2 \cdot3$. It has one subgroup of order 3 (the rotations of an equilateral triangle) and two subgroups of order $2$ (the reflections of an equilateral triangle).