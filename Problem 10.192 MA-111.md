---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.192 MA-111

> [!problem] Problem 10.192
> Prove [[Theorem 10.11 MA-111|Part 2 of Theorem 10.11]] as follows: Let $H$ and $K$ be Sylow $p$-subgroups of $G$, and consider the action of $H$ on the cosets of $K$ in $G$: $\phi_{h}(gK)=hgK$. Apply [[Problem 10.182 MA-111 (Presenter)|Problem 182]] to show that this action has a fixed point. Then show that if $xK$ is this fixed point, then $x^{-1}Hx=K$.

Let $H$ and $K$ be Sylow $p$-subgroups of $G$ with $\left| G \right|=p^{n}m$ such that $p\nmid m$, and consider the action of $H$ on the cosets of $K$ in $G$: $\phi_{h}(gK)=ghK$. The mod $p$ class equation says that
$$
\left| X \right|  = \frac{p^{n}m}{p^{n}} =m\equiv \left| X_{H} \right| \text{ mod }p.
$$
Because $p$ does not divide $m$, $m$ is not congruent to $0$ mod $p$. Thus there must be at least one fixed point.

Let $xK$ be such a fixed point. Then $hxK=xK$ for all $h$. Thus $hx=xk$ ([[Problem 4.59 MA-110|Problem 59]]) for some $k \in K$. So, $x^{-1}hx=k \in K$. Because this was done for an arbitrary $h \in H$, $x^{-1}Hx \subseteq K$. Further, because $\left| x^{-1}Hx \right|=\left| H \right|=\left| K \right|$, it must be true that $x^{-1}Hx=K$.
