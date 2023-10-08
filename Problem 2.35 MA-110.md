---
aliases:
  - Cyclic subgroups are subgroups
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.35 MA-110

> [!problem] Problem 2.35
> Let $G$ be a group, and let $g$ be a fixed element of $G$. Define $H=\{ g^{n} : n \in \mathbb{Z}  \}$. Prove that $G$ is a subgroup of $G$.

Let $G$ be a group with identity $e$ and let $g$ be a fixed element of $G$. Consider the set $H=\{ g^{n}:n \in \mathbb{Z} \}$.

$g^{0}$ is defined to be the identity, so clearly $e \in H$.

Let $a, b \in H$. We know for some $m,n \in \mathbb{Z}$, $a=g^{n}$ and $b=g^{m}$.
$$
\begin{align}
ab &= g^{n}g^{m}\\
&= g^{n+m} && \text{By Problem 16}
\end{align}
$$
$n+m$ is clearly still an integer, so $ab \in H$, and $H$ is closed under the group multiplication.

Let $x \in G$. For some $n \in \mathbb{Z}$, $x=g^{n}$. $x^{-1}=g^{-n}$. Because $-n$ is still an integer, $x^{-1} \in H$. Therefore $H$ is closed under inverses and satisfies all the criteria for a subgroup.
