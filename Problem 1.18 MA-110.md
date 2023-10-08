---
aliases:
  - cancellation
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.18 MA-110

> [!problem] Problem 1.18
> Prove or disprove, as appropriate: Suppose $G$ is a group, with $a,b,$ and $c$ in $G$. If $ac=bc$, then $a=b$.

*Proof.* Let $G$ be a group with $a,b,c \in G$. Further, let $ac=bc$. Because $G$ is a group, we know $c^{-1}$ exists.
$$
\begin{align}
ac&= bc\\
(ac)c^{-1}&= (bc)c^{-1}\\
a(cc^{-1})&= b(cc^{-1})\\
a &= b
\end{align}
$$
