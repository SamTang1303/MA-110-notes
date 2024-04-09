---
aliases:
  - class equation
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.182 MA-111 (Presenter)

> [!problem] Problem 10.182
> If $G$ is a group that acts on a finite set $X$, explain why **class equation**
> $$
> \left| X \right| =\left| X_{G} \right|  + \sum\limits\left| Gx_{i} \right| 
> $$
> holds, where the sum is taken over a set $x_{i}$ of representatives of orbits of size greater than 1. If in addition, $\left| G \right|=p^{n}$ for some prime $p$, explain why $\left| X \right| \equiv \left| X_{G} \right|$ mod $p.$

^9f3428

For any fixed point in $X_{G}$, by definition its orbit will be of size one. So we could rewrite $\left| X_{G} \right|$ as $\sum\limits\left| Gx_{i} \right|$, where the sum is taken over a set $x_{i}$ of representatives of orbits of size 1. Thus we could rewrite the class equation
$$
\left| X \right| =\sum\limits \left| Gx_{i} \right| 
$$
where the sum is taken over a set $x_{i}$ or representatives of *all* orbits. Because the orbits of $x$ partition $X$, this equation is clearly true.

If $\left| G \right|=p^{n}$ for some prime $p$, then the [[Theorem 10.10 MA-111|Orbit-Stabilizer Theorem]] implies for all $Gx_{i}$ where $\left| Gx_{i} \right| >1$, $\left| Gx_{i} \right|$ must be a multiple of $p$. Thus in the class equation, every term in $\sum\limits\left| Gx_{i} \right|$ will be a multiple of $p$, i.e., $\equiv 0$ mod $p$.
