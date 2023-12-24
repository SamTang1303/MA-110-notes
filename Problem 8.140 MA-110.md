---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.140 MA-110

> [!problem] Problem 8.140
> Let $f(x)$ and $g(x)$ be nonzero polynomials in $F[x]$, where $F$ is a field. Let $I=(f(x))$. Suppose that $g(x)+I$ is a unit in the quotient ring $F[x]/I$. Prove that $f(x)$ an $g(x)$ are relatively prime.

Let $f(x)$ and $g(x)$ be nonzero polynomials in $F[x]$, where $F$ is a field. Let $I=(f(x))$ and suppose that $g(x)+I$ is a unit in the quotient ring $F[x]/I$.

Because $g(x)+I$ is a unit, for some $c(x)+I \in F[x]/I$
$$
(g(x)+I)(c(x)+I)=g(x)c(x)+I=1+I.
$$
This implies $g(x)c(x) \in 1+I$ and $g(x)c(x)=f(x)p(x)+1$ for some $p(x) \in F[x]$. This can be rewritten as
$$
g(x)c(x)+(-f(x)p(x))=1.
$$
By [[Problem 8.138 MA-110|Problem 138]] $g$ and $f$ are relatively prime.
