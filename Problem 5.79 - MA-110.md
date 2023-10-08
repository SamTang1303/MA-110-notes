---
aliases:
  - If a group is abelian, then its quotient group is as well
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.79 MA-110

> [!problem] Problem 5.79
> Let $G$ be a group with $H\trianglelefteq G$. Prove or disprove: If $G$ is abelian, then $G/H$ is abelian.

Let $G$ be a group with $H \trianglelefteq G$ such that $G$ is abelian. Let $A,B \in G/H$.
$$
\begin{align}
AB &= \{ ab: a \in  A, b \in  B \} &&\text{definition of set multiplication} \\
&= \{ ba: a \in  G, b \in  B \} && G\text{ is abelian, \& }a,b \in  G \\
&= BA.
\end{align}
$$
Thus, $G/H$ is abelian.
