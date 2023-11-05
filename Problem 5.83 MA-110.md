---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 3.4 MA-110|kernel]]"
---
# Problem 5.83 MA-110

> [!problem] Problem 5.83
> Prove that the map $\psi$ defined in [[Problem 5.82 MA-110|Problem 82]] is a homomorphism.

Let $\phi:G \longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]] of groups, and let $K=\ker(\phi)$. Define the map $\psi:G/K\longrightarrow H$ by the formula $\psi(aK)=\phi(a)$.

Let $aK,bK \in G/K$.
$$
\begin{align}
\psi((aK)(bK)) &= \psi((ab)K) && \text{coset multiplication} \\
&= \phi(ab) && \text{definition of }\psi \\
&= \phi(a)\phi(b) && \text{property of homomorphisms} \\
&= \psi(aK)\psi(bK) && \text{definition of }\psi
\end{align}
$$
Thus, by definition, $\psi$ is a homomorphism.