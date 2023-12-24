---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Theorem 8.9 MA-110]]"
---
# Problem 8.149 MA-110

> [!problem] Problem 8.149
> Let $f$ and $g$ in $F[x]$, a polynomial ring over a field, and suppose that $r_{k}$ is the last non-zero remainder produced by the Euclidean algorithm. Prove that $r_{k}(x)=ud(x)$, where $u \in F$ and $d =\gcd(f,g)$.

Let $f$ and $g$ in $F[x]$, a polynomial ring over a field, and suppose that $r_{k}$ is the last non-zero remainder produced by the Euclidean algorithm. Let $d=\gcd(f,g)$.

By [[Definition 8.8 MA-110|definition]] $d$ divides both $f$ and $g$. [[Problem 8.147 MA-110|Problem 147]] implies $d$ divides $r_{k}$.

From [[Problem 8.148 MA-110|Problem 148]], we know $r_{k}$ divides $r_{1}$ and $r_{2}$. So,
$$
\begin{align}
g&=q_{2}ur_{k} + vr_{k} && \text{for some }u,v \in  F[x]; \text{ second step of Euclidean algorithm} \\
&=(q_{2}u+v) r_{k}.
\end{align}
$$
Thus $g$ is also a multiple of $r_{k}$. Knowing that $g$ and $r_{1}$ are multiples of $r_{k}$, we can make an identical argument to show $f$ is also a multiple of $r_{k}$.
$$
\begin{align}
d &= af + bg && \text{for some }a,b \in F[x]; \text{Theorem 8.9} \\
&= apr_{k} + bqr_{k} && \text{for some }p,q \in  F[x] \\
&= (ap+bq)r_{k}.
\end{align}
$$
Thus $r_{k}$ divides $d$. By [[Problem 8.135 MA-110|Problem 135]] $r_{k}=ud$ where $u$ is a unit of $F[x]$. As shown in [[Problem 8.131 MA-110|Problem 131]], this implies $u$ is a constant polynomial, (i.e. in $F$.)
