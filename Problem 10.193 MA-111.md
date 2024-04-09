---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.193 MA-111

> [!problem] Problem 10.193
> Prove Part 3a of [[Theorem 10.11 MA-111|Theorem 10.11]] (that the number of Sylow $p$-subgroups of $G$ is congruent to 1 modulo $p$) as follows: Let $K$ be a Sylow $p$-subgroup of $G$, and let $X$ be the set of all Sylow $p$-subgroups of $G$. By Part 2, $K$ acts on $X$ by conjugation: $\phi_{k}(H)=kHk^{-1}$. Show that this action has only one fixed point, then apply [[Problem 10.182 MA-111 (Presenter)|Problem 182]]

Let $K$ be a Sylow $p$-subgroup of a group $G$, and let $X$ be the set of all Sylow $p$-subgroups of $G$. By Part 2, $K$ acts on $X$ by conjugation: $\phi_{k}(H)=kHk^{-1}$. The fixed points are the Sylow $p$-subgroups $H$ such that $kHk^{-1}=H$ for all $K$. By absorption, $K$ must be a fixed point. I'm not sure how to show that $K$ is the *only* fixed point.

Assuming that we are able to show there is only one fixed point, the mod-p class equation tells us the order of $X$, the number of Sylow $p$-subgroups, must be congruent to 1 mod $p$.
