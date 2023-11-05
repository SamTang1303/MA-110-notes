---
aliases:
  - ring homomorphism
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 6.97 MA-110

> [!problem] Problem 6.97
> Without consulting any textbooks, the internet, or anyone else, make a guess at a definition of a **ring homomorphism**. Find a nontrivial example of a ring homomorphism that fits your definition.

> [!definition] Sam's definition of a ring homomorphism
> Let $R$ and $S$ be rings.  A mapping $\phi:R \longrightarrow S$ is defined to be a **ring homomorphism** if, for all $a,b,c \in R$
> $$
> \phi(a+b) = \phi(a) + \phi(b) \text{ and } \phi(a \cdot b) = \phi(a)  \cdot \phi(b)
> $$

For example, consider the rings $\mathbb{Z}\times \mathbb{Z}$ and $\mathbb{Q}$ where addition and multiplication are defined standardly for $\mathbb{Q}$, and as follows for $\mathbb{Z}$: for all $(a,b),(c,d) \in \mathbb{Z}\times \mathbb{Z}$
$$
\begin{align}
(a,b) + (c,d) &= (ad + cb, bd) \\
&\text{and} \\
(a,b)  \cdot (c,d) &= (ab,cd).
\end{align}
$$
The function $\phi :\mathbb{Z} \times \mathbb{Z} \longrightarrow \mathbb{Q}$ such that $\phi((a,b))= a/b$ is an example of a ring homomorphism, as we will show.

Let $(p_{1},q_{1}),(p_{2},q_{2}) \in \mathbb{Z}\times \mathbb{Z}$.
$$
\begin{align}
\phi ((p_{1},q_{1})(p_{2},q_{2})) &= \phi((p_{1}p_{2},q_{1}q_{2})) \\
&= \frac{p_{1}p_{2}}{q_{1}q_{2}} \\
&= \frac{p_{1}}{q_{1}}  \cdot \frac{p_{2}}{q_{2}} \\
&= \phi(p_{1},q_{1})\phi(p_{2},q_{2}).
\end{align}
$$
And,
$$
\begin{align}
\phi((p_{1},q_{1}) + (p_{2},q_{2})) &= \phi((p_{1}q_{2} + q_{1}p_{2},q_{1}q_{2})) \\
&= \frac{p_{1}q_{2}+q_{1}p_{2}}{q_{1}q_{2}} \\
&= \frac{p_{1}}{q_{1}} + \frac{p_{2}}{q_{2}} \\
&= \phi((p_{1},q_{1})) + \phi((p_{2},q_{2})).
\end{align}
$$
Therefore, $\phi$ is a ring homomorphism.
