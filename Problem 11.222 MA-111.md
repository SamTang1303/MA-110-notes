---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.222 MA-111

> [!problem] Problem 11.222
> Let $\phi:F_{1}\longrightarrow F_{2}$ be a nontrivial homomorphism of fields (i.e., not everything maps to zero.) Show that $\phi(1)=1$. Furthermore, show that if $F_{1}$ and $F_{2}$ both contain $\mathbb{Q}$, then $\phi(x)=x$ for all $x \in \mathbb{Q}$. (In other words, $\phi$ **fixes** $\mathbb{Q}$.)

Let $\phi:F_{1}\longrightarrow F_{2}$ be a nontrivial homomorphism of fields.
$$
\begin{align}
\phi(1)&= \phi(1 \cdot 1) \\
&= \phi(1)\phi(1).
\end{align}
$$
Cancelling then yields $\phi(1)=1$. Note that cancelling is possible because $\phi(1)\neq0$, otherwise $\phi(x)=\phi(x \cdot1)=\phi(x)\phi(1)=\phi(x) \cdot0=0$ for all $x \in F_{1}$.

Suppose that $F_{1}$ and $F_{2}$ both contain $\mathbb{Q}$. Let $x \in \mathbb{Q}$. Then for some $a,b \in \mathbb{Z}$, $x=a \cdot b^{-1}$.
$$
\begin{align}
\phi(x) &= \phi(ab^{-1}) \\
&= \phi(a)\phi(b^{-1}) && \text{property of homomorphisms} \\
&= \phi(a)\phi(b)^{-1} && \text{hmm's preserve mult. inverses} \\
&= \phi(\underbrace{1+1+\dots1}_{a})\phi(\underbrace{1+1+\dots1}_{b})^{-1} \\
&= \Big(\underbrace{\phi(1)+\phi(1)+\dots \phi(1)}_{a}\Big)\Big(\underbrace{\phi(1)+\phi(1)+\dots \phi(1)}_{b}\Big)^{-1} \\
&= (\underbrace{1+1+\dots1}_{a})(\underbrace{1+1+\dots1}_{b})^{-1} && \text{proven above} \\
&= ab^{-1} \\
&= x.
\end{align}
$$
This argument assumes $a$ and $b$ to be positive integers, but because homomorphisms preserve additive inverses as well, it still applies to negative rationals.
