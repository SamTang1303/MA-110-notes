---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.80 MA-110

> [!problem] Problem 5.80
> Let $G$ be a group with $H \trianglelefteq G$. Prove or disprove: If $G/H$ is abelian, then $G$ is abelian.

This can be trivially disproved if we use $G \trianglelefteq G$. Then $G/G=\{ G \}$, which is trivially abelian. This would imply every group is abelian, which is false. But, we can also disprove it for a [[Definition 5.2 MA-110|normal subgroup]] that is not the entire group.

Let $G=D_{3}$ and $H=\{\rho_{0},\rho_{1},\rho_{2}\}$.
$$
\begin{align}
\rho_{0}H&=H=H\rho_{0} \\
\rho_{1}H&=H=H\rho_{1} \\
\rho_{2}H&= H =H\rho_{2} \\
\mu_{1}H&= \mu_{1}H=H\mu_{1} \\
\mu_{2}H&= \mu_{1}H=H\mu_{2} \\
\mu_{3}H&= \mu_{1}H=H\mu_{3}. \\
\end{align}
$$
As we can see, $H$ is, in fact, a [[Definition 5.2 MA-110|normal subgroup]] of $G$. Further, $G/H$ only has two elements and must be [[Definition 3.1.2 MA-110|isomorphic]] to $\mathbb{Z}_{2}$ and therefore abelian. Because $D_{3}$ is not abelian, this disproves the problem statement.