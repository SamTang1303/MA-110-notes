---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 6.100 MA-110

> [!problem] Problem 6.100
> Prove that the image of a ring homomorphism is a subring of the codomain. That is, if $\phi:R \longrightarrow S$ is a ring homomorphism, and $\phi(R)=\{ \phi (r) : r \in R \}$, then $\phi(R)$ is a [[Problem 6.96 MA-110|subring]] of $S$.

Let $\phi:R \longrightarrow S$ be a ring homomorphism.

First, note that because a ring homomorphism is also a group homomorphism from on $\langle R,+\rangle$. So, it $\phi(R)$ must contain the identity of $S$ ([[Problem 3.44 MA-110|Problem 44]]), and be closed under taking inverses (definition of a subgroup.)

Thus, the only thing left to show is that $\phi(R)$ is closed under both addition and multiplication. Let $\phi(a),\phi(b) \in \phi(R)$. Because $\phi$ is a ring homomorphism,
$$
\phi(a)+\phi(b) = \phi(a+b) \text{ and } \phi(a)\phi(b) = \phi(ab).
$$
Because $a+b$ and $ab$ are elements of $G$, $\phi(a+b)$ and $\phi(ab)$ are elements of $\phi(G)$, thus making it closed under addition and multiplication.

Therefore, $\phi(R)$ must be a subring of $S$.