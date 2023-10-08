---
aliases:
  - cyclic subgroups are abelian
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.37 MA-110

> [!problem] Problem 2.37
> 1. Prove that every cyclic group is abelian.
> 2. State the contrapositive of the statement in part 1, and use it to find an example of a group that isn't cyclic.
> 3. Give a counterexample to show that the converse of the statement in part 1 is false.

1 ) Let $G$ be a cyclic group with generator $g$ (i.e. $G=\langle g\rangle$.) 

Let $a, b \in G$. Because $G$ is cyclic, for some $n,m \in \mathbb{Z}$, $a=g^{n}$ and $b=g^{m}$.
$$
ab = g^{n}g^{m}= g^{n+m}=g^{m+n} = g^{m}g^{n} = ba.
$$
The second equality is justified by [[Problem 1.16 MA-110|Problem 16]]. Thus, $ab=ba$ and $G$ is abelian.

2 ) The contrapositive of the statement in part 1 is: If a group is not abelian, then it is not cyclic. That proves that $D_{3}$ cannot be cyclic, because we know it is not commutative.

3 ) The converse of the statement in part 1 is: If a group is abelian, then it is cyclic. We will prove this false by counterexample.

Consider the subgroup of $S_{4}$.
$$
G = \{(1), (1\,2), (3 \, 4), (1\,2)(3\, 4) \}.
$$
Because it is a subgroup it is also a group. Clearly, the group is commutative. Yet every element is its own inverse, so none of them can be the generator for the group. Thus, we have found a group that is abelian,  but not cyclic.
