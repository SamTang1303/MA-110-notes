---
aliases: 
tags:
  - batch/school/class/ma110
  - subject/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-17
# Pre-Work Problems 49 Through  53 MA-110

> [!problem] Problem 3.49
> Let $\phi:U(10)\longrightarrow U(10)$ be defined by $\phi(a)=a^{2}$ for all $a \in U(10)$. (You already proved in problem [[Pre-Work Problems 40 Through 44 MA-110#^fd9a05|Problem 40]] that $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]].) Determine $\phi(U(10))$ and $\ker(\phi)$.

Let $\phi:U(10)\longrightarrow U(10)$ be defined by $\phi(a)=a^{2}$ for all $a \in U(10)$, and have identity $e$.

1. $\phi(U(10))=\{ 1,9 \}$
2. $\ker(\phi)=\{ 1,9 \}$

> [!problem] Problem 3.50
> Suppose that $G$ and $H$ are groups, and that $\phi:G\longrightarrow H$ is a homomorphism. Prove that $\ker(\phi)$ is a subgroup of $G$.

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$, respectively, and $\phi:G \longrightarrow H$ be a homomorphism.

1 ) $\phi(e_{G})=e_{H}$ by [[Pre-Work Problems 40 Through 44 MA-110#^0d5e59|Problem 44]], therefore $e_{G} \in \ker(\phi)$.
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

> [!problem] Problem 3.51
> Suppose $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]]. Let $K$ be a subgroup of $G$. Prove that $\phi(K)$ is a subgroup of $H$.

^359dd1

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
3 ) Let $h \in \phi(K)$. Then there exists some $g \in K$ such that $\phi(g)=h$. $K$ is a subgroup, so $g^{-1} \in K$ and $\phi(g^{-1}) \in \phi(K)$. By [[Pre-Work Problems 45 Through 48 MA-110#^a2d670|Problem 45]], $\phi(g^{-1})=(\phi(g))^{-1}$. Thus $h^{-1} \in \phi(K)$ and $\phi(K)$ is closed under inverses.

Thus, by definition 2.3, $\phi(K)$ must be a subgroup of $H$.

> [!problem] Problem 3.52
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]]. Prove that $\ker(\phi)=\{ e \}$ if and only if $\phi$ is one-to-one.

^206abd

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$ respectively, and that $\phi:G\longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]].

First, we will show the forward direction: Suppose $\ker(\phi)=\{ e_{G} \}$.
Let $a,b \in G$ and suppose $\phi(a)=\phi(b)$. Consider the following:
$$
\begin{align}
\phi(ab) &=\phi(a)\phi(b) && \phi \text{ is a homomorphism}\\
&=\phi(a)\phi(a) && \text{given by assumption}\\
&= \phi (a^{2}).&& \phi \text{ is a homomorphism}
\end{align}
$$
Thus, 
$$
\phi(ab) =\phi(a^{2}). \qquad(1)
$$
By definition of an inverse,
$$
\begin{align}
e_{H} &= \phi(ab)(\phi(ab))^{-1}\\
&= \phi(a^{2})(\phi(ab))^{-1} && \text{justified by (1)}\\
&= \phi(a^{2})\phi((ab)^{-1}) && \text{Problem 45}\\
&= \phi(a^{2}(ab^{-1})).
\end{align}
$$
Thus, $e_{H}=\phi(a^{2}(ab)^{-1})$. Because $\ker(\phi)=\{ e_{G} \}$ by assumption, $a^{2}(ab)^{-1}=e_{G}$. So,
$$
\begin{align}
a^{2}(ab)^{-1} &= e_{G}\\
a^{2}(ab)^{-1}(ab)&= e_{G}(ab) && \text{right multiplication}\\
a^{2}=&ab && \text{def. of an inverse, def. of an identity}\\
a&= b. && \text{left cancellation}
\end{align}
$$
Therefore, by definition, $\phi$ must be one-to-one.

Now, we will show the backward direction: Suppose $\phi$ is one-to-one.
By [[Pre-Work Problems 40 Through 44 MA-110#^0d5e59|Problem 44]] we know $\phi(e_{G})=e_{H}$. Thus $e_{G} \in \ker(\phi)$. It cannot be that $\phi(a)=e_{H}$ if $a\neq e_{G}$ because $\phi(a)$ would equal $\phi(e_{G})$ and this would violate $\phi$ being one-to-one. Therefore $\ker(\phi)=\{ e_{G} \}$.

> [!problem] Problem 3.53
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]]. Prove that $\phi(G)$ is abelian if and only if, for all $x,y \in G$, $xyx^{-1}y^{-1} \in \ker(\phi)$.
> 

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$, respectively, and $\phi:G \longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]].

First, we prove that forward direction: Suppose $\phi(G)$ is abelian and $x,y \in G$.
$$
\begin{align}
\phi(xyx^{-1}y^{-1}) &= \phi(x)\phi(y)\phi(x^{-1})\phi(y^{-1}) &&\phi \text{ is a homomorphism}\\
&= \phi(x)\phi(x^{-1})\phi(y)\phi(y^{-1}) && \phi(G)\text{ is abelian}\\
&= \phi(x x^{-1})\phi(y y ^{-1}) && \phi \text{ is a homomorphism}\\
&= \phi(e_{G})\phi(e_{G}) && \text{definition of inverses}\\
&= e_{H}e_{H} && \text{Problem 44}\\
&= e_{H}. && \text{definition of an identity}\\
\end{align}
$$
Therefore, by definition 3.4, $xyx^{-1}y^{-1} \in \ker(\phi)$.

Now, we must show the backward direction: Suppose $xyx^{-1}y^{-1} \in \ker(\phi)$ for all $x,y \in G$.

Let $a,b \in \phi(G)$. Then, there exist some $x,y \in G$ such that $\phi(x)=a$ and $\phi(y)=b$. By assumption, $\phi(xyx^{-1}y^{-1}) = e_{H}$. So,
$$
\begin{align}
e_{H} &= \phi(xyx^{-1}y^{-1})\\
e_{H} &= \phi(x)\phi(y)\phi(x^{-1})\phi(y^{-1}) &&\phi \text{ is a homomorphism}\\
(\phi(x)\phi(y))^{-1} &= \phi(x^{-1})\phi(y^{-1}) && \text{left multiplication/cancellation}\\
(\phi(x)\phi(y))^{-1} &= (\phi(x))^{-1}(\phi(y))^{-1} && \text{Problem 45}\\
(ab)^{-1}&= a^{-1}b^{-1}\\
ab&= (b^{-1})^{-1}(a^{-1})^{-1} && \text{Problem 21}\\
ab&= ba. && \text{Problem 15}
\end{align}
$$
Therefore, $\phi(G)$ is abelian, the backward direction is shown, and the proof is complete.
