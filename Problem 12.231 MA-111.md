---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 12.231 MA-111

> [!problem] Problem 12.231
> Suppose that $p(x) \in F[x]$ is a polynomial of degree $n$, and that its roots $\alpha_{1},\alpha_{2},\dots,\alpha_{n}$ are all distinct. Explain why $\text{Gal}(F(\alpha_{1},\alpha_{2}, \dots,\alpha_{n})/F)$ is isomorphic to a subgroup of $S_{n}$.

As shown in [[Problem 12.229 MA-111]], the automorphisms of $F(\alpha_{1},\alpha_{2},\dots,\alpha_{n})$ that fix $F$ are entirely defined by how they permute $\alpha_{1},\alpha_{2},\dots \alpha_{n}$, with the added restriction that $\alpha_{i}\longmapsto \alpha_{j}$ if and only if $\alpha_{i}$ and $\alpha_{j}$ are roots of the same irreducible polynomial over $F$. Furthermore, composing two automorphisms corresponds to composing their permutations of the alphas. Thus, $\text{Gal}(F(\alpha_{1},\alpha_{2},\dots \alpha_{n}/F))$ will be isomorphic to some subset of the group of permutations of $n$ symbols.
