---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.41 MA-110

> [!problem] Problem 3.41
> Suppose that $G$ is an abelian group. Prove that the function defined by $\phi(g) = g^{2}$ is a [[Definition 3.1.1 MA-110|homomorphism]] from $G\longrightarrow G$.

Let $G$ be an abelian group. Consider the function $\phi(g)=g^{2}$. Let $g_{1},g_{2} \in G$.
$$
\phi(g_{1})\phi(g_{2}) = g_{1}^{2}g_{2}^{2}
$$
and
$$
\phi(g_{1}g_{2}) = (g_{1}g_{2})^{2} = g_{1}g_{2}g_{1}g_{2} = (g_{1}g_{1})(g_{2}g_{2}) = g_{1}^{2}g_{2}^{2} = \phi(g_{1})\phi (g_{2}).
$$
Therefore, by Definition 3.1, $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]] from $G\to G$.
