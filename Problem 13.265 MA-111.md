---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.265 MA-111

> [!problem] Problem 13.265
> Use Theorem 13.6 and your above examples of solvable groups to prove that every polynomial of degree 2,3, or 4 over $\mathbb{Q}$ is solvable by radicals.

Let $p(x) \in \mathbb{Q}[x]$ be a polynomial of degree less than 5 and $K$ the splitting field of $f(x)$ over $\mathbb{Q}$. [[Problem 12.231 MA-111|Problem 231]] says that $\text{Gal}(K/\mathbb{Q})$ is isomorphic to some subgroup of $S_{4}$, call it $H$. If $H=S_{3}, S_{4},$ or $D_{4}$, then it is solvable by [[Problem 13.262 MA-111|262]] and [[Problem 13.263 MA-111|263]] respectively. By the proof of 263, we also know that if $H=A_{4}$, then it is solvable. The only other subgroups of $S_{4}$ are of order $4$ or less, implying they are abelian and therefore solvable. Thus, by Theorem 13.6, all polynomials of degree less than 5 are solvable by radicals.
