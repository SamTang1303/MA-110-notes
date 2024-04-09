---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.216 MA-111

> [!problem] Problem 11.216
> Let $E$ be a finite extension of a field $F$, and let $p(x) \in F[x]$ be irreducible over $F$ and have degree that is not a divisor of $[E:F]$. Show that $p(x)$ has no zeros in $E$.

Let $E$ be a finite extension of a field $F$, and let $p(x) \in F[x]$ with degree $p$ be irreducible over $F$ and have degree that is not a divisor of $[E:F]$. Suppose to the contrary that $p(x)$ has a zero, $\alpha$, in $E$. Then the Algebraic Extension Theorem says that $F(\alpha)$ will have a basis $\{ 1,\alpha,\alpha^{2},\dots,\alpha^{p-1} \}$. Thus $F(\alpha)\subseteq E$. By the Degree Multiplication Theorem, $[E:F]=[E:F(\alpha)][F(\alpha):F]=[E:F(\alpha)]p$. This contradicts our initial assumptions, so $p$ cannot have any zeros in $E$.
