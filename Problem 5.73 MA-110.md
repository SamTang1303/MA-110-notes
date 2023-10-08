---
aliases:
  - test for normal subgroups
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 5.2 MA-110|normal subgroup]]"
---
# Problem 5.73 MA-110

> [!problem] Problem 5.73
> Let $H$ be a subgroup of a group $G$. Prove that $H\trianglelefteq G$ if and only if the following condition holds: for all $h \in H$ and for all $g \in G$, $ghg^{-1}$ is in $H$.

Let $H$ be a subgroup of a group $G$. First, suppose $H\trianglelefteq G$ and let $h \in H$ and $g \in G$. Because $H\trianglelefteq G$, there exists some $h' \in H$ such that $gh=h'g$. Thus,
$$
ghg^{-1} =h'g g^{-1} = h' \in  H.
$$

Now, suppose for all $h \in H$ and $g \in G$, $ghg^{-1} \in H$. Let $g_{0} \in G$ be given, and suppose $x \in g_{0}H$. Then $x=g_{0}h$ for some $h \in H$. Right multiplying by $g_{0}^{-1}g_{0}$ yields
$$
\begin{align}
x(g_{0}^{-1}g_{0}) &= g_{0}h(g_{0}^{-1}g_{0}) \\
x&= (g_{0}hg_{0}^{-1})g_{0} \\
x &= h'g_{0}. && \text{for some } h' \in  H
\end{align}
$$
Therefore, $x \in Hg_{0}$ and $g_{0}H\subseteq Hg_{0}$. We can argue similarly to show $Hg_{0}\subseteq g_{0}H$. Therefore $g_{0}H=Hg_{0}$ and $H\trianglelefteq G$.
