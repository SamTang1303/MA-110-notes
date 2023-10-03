---
aliases: 
tags:
  - batch/school/class/ma110
  - subject/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-13
# Pre-Work Problems 45 Through 48 MA-110

> [!problem] Problem 3.45
> Suppose that $G$ and $H$ are groups, and that $\phi:G\longrightarrow H$ is a homomorphism. Prove that, for all $a \in G$, $\phi(a^{-1})=(\phi(a))^{-1}$.

^a2d670

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$ respectively, and that $\phi:G \longrightarrow H$ is a homomorphism. 

Let $a \in G$.
$$
\begin{align}
\phi(a)\phi(a^{-1}) &= \phi(aa^{-1}) && \phi\text{ is isomorphic}\\
&= \phi(e_{G})\\
&= e_{H} && \text{Problem 44}
\end{align}
$$
Therefore, by [[Pre-Work Problems 8 Through 15 MA-110#^f23d7c|Problem 13]], $\phi(a^{-1})=(\phi(a))^{-1}$.

> [!problem] Problem 3.46
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is an isomorphism. Prove that if $G$ is abelian, then $H$ is abelian. Would this statement still be true if $\phi$ were just a homomorphism and not an isomorphism?

^57f3d4

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

> [!problem] Problem 3.47
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is an isomorphism. Prove that if $G$ has an element of order $n$, then $H$ has an element of order $n$. Would this statement still be true if $\phi$ were just a homomorphism and not an isomorphism?

^19dd32

Suppose that $G$ and $H$ are groups with identities $e_{G}$ and $e_{G}$ respectively, and that $\phi:G \longrightarrow H$ is an isomorphism. Further, suppose $G$ has an element $g_{0}$ of order $n$. Thus, we know $\langle g_{0}\rangle=\{ g_{0}^{1},g_{0}^{2},\dots g_{0}^{n} \}$ where $g^{n}=e_{G}$.

Consider the set 
$$
\begin{align}
\phi(\langle g_{0}\rangle) &= \{ \phi(g_{0}^{1}),\dots,\phi(g_{0}^{n}) \}\\
&= \{ \phi(g_{0})^{1},\dots, \phi(g_{0})^{n} \}^{\dagger}.\\
\end{align}
$$
Moreover, all of these element must be unique because $\phi$ is 1-1. Therefore, we can see that $\phi(g_{0})$ has order of at least $n$. We also know the order cannot be greater than $n$ because $\phi(g_{0})^{n}=\phi(g_{0}^{n})=\phi(e_{G})=e_{G}$, by [[Pre-Work Problems 40 Through 44 MA-110#^0d5e59|Problem 44]]. Therefore, $\phi(g_{0})$ has order of exactly $n$.

This theorem would not apply if $\phi$ were just a homomorphism and not an isomorphism. Consider if we had mapping $\phi:G \longrightarrow\langle \{ 1 \},\times \rangle$ such that $\phi(g)=1$ for all $g\in G$. This can trivially be verified to be a homomorphism, but clearly $\langle \{ 1 \},\times \rangle$ has no elements of order greater than $n$ if $n>1$.
- - -
$^{\dagger}$It can be easily seen by iterative applications of the property of homomorphisms that, for any group $G$ with $g \in G$, if $\phi$ is a homomorphism, then $\phi(g^{n})=\phi(g)^{n}$.

<div class="page-break" style="page-break-after: always;"></div> 

> [!problem] Problem 3.48
> In each of the following, prove that the two groups specified are not isomorphic.
> 1. $S_{4}$ and $\mathbb{Z}_{6}\times \mathbb{Z}_{4}$
> 2. $\mathbb{Z}_{2}\times \mathbb{Z}_{4}$ and $\mathbb{Z}_{8}$
> 3. $U(10)$ and $\mathbb{Z}_{2}\times \mathbb{Z}_{3}$
> 4. $\langle \mathbb{Q}^{*},\times \rangle$ and $\langle \mathbb{Z},+\rangle$, where $\mathbb{Q}^{*}$ denotes the nonzero rational numbers.
> 5. $\langle \mathbb{R}^{*}, \cdot\rangle$ and $\langle \mathbb{R},+\rangle$.

1. $(1\,2\,3)(1\,2)=(1\,3)$ and $(1\,2)(1\,2\,3)=(23)$. Because these are not equal, $S_{4}$ cannot be abelian. On the other hand, $\mathbb{Z}_{6}\times \mathbb{Z}_{4}$ is abelian because it is the cross-product of two abelian groups. ([[Pre-Work Problems 23 Through 28 MA-110#^88be9e|Problem 27]].) Therefore, [[#^57f3d4|Problem 46]] tells us that the two groups are not isomorphic.
2. $1$ has order $8$ in $\mathbb{Z}_{8}$. For any element $(a,b) \in \mathbb{Z}_{2}\times \mathbb{Z}_{4}$, $(a,b)^{4}=(4a,4b)$, but anything times $4$ is $0$ in mod 2 and mod 4. Therefore, $(a,b)^{4}=(0,0)$, which is the groups identity element, implying no elements have order greater than 4. Therefore, by [[#^19dd32|Problem 47]], the groups are not isomorphic.
3. $U(10)=\{ 1,3,7,9 \}$ and has order 4. $\mathbb{Z}_{2}\times \mathbb{Z}_{3}= \{ (0,0),(0,1),(0,2),(1,0),(1,1),(1,2),(2,0),(2,1),(2,2) \}$ which has order $6$. Therefore, there can be no bijection between the sets and they cannot be isomorphic.
4. $\langle \mathbb{Z},+\rangle=\langle 1\rangle$ and is cyclic. If $\langle \mathbb{Q}^{*}, \cdot \rangle$ were cyclic, it would imply every element of the set could be represented as $a^{n}$ for some $a \in \mathbb{Q}^{*}$ and $n \in \mathbb{Z}$. Because $q$ is rational we could rewrite this as $\left( \frac{p}{q} \right)^{n}=\frac{p^{n}}{q^{n}}$ where $p,q \in \mathbb{Z}$ and are coprime. If we choose a prime $\rho\neq q$ then it is clear $\frac{1}{\rho }$ is not of this form. Therefore, $\langle \mathbb{Q}^{*}, \times \rangle$ cannot be cyclic or isomorphic to $\langle \mathbb{Z},+\rangle$.
5. In $\langle \mathbb{R}^{*},  \cdot \rangle$, $\langle -1\rangle=\{ -1,1 \}$ has order two. But, under $\langle \mathbb{R},  +\rangle$, $\langle x\rangle=\{ x^{n}:n \in \mathbb{Z} \}$ has infinite order for all $x\neq0$ and order $1$ when $x=0$. Therefore, $\langle \mathbb{R},+\rangle$ has no element of order $2$ and cannot be isomorphic to $\langle \mathbb{R}^{*},  \cdot \rangle$.
