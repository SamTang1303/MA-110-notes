---
aliases:
  - Inverses preserve groups
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.32 MA-110

> [!problem] Problem 2.32
> Prove that if $H$ and $K$ are subgroups of a group $G$, then their intersection $H\cap K$ is a subgroup of $G$.

Let $H$ and $K$ be subgroups of a group $G$. Consider the set $H\cap K$ with operation defined similarly to $G$.

$G$ is a group, so it must have an identity element $e$. $H$ and $K$ are both subgroups, so by definition they must also contain $e$. Thus $e \in H\cap K$.

Let $x,y \in H\cap K$. By definition of the intersection operator, $x,y \in H$ *and* $x,y \in K$. $H$ is a subgroup, it is closed under its operation, and $xy \in H$. Similarly, $xy \in K$. Thus,
$xy \in H\cap K$, implying $H\cap K$ is closed under the operation of $G$.

Let $z \in H\cap K$ (i. e. $z \in H$ and $z \in K$.) By the definition of a subgroup $z^{-1} \in H$ and $z^{-1} \in K.$ Therefore, $z^{-1} \in H\cap K$ and $H\cap K$ is closed under taking inverses.

Thus $H\cap K$ fulfill all the requirements for a subgroup of $G$.
