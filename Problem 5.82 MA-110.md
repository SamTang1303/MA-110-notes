---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 3.4 MA-110|kernel]]"
---
# Problem 5.82 MA-110

> [!problem] Problem 5.82
> Let $\phi:G \longrightarrow H$ be a homomorphism of groups, and let $K=\ker(\phi)$. In Problem 71, you proved that $K\trianglelefteq G$. Define a map $\psi:G/K\longrightarrow H$ by the formula $\psi(aK)=\phi(a)$. Prove that this map is **well defined**. That is, prove that it doesn't depend on the choice of representative for the coset $aK$: Show that if $aK=bK$, then $\psi(aK)=\psi(bK)$.

Let $\phi:G \longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]] of groups, and let $K=\ker(\phi)$. Define the map $\psi:G/K\longrightarrow H$ by the formula $\psi(aK)=\phi(a)$.

Let $a,b \in G$ and suppose that $aK=bK$. By definition of $\psi$, $\psi(aK)=\phi(a)$ and $\psi(bK)=\phi(b).$ Because $b \in bK$ and $bK=aK$, $b \in aK$. By [[Problem 4.68 MA-110|Problem 68]], it must then be true that $\phi(b)=\phi(a)$ and $\psi(bK)=\psi(aK)$, completing the proof.