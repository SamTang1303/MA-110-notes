---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.253 MA-111

> [!problem] Problem 13.253
> Let $K$ be the splitting field of $x^{4}-2$ over $\mathbb{Q}$. Compute $\text{Gal}(K/\mathbb{Q})$ and represent it as a subgroup of $S_{4}$.

Let $K$ be the splitting field of $x^{4}-2$ over $\mathbb{Q}$. Because $i\sqrt[3]{ 2 }/\sqrt[3]{ 2 }=i$, $i$ is an element of the field, making it easy to show that $K=\mathbb{Q}(i,\sqrt[4]{ 2 })$. By the degree multiplication theorem,
$$
[\mathbb{Q}(i,\sqrt[4]{ 2 })] = [\mathbb{Q}(i,\sqrt[4]{ 2 }): \mathbb{Q}(\sqrt[4]{ 2 })][\mathbb{Q}(\sqrt[4]{ 2 }):\mathbb{Q}]=2 \cdot 4=8.
$$
Therefore, by [[Problem 12.231 MA-111|Problem 231]] $K$ is isomorphic to a subgroup of $S_{4}$ with degree $8$. Thus, it is a Sylow-2 subgroup of $S_{4}$. We will identify the roots of $x^{4}-2$, $\sqrt[4]{ 2 }, i\sqrt[4]{ 2 }, -\sqrt[4]{ 2 },$ and $-i\sqrt[4]{ 2 }$ with the symbols $1, 2,3,$ and $4$, respectively. The Sylow-2 subgroups of $S_{4}$ are
$$
\begin{align}
\langle (1\ 2\ 3\ 4), (1\ 3)\rangle \\
\langle (1\ 3\ 4\ 2), (2\ 3)\rangle \\
\langle (1\ 4\ 2\ 3),(1\ 4)\rangle.
\end{align}
$$
We will show that the second two groups cannot be $\text{Gal}(K/\mathbb{Q})$.
$$
\begin{align}
(2\ 3)(i) &= (2\ 3)\left( \frac{i\sqrt[4]{ 2 }}{\sqrt[4]{ 2 }} \right) \\
&= \frac{(2\ 3)i\sqrt[4]{ 2 }}{(2\ 3)\sqrt[4]{ 2 }} \\
&= -\frac{\sqrt[4]{ 2 }}{\sqrt[4]{ 2 }} \\
&= -1.
\end{align}
$$
$$
\begin{align}
(1\ 4)(i) &= (1\ 4)\left( \frac{i\sqrt[4]{ 2 }}{\sqrt[4]{ 2 }} \right) \\
&= \frac{(1\ 4)i\sqrt[4]{ 2 }}{(1\ 4)\sqrt[4]{ 2 }} \\
&= \frac{i\sqrt[4]{ 2 }}{-i\sqrt[4]{ 2 }} \\
&= -1.
\end{align}
$$
Because non-trivial automorphisms of $K$ must fix $\mathbb{Q}$ and be 1-to-one, $(2\ 3)$ and $(1\ 4)$ cannot be automorphisms. Therefore,
$$
\langle (1\ 2\ 3\ 4),(1\ 3)\rangle \simeq \text{Gal}(K/\mathbb{Q}).
$$
