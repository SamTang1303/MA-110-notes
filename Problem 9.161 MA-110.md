---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Problem 8.138 MA-110]]"
---
# Problem 9.161 MA-110

> [!problem] Problem 9.161
> Prove *Euclid's lemma* for polynomials: Let $F$ be a field, and suppose that $p(x) \in F[x]$ is irreducible. Prove that if $p(x)\mid a(x)b(x)$ for some $a(x),b(x) \in F[x]$, then $p(x)\mid a(x)$ or $p(x)\mid b(x)$.

Let $F$ be a field, and suppose that $p \in F[x]$ is irreducible. Let $p\mid ab$ for some $a,b \in F[x]$. Suppose that $p\nmid a$.

Because $p$ is irreducible, its only non-one factor is itself. Because $p\nmid a$, they must then be relatively prime. Then for some $f,g \in F[x]$,
$$
\begin{align}
1 &= fa+gp && \text{Problem 138}\\
b&= fab+gpb \\
b&= fqp+gbp && \text{for some }q \in  F[x]; p\mid ab \\
b&= (fq+gb) p.
\end{align}
$$
Therefore $p\mid b$. 
