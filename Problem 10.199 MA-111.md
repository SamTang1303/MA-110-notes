---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.199 MA-111

> [!problem] Problem 10.199
> Show, by giving nontrivial examples, that the center of the group can be the whole group, a proper nontrivial subgroup, or a trivial subgroup.

**Showing the center of a group can be the whole group:** Essentially by definition, the center of a group is the whole group if and only if the group is abelian. An example of such a group would be $\mathbb{Z}_{7}$.

**Showing the center of a group can be a proper nontrivial subgroup:** Consider the group $D_{4}$. $Z(D_{4})=\{ (1),(1\ 3)(2\ 4) \}$ is a nontrivial proper subgroup of $D_{4}$.

**Showing the center of a group can be a trivial subgroup:** Consider the group
$$
S_{3} = \{ (1), (1\ 2\ 3), (1\ 3\ 2), (1\ 2), (1\ 3), (2\ 3) \}.
$$
$$
\begin{align}
(1\ 2\ 3)(1\ 2) = (1\ 3) &\neq (1\ 2)(1\ 2\ 3) = (1\ 2) \\
(1\ 3\ 2)(1\ 3) = (1\ 2) &\neq (1\ 3)(1\ 3\ 2) = (2\ 3) \\
(1\ 2\ 3)(2\ 3) = (1\ 2) &\neq (2\ 3)(1\ 2\ 3) = (1\ 3).
\end{align}
$$
This shows that all the non-identity elements of $S_{3}$ are not in the center of $S_{3}$. Thus, $Z(S_{3})=\{ (1) \}$.