---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.173 MA-111

> [!problem] Problem 173
> Let $\phi: \mathbb{Z}_{12} \longrightarrow\mathbb{Z}_{3}$ be the homomorphism determined by $\phi(1)=2$. Illustrate the correspondence between cosets and group elements given by the First Isomorphism Theorem when it is applied to $\phi$.

Let $\phi: \mathbb{Z}_{12} \longrightarrow\mathbb{Z}_{3}$ be the homomorphism determined by $\phi(1)=2$. The kernel of $\phi$ will be $\{ 0, 3, 6, 9 \}$. Thus, [[Problem 5.84 MA-110|The First Isomorphism Theorem]] says that
$$
\mathbb{Z}_{12}/\{ 0,3,6,9 \} \simeq \mathbb{Z}_{3}.
$$
It will map the elements in the following manner:
$$
\begin{align}
\{ 0,3,6,9 \} \mapsto 0 \\
\{ 1,4,7,10 \} \mapsto 2 \\
\{ 2,5,8,11 \} \mapsto 1.
\end{align}
$$
