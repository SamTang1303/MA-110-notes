---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.148 MA-110

> [!problem] Problem 8.148
> Let $f$ and $g$ in $F[x]$, a polynomial ring over a field, and suppose that $r_{1},r_{2},\dots,r_{k}$ are the remainders produced by the Euclidean algorithm. Prove that $r_{k}$ divides all of the other remainders.

Let $f$ and $g$ in $F[x]$, a polynomial ring over a field, and suppose that $r_{1},r_{2},\dots,r_{k}$ are the remainders produced by the Euclidean algorithm. We will prove by strong induction.

**Base case**: $n=k-1$
The last step of the Euclidean algorithm guarantees that $r_{k-1}$ is a multiple of $r_{k}$.

Suppose all $r_{n},\dots,r_{k}$ are multiples of $r_{k}$ for $n \in \{ 2,\dots k-1 \}$.
$$
\begin{align}
r_{n-1} &=q_{n+1}r_{n} + r_{n+1} \\
&= q_{n+1}ur_{k} + vr_{k} && \text{for some }u,v \in  F[x] \\
&= (q_{n+1}u + v)r_{k}.
\end{align}
$$
Thus $r_{k}$ divides $r_{n-1}$. Strong induction implies that $r_{k}$ is then a divisor for all $r_{1},\dots,r_{k}$.
