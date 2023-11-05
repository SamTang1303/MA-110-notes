---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.89 MA-110

> [!problem] Problem 5.89
> Let $H$ and $K$ be normal subgroups of a group $G$ with $K \leq  H$. Prove that $H/K$ is a subgroup of $G/K$, and furthermore, that $H/K \trianglelefteq G/K$.

Let $H$ and $K$ be normal subgroups of a group $G$ with $K \trianglelefteq H$. First, we will show $H/K$ is a subgroup of $G/K$. $H\subseteq G$, so $H/K\subseteq G/K$.

1 ) Since $e \in H$, $eK=K \in H/K$. Therefore, $H/K$ contains the identity of $G/K$.

2 ) Let $aK,bK \in H/K$ where $a,b \in H$.
$$
aKbK=(ab)K.
$$
Because $H$ is a group, $ab \in H$, so $aKbK \in H/K$ and the subgroup is closed under multiplication.

3 ) Let $aK \in H/K$ with $a \in H$. $(aK)(a^{-1}K)=(aa^{-1}K)=K$. Because $a^{-1} \in H$, $a^{-1}K \in H/K$ and the subgroup is closed under inverses. Further, it satisfies all the criteria to be a subgroup of $G/K$.

Now we must show $H/K \trianglelefteq G/K$. Let $hK \in G/K$ and $gK \in G/K$. Because $G$ is a group $g^{-1} \in G$ and $g^{-1}K=(gK)^{-1} \in G/K$. So,
$$
\begin{align}
(gK)(hK)(gK)^{-1} &= (gK)(hK)(g^{-1}K) \\
&= (ghg^{-1})K. \\
\end{align}
$$
Because $H \trianglelefteq G$, $ghg^{-1} \in H$ by the [[Problem 5.73 MA-110|test for normal subgroups]]. So, $(gK)(hK)(gK)^{-1} \in H/K$, and by the test for normal subgroups, $H/K \trianglelefteq G/K$.