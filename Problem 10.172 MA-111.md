---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.172 MA-111

> [!problem] Problem 172
> Let $H$ be a subgroup of a group $G$, and suppose that $[G:H]=2$. Prove that $H \trianglelefteq G$.

Let $H$ be a subgroup of a group $G$, and suppose that $[G:H]=2$. Then $G/H$ only has two distinct cosets, $H$ and $G\setminus H$.

First, suppose $g \in H$. Then $gH=H=Hg$. Next, suppose $g \notin H$. Then $gH=G\setminus H=Hg$. Thus $gH=Hg$ for all $g \in G$, so $H \trianglelefteq G$.
