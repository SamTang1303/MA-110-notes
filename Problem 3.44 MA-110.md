---
aliases:
  - homomorphisms preserve identities
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.44 MA-110

> [!problem] Problem 3.44
> Let $G$ and $H$ be groups, with identities $e_{G}$ and $e_{H}$, respectively. Let $\phi:G\longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]]. Prove that $\phi(e_{G})=e_{H}$. (Hint: consider $\phi(e_{G}e_{G})$.)

Let $G$ and $H$ be groups, with identities $e_{G}$ and $e_{H}$, respectively. Further, let $\phi:G\longrightarrow H$ be a homomorphism.
$$
\begin{align}
\phi(e_{G}e_{G}) &= \phi(e_{G})\phi(e_{G}) && \text{Definition of a homomorphism}\\ 
\phi(e_{G}) &= \phi(e_{G})\phi(e_{G}) && \text{Definition of an identity}\\
(\phi(e_{G}))^{-1}\phi(e_{G}) &= (\phi(e_{G})^{-1}\phi(e_{G}))\phi(e_{G}) && \text{Left multiplication}\\
e_{H}&= e_{H} \phi(e_{G}) && \text{Definition of an inverse}\\
e_{H} &= \phi(e_{G}) && \text{Definition of an identity} \\
\end{align}
$$
