---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.108 MA-110

> [!problem] Problem 7.108
> Let $I$ be an ideal of a ring $R$. Explain why $\langle I,+\rangle$ is a normal subgroup of $\langle R,+\rangle$. Which problems (that we have already proved) establish the following facts?
> 1. The cosets of $I$ in $R$ partition $R$.
> 2. The cosets of $I$ in $R$ have all the same size (or cardinality).
> 3. If $R$ is finite, than $\left| I \right|$ divides $\left| R \right|$.
> 4. For all $r,s \in R$, $(r+I)+(s+I)=(r+s)+I$.
> 5. The set $R/I$ is a group under coset addition.

Let $I$ be an ideal ring of $R$. By the definition of an ideal, $\langle I,+\rangle$ must be a subgroup of the commutative group $\langle R,+\rangle$. Therefore, $I$ is a subgroup of an abelian group, implying it is normal. Because $I$ is a normal subgroup, we can conclude the following.
1. [[Problem 4.61 MA-110|Problem 61]] implies the cosets of $I$ in $R$ partition $R$.
2. [[Problem 4.62 MA-110|Problem 62]] implies the cosets of $I$ in $R$ have all the same size.
3. [[Problem 4.64 MA-110|Lagrange's Theorem]] implies that $\left| I \right|$ divides $\left| R \right|$.
4. [[Problem 5.74 MA-110|Problem 74]] implies that for all $r,s \in R, (r+I)+(s+I)=(r+s)+I$ (the notation is translated to additive notation.)
5. [[Problem 5.76 MA-110|Problem 76]] implies that $R/I$ is a group under coset addition (again translating to additive terminology.)
