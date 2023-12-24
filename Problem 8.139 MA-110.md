---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.139 MA-110

> [!problem] Problem 8.139
> The following statements establish a proof of the [[Theorem 8.9 MA-110|above theorem]]. Give a reason for each statement (cite previous problems, or give a brief justification).
> 1. The set $I$ of all linear combinations of $f(x)$ and $g(x)$ is an ideal of $F[x]$.
> 2. The ideal $I$ can be written as $I=(d(x))$ for some monic polynomial $d(x)$.
> 3. There exist polynomials $a(x)$ and $b(x)$ in $F[x]$ such that $d(x)=a(x)f(x)+b(x)g(x)$.
> 4. The polynomial $d(x)$ is a common divisor of $f(x)$ and $g(x)$.
> 5. If $c(x) \in F[x]$ is a polynomial such that $c(x)\mid f(x)$ and $c(x)\mid g(x)$, then $c(x)\mid d(x)$.

1. [[Problem 8.132 MA-110|Problem 132]]
2. [[Problem 8.128 MA-110|Problem 128]] and [[Problem 8.129 MA-110|Problem 129]]
3. $d \in I$ and therefore can be represented as a linear combination of $f$ and $g$.
4. Both $f$ and $g$ are in $(d)$, so they must both be multiples of $d$. I.e., $d$ is a common divisor of them both.
5. If $c$ divides both $f$ and $g$, then for some $p,q \in F[x]$, $d=apc+bqc=(ap+bq)c$ and $c$ divides $d$.
