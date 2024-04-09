---
aliases:
  - the bigger the group, the smaller the fixed field
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
related:
  - "[[Definition 12.2 MA-111|Definition of Galois Groups]]"
---
# Problem 12.227 MA-111

> [!problem] Problem 12.227
> Explain why $\text{Gal}(E/F)$ is a group. If $F\subseteq E\subseteq K$ is a tower of fields, explain why $\text{Gal}(K/E)$ is a subgroup of $\text{Gal}(K/F)$.

Let $F$ and $E$ be fields such that $F\subseteq E$. We will show $G=\text{Gal}(E/F)$ to be a group under function composition.

Let $f,g \in G$. Because the composition of two isomorphisms is still an isomorphism, $f \cdot g=f\circ g$ and $g  \cdot f = g \circ f$ are both automorphisms as well. Furthermore, composing two functions that fix $F$ will clearly result in a function that fixes $F$. Therefore, function composition is a valid binary operator on $G$.
1. The identity function is an automorphism that fixes every element.
2. Function composition is associative.
3. Isomorphisms are bijections so they have inverses, and their inverses are isomorphisms. Thus $f^{-1}$ exists and is an automorphism.
Thus, $\text{Gal}(E/F)$ satisfies all the criteria for a group.

Let $K$ be an extension field of $E$. For the same reason given above, $\text{Gal}(K/E)$ and $\text{Gal}(K/F)$ will be groups. Furthermore, any function $f \in \text{Gal}(K/E)$ will also be an automorphism from $F\longrightarrow K$. Therefore $f \in \text{Gal}(K/F)$, and $\text{Gal}(K/E)\subseteq \text{Gal}(K/F)$. Thus $\text{Gal}(K/E) \leq  \text{Gal}(K/F)$.
