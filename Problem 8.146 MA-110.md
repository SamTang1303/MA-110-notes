---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.146 MA-110

> [!problem] Problem 8.146
> Let $I=(f,g)$ be the ideal of $F[x]$ consisting of all linear combinations of $f$ and $g$. Prove that, in the Euclidean algorithm, the remainders
> $$
> r_{1},r_{2},r_{3},\dots,r_{k}
> $$
> are all elements of $I$.

Let $I=(f,g)$ be the ideal of $F[x]$ consisting of all linear combinations of $f$ and $g$. We seek to prove the Euclidean algorithm, the remainders
$$
r_{1},r_{2},r_{3},\dots,r_{k}
$$
are all elements of $I$. We will do this by strong induction.

**Base case**: $m=1$
$$
r_{1} = f-q_{1}g.
$$
Therefore, $r_{1}$ is a linear combination of $f$ and $g$ and is in $I$.

Suppose for some given $m \in \{ 1,\dots, k-1\}$, $r_{1},\dots,r_{m} \in I$. The Euclidean algorithm tells us
$$
\begin{align}
r_{m-1} &= q_{k+1}r_{m} + r_{m+1} \\
r_{m-1} - q_{k+1}r_{m} &= r_{m+1.}
\end{align}
$$
Because $r_{m-1}$ and $r_{m}$ are in $I$, by the properties of [[Definition 6.3 MA-110|ideals]], $r_{m+1}$ must be as well.

Thus, by strong induction, $r_{1},\dots r_{k} \in I$.
