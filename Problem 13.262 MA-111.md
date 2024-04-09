---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.262 MA-111

> [!problem] Problem 13.262
> Show that $S_{3}$ and $D_{4}$ are solvable.

First, consider the group $S_{3}$. By [[Problem 10.172 MA-111|Problem 172]], $\langle (1\ 2\ 3)\rangle \lhd S_{3}$. $S_{3}/\langle (1\ 2\ 3)\rangle$ is of order $2$, and therefore must be abelian. Furthermore, $\langle (1\ 2\ 3)\rangle$ is abelian, so $\{ e \}\lhd \langle (1\ 2\ 3)\rangle$. Thus, $S_{3}$ is a solvable group.

Now, consider $D_{4}$, and the sequence of normal subgroups
$$
\{ (1) \} \lhd  \langle (1\ 3)(2\ 4)\rangle \lhd  \langle (1\ 2\ 3\ 4)\rangle \lhd  D_{4}.
$$
The index of each subgroup in its parent group is two for each subgroup, implying they are normal subgroups, and that their quotients are abelian. Thus, $D_{4}$ is a solvable group.