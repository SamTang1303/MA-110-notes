---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.53 MA-110

> [!problem] Problem 3.53
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]]. Prove that $\phi(G)$ is abelian if and only if, for all $x,y \in G$, $xyx^{-1}y^{-1} \in \ker(\phi)$.
> 

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$, respectively, and $\phi:G \longrightarrow H$ be a homomorphism.

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
