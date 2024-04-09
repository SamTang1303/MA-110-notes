---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.198 MA-111

> [!problem] Problem 10.198
> Prove that $Z(G)$ is a subgroup of $G$, and that $Z(G) \lhd G$.

Let $G$ be a group. The identity of the group commutes with every element, so $e \in Z(G)$. Let $a,b \in Z(G)$. Let $g \in G$. Define $x:=a^{-1}g$.
$$
\begin{align}
a^{-1}g&=x \\
g&= ax \\
g&= xa && a \in  Z(G) \\
ga^{-1} &= x =a^{-1}g.
\end{align}
$$
Therefore $a^{-1} \in Z(G)$. Furthermore,
$$
\begin{align}
(ab)g &= a(bg) \\
&= a(gb) && b \in  Z(G) \\
&= (ag)b \\
&= (ga)b && a \in  Z(G)\\
&= g(ab).
\end{align}
$$
Thus $ab \in Z(G)$, and $Z(G)$ is a subgroup of $G$. Let $z \in Z(G)$ and $g \in G$. 
$$
gzg^{-1}=gg^{-1}z=z \in  Z(G).
$$
So, $Z(G)$ a normal subgroup of $G$.
