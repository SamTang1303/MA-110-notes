---
aliases:
  - The First Isomorphism Theorem
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 3.4 MA-110|kernel]]"
  - "[[Definition 3.3 MA-110|Definition of the image of a function]]"
---
# Problem 5.84 MA-110

> [!problem] Problem 5.84
> Prove that the map defined in [[Problem 5.82 MA-110|Problem 82]] is one-to-one. Conclude that if $\phi:G\longrightarrow H$ is a homomorphism of groups, then $G/\ker(\phi)\simeq \phi(G)$.

Let $\phi:G \longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]] of groups, and let $K=\ker(\phi)$. Define the map $\psi:G/K\longrightarrow H$ by the formula $\psi(aK)=\phi(a)$.

Let $aK,bK \in G/\ker(\phi)$ and suppose $\psi(aK)=\psi(bK)$. By definition of $\psi$, this implies
$$
\phi(a)=\phi(b).
$$
Then, by [[Problem 4.68 MA-110|Problem 68]], $b \in aK$. Because $b \in bK$, $aK$ and $bK$ are not disjoint and so by [[Problem 4.61 MA-110|Problem 61]], $aK=bK$. Thus, by definition, $\psi$ is one-to-one.

For any element $\phi(a) \in \phi(G)$, $\psi(aK)=\phi(a)$. So if we limit the codomain of $\psi$ to $\phi(G)$, it is onto as well as one-to-one. Further, we showed $\psi$ homomorphism in [[Problem 5.83 MA-110|Problem 83]], implying it is an [[Definition 3.1.2 MA-110|isomorphism]], and $G/\ker(\phi)\simeq \phi(G)$.