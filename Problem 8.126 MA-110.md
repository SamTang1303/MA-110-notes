---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Problem 8.121 MA-110]]"
---
# Problem 8.126 MA-110

> [!problem] Problem 8.126
> Suppose, in addition to the hypothesis of the division algorithm, that $R$ is an integral domain. Prove that the polynomials $q(x)$ and $r(x)$ are uniquely determined.

Suppose, in addition to the hypothesis of the division algorithm, that $R$ is an integral domain. Let $r_{1}(x)$ and $r_{2}(x)$ be remainders of degree $<n$ of $f(x)$ and $g(x)$. Then
$$
\begin{align}
f(x) &= q_{1}(x)g(x) +r_{1}(x) \\
&\text{and} \\
f(x) &= q_{2}(x)g(x) + r_{2}(x).
\end{align}
$$
for some quotients $q_{1}(x),q_{2}(x) \in R[x]$. Setting the equations equal to each other,
$$
\begin{align}
q_{1}(x)g(x) + r_{1}(x) &= q_{2}(x)g(x) + r_{2}(x) \\
r_{1}(x)-r_{2}(x) &= q_{2}(x)g(x) -q_{1}(x)g(x)\\
r_{1}(x)-r_{2}(x) &= g(x)(q_{2}(x) -q_{1}(x)).\\
\end{align}
$$
Note that because $r_{1}$ and $r_{2}$ must both have degree less than $g(x)$ by [[Theorem 8.6 MA-110|The Division Algorithm]], $r_{1}-r_{2}$ must as well. If $q_{2}-q_{1}$ is a non-zero polynomial ($g$ cannot be the zero polynomial), then
$$
\begin{align}
\deg(g)&>\deg(r_{1}-r_{2}) && \text{explained above}\\
&= \deg(g \cdot(q_{2}-q_{1})) && r_{1}-r_{2}=g \cdot (q_{2}-q_{1)}\\
&= \deg(g) + \deg(q_{2}-q_{1}). && \text{Problem 121} \\
&\text{and} \\
\deg(g) &> \deg(g) + \deg(q_{2}-q_{1}) \\
0 &> \deg(q_{2}-q_{1})
\end{align}
$$
This is impossible, meaning $q_{2}-q_{2}$ is the zero polynomial implying both $q_{1}=q_{2}$ and $r_{1}=r_{2}$. Therefore, if $R$ is an integral domain, the remainder and quotient of $f$ and $g$ are uniquely defined.
