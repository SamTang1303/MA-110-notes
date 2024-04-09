---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.195 MA-111

> [!problem] Problem 10.195
> Prove that every group of order 45 has a normal subgroup of order 9. Give a general condition for determining when a Sylow $p$-subgroup is a normal subgroup.

Let $G$ be a group such that $\left| G \right|=45$. From [[Theorem 10.11 MA-111|The Sylow Theorems]], we know that there is only one Sylow $p$-subgroup of order $3^{2}$. Because conjugating does not change the order of a group, this implies that $gHg^{-1}=H$ for all $g \in G$. Thus $H$ is normal in $G$.

In general, a Sylow $p$-subgroup with be normal if and only if none of the factors of $\left| G \right|$ are congruent to mod modulo $p$.
