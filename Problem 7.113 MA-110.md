---
aliases:
  - The First Ring Isomorphism Theorem
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.113 MA-110

> [!problem] Problem 7.113
> Review your solution to Problem 84 and the discussion at the beginning of section 5.3. Then state and prove the first isomorphism theorem for rings.

> [!definition] The First Isomorphism Theorem for rings
> Let $R$ and $S$ be a rings. If $\phi:R \longrightarrow S$ is a ring homomorphism, then
> $$
> R/\ker(\phi) \simeq \phi(R).
> $$

*Proof.* Let $R,S$ be rings, $\phi:R \longrightarrow S$ a ring homomorphism, and $I=\ker(\phi )$. Note $I$ is an ideal, as proved in [[Problem 6.101 MA-110|Problem 101]]. 

Define the map $\psi:R/I \longrightarrow S$ by the formula $\psi(a + I)=\phi(a)$. Note that all ideals are subgroups of abelian groups, so $\langle I,+\rangle$ is a normal subgroup of $\langle R,+\rangle$. Let $a+I,b+I \in R/I$. Our work in [[Problem 5.82 MA-110|Problem 82]] guarantees $\psi$ is well defined, and our work in [[Problem 5.83 MA-110|Problem 83]] guarantees $\psi((a+I)+(b+I))=\psi(a+I)+\psi(b+I)$ for all $a,b \in R$. 
$$
\begin{align}
\psi((a+I)(b+I)) &= \psi(ab+I)&& \text{coset product}\\
&= ab \\
&= \psi(a+I)\psi(b+I).
\end{align}
$$
Therefore, $\psi$ is a ring homomorphism.

Let $a+I,b+I \in R/I$ and suppose $\psi(a+I)=\psi(b+I)$. By definition of $\psi$, this implies
$$
\phi(a)=\phi(b).
$$
Then, by [[Problem 4.68 MA-110|Problem 68]] ($\phi$ is also a group homomorphism from $\langle R,+\rangle \longrightarrow \langle S,+\rangle$ with kernel $I$), $b \in a + I$. Thus $a+I$ and $b+I$ are not disjoint and [[Problem 4.61 MA-110|Problem 61]] implies $a+I=b+I$. Thus, by definition, $\psi$ is one-to-one.

For any element $\phi(r) \in \phi(R)$, $r + I \in R/I$, and $\psi(r+I)=\phi(r)$. So, if we limit the codomain of $\psi$ to $\phi(R)$, it is onto.

We have now shown $\psi:R/\ker(\phi ) \longrightarrow \phi(R)$ is a [[Problem 6.97 MA-110|ring homomorphism]], one-to-one, and onto. Therefore it is a ring isomorphism and
$$
R/\ker(\phi) = \phi(R).
$$
