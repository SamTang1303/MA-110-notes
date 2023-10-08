---
aliases:
  - group elements have a unique inverse
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.12 MA-110

> [!problem] Problem 1.12
> Let $G$ be a group, and let $a \in G$. Prove that $a$ has a unique inverse.

*Proof.* Let $\langle G,*\rangle$ be a group with $a \in G$ and $b,c$ as inverses of $a$. Further, let $e$ be the identity of the group.
$$
\begin{align}
e &= a *b\\
c*e &= c*(a*b)\\
c &= (c*a)*b\\
c &= e*b\\
c &= b
\end{align}
$$
