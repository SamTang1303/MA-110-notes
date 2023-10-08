---
aliases:
  - all elements of cosets of the kernel map to the same element
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 3.4 MA-110|kernel]]"
---
# Problem 4.68 MA-110

> [!problem] Problem 6.68
> Let $\phi:G\longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]] and let $K=\ker(\phi)$. Let $a$ be a fixed element of $G.$ Prove that $aK=\{ x \in G : \phi(x)=\phi(a) \}$.

Let $\phi:G\longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]] and let $K=\ker(\phi)$. Let $a$ be a fixed element of $G$.

Let $x \in aK$. Then for some $k \in \ker(\phi)$, $ak=x$. Thus,
$$
\begin{align}
\phi(ak)&=\phi(x) \\
\phi(a)\phi(k) &= \phi(x) && \text{property of homomorphisms} \\
\phi(a) &= \phi(x) && k \in  \ker(\phi ).
\end{align}
$$
Therefore, $aK \subseteq \{ x \in G : \phi(x)=\phi(a) \}$.

Now suppose that $x \in \{ x \in G : \phi(x)=\phi(a) \}$. Consider $k=a^{-1}x$:
$$
\begin{align}
\phi(k)&= \phi(a^{-1}x) \\
&= \phi(a^{-1})\phi(x) && \text{property of homomorphisms} \\
&= \phi(a)^{-1}\phi(x) &&\text{Problem 45} \\
&= \phi(x)^{-1}\phi(x) && \text{assumption} \\
&= e.
\end{align}
$$
Therefore, $k \in \ker(K)=K$. Furthermore, $ak=aa^{-1}x=x$, so $x \in aK$. Thus, $\{ x \in G : \phi(x)=\phi(a) \}\subseteq aK$ and the two sets must be equal.
