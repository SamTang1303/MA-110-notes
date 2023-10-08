---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.45 MA-110

> [!problem] Problem 3.45
> Suppose that $G$ and $H$ are groups, and that $\phi:G\longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]]. Prove that, for all $a \in G$, $\phi(a^{-1})=(\phi(a))^{-1}$.

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$ respectively, and that $\phi:G \longrightarrow H$ is a homomorphism. 

Let $a \in G$.
$$
\begin{align}
\phi(a)\phi(a^{-1}) &= \phi(aa^{-1}) && \phi\text{ is [[Definition 3.1.2 MA-110|isomorphic]]}\\
&= \phi(e_{G})\\
&= e_{H} && \text{Problem 44}
\end{align}
$$
Therefore, by [[Problem 1.13 MA-110|Problem 13]], $\phi(a^{-1})=(\phi(a))^{-1}$.
