---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.168 MA-110

> [!problem] Problem 9.168
> Prove that if $F$ is a field and $p(x) \in F[x]$ is an irreducible polynomial, then $F[x]/(p(x))$ is a field.

Let $F$ be a field and $p(x) \in F[x]$ be an irreducible polynomial. Let $f(x) + (p(x)) \in F[x]/(p(x))$ such that it is not the additive identity (in other words, $f(x)\notin (p(x))$). Because $p(x)$ is irreducible and $f(x)$ is not a multiple of $p(x)$, they must be relatively prime. Thus, by [[Problem 8.138 MA-110|Problem 138]], $a(x)f(x)+b(x)p(x)=1$ for some $a(x),b(x) \in F[x]$. Therefore $a(x)f(x) = 1-b(x)p(x)$ and
$$
\begin{align}
\Big(a(x)+(p(x)\Big)\Big(f(x)+(p(x)\Big) &= a(x)f(x)+(p(x))\\
&= 1-b(x)p(x)+(p(x))\\
&=1+(p(x)). && \text{absorption}
\end{align}
$$
Thus $a(x)+(p(x))=\Big(f(x)+(p(x))\Big)^{-1}$ and $F[x]/(p(x))$ is a field.
