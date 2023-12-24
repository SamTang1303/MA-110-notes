---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.147 MA-110

> [!problem] Problem 8.147
> Let $f$ and $g$ in $F[x]$, a polynomial ring over a field, and suppose that $c(x)$ is a common divisor of $f$ and $g$. Prove that $c$ divides all of the remainders $r_{1},\dots ,r_{k}$ produced by the Euclidean algorithm.

We will again prove by strong induction.

**Base case**: $n=1$
$$
\begin{align}
r_{1} &= f-q_{1}g \\
&= uc - q_{1}vc && \text{for some }u,v \in  F[x] \\
&= (u-q_{1}v)c.
\end{align}
$$
Thus $c$ divides $r_{1}$.

Suppose $c$ divides $r_{n}$ for all $n \in 1,\dots k-1$.
$$
\begin{align}
r_{n-1} &= q_{n+1}r_{n} + r_{n+1} \\
r_{n-1}-q_{n+1}r_{n} &= r_{n+1} \\
uc - q_{n+1}vc &= r_{n+1} && \text{for some }u,v \in  F[x] \\
(u-q_{n+1}v)c &= r_{n+1}.
\end{align}
$$
Thus, $c$ divides $r_{n+1}$.

By strong induction, all $r_{1},\dots,r_{k}$ are multiples of $c$.