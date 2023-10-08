---
aliases:
  - kernels are subgroups
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 3.4 MA-110|kernel]]"
---
# Problem 3.50 MA-110

> [!problem] Problem 3.50
> Suppose that $G$ and $H$ are groups, and that $\phi:G\longrightarrow H$ is a homomorphism. Prove that $\ker(\phi)$ is a [[Definition 2.3 MA-110|subgroup]] of $G$.

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$, respectively, and $\phi:G \longrightarrow H$ be a homomorphism.

1 ) $\phi(e_{G})=e_{H}$ by [[Problem 3.44 MA-110|Problem 44]], therefore $e_{G} \in \ker(\phi)$.
2 ) Let $g_{1},g_{2} \in \ker(\phi)$. Consider $\phi(g_{1}g_{2})$:
$$
\begin{align}
\phi(g_{1}g_{2}) &= \phi(g_{1})\phi(g_{2}) && \phi\text{ is a homomorphism}\\
&= e_{H}e_{H} && \text{definition of }g_{1},g_{2} \in  \ker(\phi)\\
&= e_{H}. && \text{definition of an identity}
\end{align}
$$
Therefore, by definition 3.4 $g_{1}g_{2} \in \ker(\phi)$ and $\ker(\phi)$ is closed under multiplication.
3 ) Let $g \in \ker(\phi)$.
$$
\begin{align}
g g^{-1} &= e_{G} && \text{definition of an inverse}\\
\phi(g)\phi(g^{-1}) &= \phi(e_{H}) && \phi \text{ is a homomorphism}\\
\phi(g)\phi(g^{-1}) &=  e_{G} && \text{Problem 44}\\
e_{G}\phi(g^{-1}) &=  e_{G} && g \in  \ker(\phi )\\
\phi(g^{-1}) &= e_{G}. && \text{definition of an identity}
\end{align}
$$
Thus, by definition, $g^{-1} \in \ker(\phi)$ and $\ker(\phi)$ is closed under inverses.

Therefore, by definition 2.3, $\ker(\phi)$ must be a subgroup of $G$.
