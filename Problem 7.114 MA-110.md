---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.114 MA-110

> [!problem] Problem 7.114
> Let $R$ be a ring. Prove that the set $\{ 0 \}$ is an ideal of $R$, and that $R/\{ 0 \}\simeq R$.

Let $R$ be a ring. Consider the set $\{ 0 \}$. The group $\langle \{ 0 \}, +\rangle$ is the trivial group, and therefore abelian. For any $r \in R$, $0 \cdot r,r \cdot0 =0$ by [[Problem 6.92 MA-110|Problem 92]]. Thus $\{ 0 \}$ is an ideal of $R$.

Consider the map $\phi:R \longrightarrow R$ such that $\phi$ is the identity function. This is trivially a ring homomorphism. Then the kernel of the function is only $\{ 0 \}$, so [[Problem 7.113 MA-110|The First Ring Isomorphism Theorem]] says
$$
R/\{ 0 \} = R/\ker(\phi) \simeq \phi(R) =R.
$$
