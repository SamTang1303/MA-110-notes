---
aliases:
  - If a group is cyclic, then its quotient group is as well
tags:
  - batch/school/class/ma110
  - batch/math
---
# Problem 5.78 MA-110

> [!problem] Problem 5.78
> Let $G$ be a group with $H\trianglelefteq G$. Prove or disprove: If $G$ is cyclic, then $G/H$ is cyclic.

Let $G$ be a group with $H\trianglelefteq G$ such that $G$ is cyclic and can be written as $\langle g_{0}\rangle$ for some $g_{0} \in G$. Let the coset $g_{0}$ falls in be denoted by $G_{0}$.

Let $A \in G/H$ with representation $aH=A$ where $a \in G$. By assumption, $a=g_{0}^{n}$ for some $n \in \mathbb{Z}$. Because $g_{0} \in G_{0}$, $g_{0}^{n} \in G_{0}^{n}$ by the definition of coset multiplication. Therefore, $a \in G_{0}^{n}$. Therefore, $A$ and $G_{0}^{n}$ are not disjoint, and by [[Pre-Work Problems 60 Through 63 MA-110#^0d748d|Problem 61]], $A=G_{0}^{n}$. Thus, every element can be represented as a power of $G_{0}$, and $G/H=\langle G_{0}\rangle$. 