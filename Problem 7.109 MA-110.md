---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.109 MA-110

> [!problem] Problem 7.109
> If $X$ and $Y$ are subsets of a ring, we could define "set multiplication" by letting the product $XY$ be the set $\{ xy \mid x \in X \text{ and } y \in Y \}$, as we did with groups. Unfortunately, this notion of multiplication fails on the cosets of a ring; give an example to show that it fails. In other words, find an example of a ring $R$, an ideal $I$, and a cosets $a+I$ and $b+I$ such that the set $\{ xy \mid x \in a + I \text{ and } y \in b + I \}$ is not a coset of $I$ in $R$.

Consider the ring $\mathbb{Z}_{12}$ with ideal $I=(6) = \{ 0,6 \}$ as discussed in [[Problem 6.106 MA-110|Problem 106]].
$$
\begin{align}
(0+I)(2+I) &= \{ 0,6 \}\{ 2,8 \} \\
&= \{ 0 \cdot 2,0 \cdot 8, 6 \cdot 2,6 \cdot 8 \} \\
&= \{ 0 \} \\
&\neq \{ 2,8 \} \\
&= 2 + I \\
&= (0 + 2) + I.
\end{align}
$$
Therefore, we can see that the given multiplication for cosets does not make them closed.
