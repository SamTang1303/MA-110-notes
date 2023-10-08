---
aliases: 
tags:
  - batch/math
  - batch/school/class/ma110
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-27
# Pre-Work Problems 64 Through 68 MA-110

> [!problem] Problem 4.64
>     Suppose that $G$ is a finite group and $H$ is a subgroup of $G$. Prove that $\left| H \right|$ divides $\left| G \right|$. Explain why it follows that the order of any element of $G$ also divides $\left| G \right|$

^a8723b

Let $G$ be a finite group and $H$ a subgroup of $G$. Consider the set of all
$$
X=\{ gH: g \in  G \}.
$$
We can interpret this as the set of all left cosets of $H$. Let $A \in X$. For some $a \in g$, $aH=A$. By [[Pre-Work Problems 60 Through 63 MA-110#^ed1852|Problem 62]], we know $\left| H \right|=\left| aH \right|=\left| A \right|$ and $\left| A \right|=\left| B \right|$. Thus, the order of every of $X$ is $\left| H \right|$. For any $g \in G$, $g \in gH\in X$. So $\cup_{O \in X} O=G$. Further, [[Pre-Work Problems 60 Through 63 MA-110#^0d748d|Problem 61]] tells us that all the distinct elements of $X$ are pairwise disjoint, so
$$
\begin{align}
\left| G \right| &=\left| \bigcup\limits_{O \in  X}O \right|  \\
&=  \sum\limits_{O \in  X} \left| O \right| && \text{elements of X are disjoint}  \\
&= \sum\limits_{O \in  X}\left| H \right| && O\text{ is a coset of }H \\
&= \left| X \right| \left| H \right| .
\end{align}
$$
Thus, we can see the order of $H$ divides the order of $G$. This implies the order of every element of $G$ also divides $\left| G \right|$ because the order of an element is determined by the [[Definition 2.5 MA-110|cyclic subgroup]] it generates.

> [!problem] Problem 4.65
> Prove that every group of prime order is cyclic.

Let $G$ be a group of prime order. For any $g \in G$, the order of $G$ must be either $1$ or $\left| G \right|$  ([[#^a8723b|Problem 64]]). The only element that can have order one is the identity, so all other elements must have order $\left| G \right|$, meaning they generate every element of the group.

> [!problem] Problem 4.66
> Show that any [[Definition 3.1.1 MA-110|homomorphism]] of groups $\phi:G\longrightarrow H$ where $\left| G \right|$ is prime must be either the trivial [[Definition 3.1.1 MA-110|homomorphism]], or a one-to-one map.

^bda8d5

Let $\phi:G\longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]] of groups where $G$ is prime. Suppose that $\phi$ is not a one-to-one map. Then, by [[Pre-Work Problems 49 Through  53 MA-110#^206abd|Problem 52]], $\left| \ker(\phi) \right|>1$. $\ker(\phi)$ is a subgroup of $G$ and must have an order that is a factor of $\left| G \right|$ by [[#^a8723b|Problem 64]]. $\left| G \right|$ is prime, so this is only possible if $\left| \ker(\phi) \right|=\left| G \right|$. Therefore, the [[Definition 3.4 MA-110|kernel]] must contain every element of $G$ and $\phi$ is the trivial [[Definition 3.1.1 MA-110|homomorphism]].

Thus, $\phi$ must be either trivial, or a one-to-one map.

> [!problem] Problem 4.67
> Explain why there are no nontrivial homomorphisms $\phi:\mathbb{Z}_{7}\longrightarrow S_{6}$.

Let $\phi:\mathbb{Z}\longrightarrow S_{6}$ be a non-trivial [[Definition 3.1.1 MA-110|homomorphism]].
By [[#^bda8d5|Problem 66]], $\phi$ must be one-to-one. But if that were the case $\phi(\mathbb{Z}_{7})$ must be order 7 as well, and, by [[Pre-Work Problems 49 Through  53 MA-110#^359dd1|Problem 51]], a subgroup of $S_{6}$. There can be no subgroups of order 7 of $S_{6}$ because $\left| S_{6} \right|=720$, which does not have a factor of 7 (Problem 64.)

> [!problem] Problem 6.68
> Let $\phi:G\longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]] and let $K=\ker(\phi)$. Let $a$ be a fixed element of $G.$ Prove that $aK=\{ x \in G : \phi(x)=\phi(a) \}$.

^6bf01f

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

<div class="page-break" style="page-break-after: always;"></div> 

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
