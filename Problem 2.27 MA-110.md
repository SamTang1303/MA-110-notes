---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.27 MA-110

> [!problem] Problem 2.27
> Prove or disprove: if $G$ and $H$ are abelian groups, then $G\times H$ is abelian.

Let $G$ and $H$ be abelian groups, and consider the group $G\times H$. Let $(g_{1},h_{1}),(g_{2},h_{2}) \in G\times H$.
$$
\begin{align}
(g_{2},h_{2})(g_{1},h_{1}) &= (g_{2}g_{1},h_{2}h_{1})\\
&= (g_{1}g_{2},h_{1}h_{2}) && \text{by commutivity}.\\
&= (g_{1},h_{1})(g_{2},h_{2})
\end{align}
$$
Thus, commutativity holds for $G\times H$ and it is an abelian group.
