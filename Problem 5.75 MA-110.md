---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.75 MA-110

> [!problem] Problem 5.75
> Give an example to show that the hypothesis that $H\trianglelefteq G$ is needed in [[Problem 5.74 MA-110|Problem 74]]. That is, find an example of a group and a subgroup where the product of two cosets fails to be a [[Definition 4.1 and 5.1 MA-110|coset]].

Consider the group $D_{3}$ with subgroup $H=\{ (1), (1\ 2) \}$. If we consider
$$
((1\ 2\ 3)H)H= \{ (1\ 2\ 3), (1\ 3) \}\{ (1), (1\ 2) \}=\{ (1), (1\ 2), (1\ 3), (1\ 2\ 3) \}.
$$
The resulting product cannot be a coset, it has order four while $H$ has order two.
