---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.196 MA-111

> [!problem] Problem 10.196
> Prove that there is no [[Definition 10.12 MA-111|simple group]] of order 56.

Let $G$ be a group of order 56. The [[Theorem 10.11 MA-111|The Sylow Theorem]] Part 3 tells us that there are either $1$ or $8$ subgroups of order $7$ and there are either $1$ or $7$ groups of order 2. Suppose to the contrary that there are $8$ subgroups of $G$ of order $7$. The pairwise intersections of the subgroups of order $7$ include only the identity element because $7$ is prime and the intersection of two subgroups is a subgroup. Therefore, they must all have no elements in common. Thus, there are $48$ elements of order $7$ in $G$. Let $X$ be the set $\{ g \in G \mid \left| g =7 \right|\}$.

Let $Y$ be a subgroup of order eight. $Y$ will be comprised entirely of elements whose order divides 8. This means $Y$ is disjoint from $X$. Because $\left| X \right|+\left| Y \right|=\left| G \right|$, $Y$ must be the only Sylow $8$-subgroup, implying it is normal.
