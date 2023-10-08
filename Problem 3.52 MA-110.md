---
aliases:
  - the kernel is the identity if and only of the homomorphism is one-to-one
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 3.4 MA-110|kernel]]"
---
# Problem 3.52 MA-110

> [!problem] Problem 3.52
> Suppose that $G$ and $H$ are groups, and that $\phi:G \longrightarrow H$ is a [[Definition 3.1.1 MA-110|homomorphism]]. Prove that $\ker(\phi)=\{ e \}$ if and only if $\phi$ is one-to-one.

Let $G$ and $H$ be groups with identities $e_{G}$ and $e_{H}$ respectively, and that $\phi:G\longrightarrow H$ is a homomorphism.

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
By [[Problem 3.44 MA-110|Problem 44]] we know $\phi(e_{G})=e_{H}$. Thus $e_{G} \in \ker(\phi)$. It cannot be that $\phi(a)=e_{H}$ if $a\neq e_{G}$ because $\phi(a)$ would equal $\phi(e_{G})$ and this would violate $\phi$ being one-to-one. Therefore $\ker(\phi)=\{ e_{G} \}$.
