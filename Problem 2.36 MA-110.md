---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.36 MA-110

> [!problem] Problem 2.36
> Show that all of the subgroups considered in [[Problem 2.29 MA-110|Problem 29]] are cyclic, and write each subgroup in the form $\langle a\rangle$, for a suitably chosen generator $a$ in the parent group.

1 ) Let $M_{n}$ denote the set of all multiples of some integer $n$. From Problem 29 we know all subgroups $\mathbb{Z}$ take the form $M_{n}$ where $n$ is any integer. 

Let $k$ be given and consider $M_{k}$. Any element of $M_{k}$ can be written as $c \cdot k$ where $c \in \mathbb{Z}$. This is simply the additive notation for $k^{c}$, so clearly the group is cyclic and can be represented as $\langle k\rangle$. 

2 ) The subgroups of $\langle \mathbb{Z}_{6}, +\rangle$
$$
\begin{align}
&\{ 0 \} = \langle 0\rangle\\
& \{ 0,2,4 \} = \{ 2 \cdot 0 , 2 \cdot 1, 2 \cdot 2\} = \langle 2\rangle &&\\
&\{ 0,3 \} = \{ 0 \cdot 3, 3 \cdot 1 \} = \langle 3\rangle.
\end{align}
$$
Again, remember that the operation in these groups is addition, so multiplication corresponds to exponentiation in multiplicative notation.

3 ) The subgroups of $\langle \mathbb{Z}^{*}_{5}, \times\rangle$
$$
\begin{align}
& \{ 1 \} = \langle 1\rangle\\
& \{ 1,4 \} = \{ 4^{2}, 4^{1} \} = \langle 4\rangle
\end{align}
$$
