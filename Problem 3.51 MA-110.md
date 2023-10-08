---
aliases:
  - the image of the kernel is a subgroup
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 3.4 MA-110|Definition of kernel]]"
---
# Problem 3.51 MA-110

> [!problem] Problem 3.51
> Suppose $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]]. Let $K$ be a subgroup of $G$. Prove that $\phi(K)$ is a subgroup of $H$.

Suppose $G$ and $H$ are groups with identities $e_{G}$ and $e_{H}$, respectively, and that $\phi:G \longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]].

1 ) $e_{G} \in  K$ by Definition 2.3 and $\phi(e_{G})=e_{H}$ by Problem 44. Therefore $e_{H} \in \phi(K)$.
2 ) Let $h_{1}h_{2} \in \phi(K)$. By definition, there exist some $g_{1}, g_{2} \in K$ such that $\phi(g_{1})=h_{1}$ and $\phi(g_{2}) = h_{2}$. 
$$
\begin{align}
k_{1}k_{2} &= \phi(g_{1})\phi (g_{2})\\
&= \phi(g_{1}g_{2}). && \phi \text{ is a homomorphism}\\
\end{align}
$$
Because $K$ is a subgroup, $g_{1}g_{2} \in K$. Therefore $\phi(g_{1}g_{2})=k_{1}k_{2} \in \phi(K)$, and $\phi(K)$ is closed under multiplication.
3 ) Let $h \in \phi(K)$. Then there exists some $g \in K$ such that $\phi(g)=h$. $K$ is a subgroup, so $g^{-1} \in K$ and $\phi(g^{-1}) \in \phi(K)$. By [[Problem 3.45 MA-110|Problem 45]], $\phi(g^{-1})=(\phi(g))^{-1}$. Thus $h^{-1} \in \phi(K)$ and $\phi(K)$ is closed under inverses.

Thus, by definition 2.3, $\phi(K)$ must be a subgroup of $H$.
