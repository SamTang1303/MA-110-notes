---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.151 MA-110

> [!problem] Problem 9.151
> Let $f(x) \in F[x]$, where $F$ is a field. Let $a \in F$, and let $r(x)$ be the remainder of [[Theorem 8.6 MA-110|The Division Algorithm]] applied to $f(x)$ and $g(x)=x-a$. Show that $r(x)=f(a)$.

Let $f(x) \in F[x]$, where $F$ is a field. Let $a \in F$, and let $r(x)$ be the remainder of the division algorithm applied to $f(x)$ and $g(x)=x-a$.

Because $\deg(r)<\deg(g)=1$, $r$ must be a constant term. The division algorithm gives.
$$
\begin{align}
f(x)=q(x)(x-a) + r && \text{for some }q(x) \in  F[x].
\end{align}
$$
Evaluating at $x=a$ yields
$$
f(2)=q(2)(2-2)+r=q(2) \cdot 0+r = r.
$$
