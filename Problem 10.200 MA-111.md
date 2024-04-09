---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.200 MA-111

> [!problem] Problem 10.200
> Consider the action of $G$ on itself by conjugation: $\phi_{g}(x)=gxg^{-1}$.
> 1. Show that the fixed point set $G_{G}$ of this action is the center $Z(G)$.
> 2. Let $p$ be prime and $n \in \mathbb{N}$. Use the class equation to show that every group of order $p^{n}$ has nontrivial center.

Consider the action of $G$ on itself by conjugation: $\phi_{g}(x)=gxg^{-1}$.
1 ) Let $x \in G_{G}$. Then for all $g \in G$, $gxg^{-1}=x \iff gx=xg$. Thus $x \in Z(G)$. All the implications used in this argument are biconditional, so we can make the converse argument to show $x \in Z(G) \implies x \in G_{G}$. Thus, $G_{G}=Z(G)$.

2 ) Let $p$ be prime and $n \in \mathbb{N}$. Consider the group action considered in part 1). [[Problem 10.182 MA-111 (Presenter)|The class equation]] says
$$
\left| Z(G) \right| = \left| G_{G} \right|  \equiv  p^{n} \equiv0 \text{ mod }p.
$$
Because there must be at least one element in the center, the identity, there must be a (nonzero) multiple of $p$ number of elements in the center.
