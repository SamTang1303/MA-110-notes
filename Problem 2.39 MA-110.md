---
aliases:
  - U groups are groups
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.39 MA-110

> [!problem] Problem 2.39
> 1. Prove that $U(n)$ is a group under multiplication modulo $n$.
> 2. A group of the form $U(n)$ is called a "$u$-group". Are all $U$-groups cyclic? Prove or disprove.

1 ) For some $n \in \mathbb{N}$, consider $U(n)$. 

$1 \cdot1=1$, so $1 \in U(n)$ and $1 \cdot a=a$ for all $a \in U(n)$. Therefore $U(n)$ has an identity element.

By definition, every element of $U(n)$ has an inverse, so this criterion is trivially satisfied.

Let $a,b \in U(n)$. By definition of $U(n)$ $a^{-1}$ and $b^{-1}$ exist.
$$
(ab)(b^{-1}a^{-1}) = a(bb^{-1})a^{-1}=(ae)a^{-1}=aa^{-1}=1
$$
This verifies that $ab$ and $b^{-1}a^{-1}$ are inverses of each other and therefore both in $U(n)$. Thus, $U(n)$ is closed under multiplication and thus it is a valid binary operator.

Finally, multiplication in $U(n)$ is clearly associative because it is the same as multiplication in $\mathbb{Z}_{n}$. Therefore, $U(n)$ is a group.

2 ) We will disprove by counterexample.

Consider $U(8)=\{ 1,3,5,7 \}$. Every element is its own inverse. Thus, none of the elements can be generators, and the group is not cyclic.
