---
aliases:
  - isomorphisms preserve the property of being abelian
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.46 MA-110

> [!problem] Problem 3.46
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is an [[Definition 3.1.2 MA-110|isomorphism]]. Prove that if $G$ is abelian, then $H$ is [[Definition 1.5 MA-110|abelian]]. Would this statement still be true if $\phi$ were just a [[Definition 3.1.1 MA-110|homomorphism]] and not an isomorphism?

Let $G$ and $H$ be groups and that $\phi:G\longrightarrow H$ is an isomorphism. Further, suppose $G$ is abelian.

Let $h_{1}, h_{2} \in G$. Because $\phi$ is an isomorphism and therefore onto, there must exist some $g_{1}, g_{2}$ such that $\phi(g_{1})=h_{1}$ and $\phi(g_{2})=h_{2}$. Thus,
$$
\begin{align}
h_{1}h_{2} &=  \phi(g_{1})\phi(g_{2})\\
&= \phi(g_{1}g_{2}) && \phi \text{ is a homomorphism}\\\
&= \phi(g_{2}g_{1}) && G \text{ is abelian}\\
&= \phi(g_{2})\phi(g_{1}) && \phi \text{ is a homomorphism}\\
&= h_{2}h_{1}.
\end{align}
$$
Therefore, $H$ is abelian as well.

If $\phi$ were a homomorphism instead of an isomorphism, the theorem would not hold. Let $G=\langle \{ 1 , \times \}\rangle$ and $H=\langle \mathbb{Z}, -\rangle$ and $\phi:G \longrightarrow H$ is a function such that $\phi(g)=1$ for all $g \in G$. $\phi$ trivially satisfies the criteria for a homomorphism, but $G$ is abelian while $H$ is not. 
