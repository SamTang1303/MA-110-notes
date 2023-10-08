---
aliases:
  - isomorphisms preserve order
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.47 MA-110

> [!problem] Problem 3.47
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is an [[Definition 3.1.2 MA-110|isomorphism]]. Prove that if $G$ has an element of [[Definition 3.2 MA-110|order]] $n$, then $H$ has an element of order $n$. Would this statement still be true if $\phi$ were just a [[Definition 3.1.1 MA-110|homomorphism]] and not an isomorphism?

Suppose that $G$ and $H$ are groups with identities $e_{G}$ and $e_{G}$ respectively, and that $\phi:G \longrightarrow H$ is an isomorphism. Further, suppose $G$ has an element $g_{0}$ of order $n$. Thus, we know $\langle g_{0}\rangle=\{ g_{0}^{1},g_{0}^{2},\dots g_{0}^{n} \}$ where $g^{n}=e_{G}$.

Consider the set 
$$
\begin{align}
\phi(\langle g_{0}\rangle) &= \{ \phi(g_{0}^{1}),\dots,\phi(g_{0}^{n}) \}\\
&= \{ \phi(g_{0})^{1},\dots, \phi(g_{0})^{n} \}^{\dagger}.\\
\end{align}
$$
Moreover, all of these element must be unique because $\phi$ is 1-1. Therefore, we can see that $\phi(g_{0})$ has order of at least $n$. We also know the order cannot be greater than $n$ because $\phi(g_{0})^{n}=\phi(g_{0}^{n})=\phi(e_{G})=e_{G}$, by [[Problem 3.44 MA-110|Problem 44]]. Therefore, $\phi(g_{0})$ has order of exactly $n$.

This theorem would not apply if $\phi$ were just a homomorphism and not an isomorphism. Consider if we had mapping $\phi:G \longrightarrow\langle \{ 1 \},\times \rangle$ such that $\phi(g)=1$ for all $g\in G$. This can trivially be verified to be a homomorphism, but clearly $\langle \{ 1 \},\times \rangle$ has no elements of order greater than $n$ if $n>1$.
- - -
$^{\dagger}$It can be easily seen by iterative applications of the property of homomorphisms that, for any group $G$ with $g \in G$, if $\phi$ is a homomorphism, then $\phi(g^{n})=\phi(g)^{n}$.
