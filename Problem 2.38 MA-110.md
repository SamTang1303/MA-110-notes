---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.38 MA-110

> [!problem] Problem 2.38
> Let $G$ and $H$ be groups. Prove that if $G\times H$ is a cyclic group, then $G$ and $H$ are both cyclic groups.

Let $G$ and $H$ be groups and suppose $G\times H$ is a cyclic group with generator $\langle (g,h)\rangle$.

Let $a \in G$ and $b \in H$. By the definition of a cartesian product, $(a,b) \in G\times H$. Because $G\times H$ is cyclic, there exists some $n \in \mathbb{Z}$ such that
$$
(a,b) = (g,h)^{n} = (g^{n},h^{n}).
$$
Therefore, $a=g^{n}$ and $b=h^{n}$. Because we did this for an arbitrary $a \in G$ and $b \in H$, it must be true that $G=\langle g\rangle$ and $H=\langle h\rangle$.
