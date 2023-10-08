---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 4.59 MA-110

> [!problem] Problem 4.59
> Prove or disprove as appropriate: Suppose $G$ is a group, $H$ a subgroup of $G$, and $a$ and $b$ elements of $G$. If $a \in bH$, then $b \in aH$.

Let $G$ be a group, $H$ a subgroup of $G$ and $a,b \in G$. Suppose $a \in bH$. This implies
$a =bh$ for some $h \in H$. 
$$
\begin{align}
a&=bh\\ 
ah^{-1} &= b.
\end{align}
$$
Because $H$ is a subgroup, $h^{-1} \in H$. Thus, $b \in aH$.
