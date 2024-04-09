---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.174 MA-111

> [!problem] Problem 174
> In the Introductory Activity at the beginning of these notes, you constructed a table of permutations corresponding to the elements of the group $D_{4}$. Show, by multiplying permutations, that all eight of these can be obtained by taking products of $(1\ 2)(3\ 4)$ and $(1\ 3)$. That is, show that $D_{4}\simeq \langle (1\ 2)(3\ 4), (1\ 3)\rangle$.

Note that once we have shown an element can be obtained as a product of $(1\ 2)(3\ 4)$ and $(1\ 3)$, we can use that element to construct other products of the two given elements.
$$
\begin{align}
(1) &= (1\ 3)(1\ 3) \\
(1\ 4\ 3\ 2) &= [(1\ 2)(3\ 4)] (1\ 3)  \\
(1\ 3)(2\ 4) &= (1\ 4\ 3\ 2)(1\ 4\ 3\ 2) \\
(1\ 2\ 3\ 4) &= [(1\ 3)(2\ 4)](1\ 4\ 3\ 2) \\
(1\ 3)&= (1\ 3)\\
(1\ 4)(2\ 3)&= (1\ 2\ 3\ 4)(1\ 3) \\
(2\ 4)&= (1\ 2\ 3\ 4)\big[(1\ 4)(2\ 3)\big] \\
(1\ 2)(3\ 4)&= (1\ 2\ 3\ 4)(2\ 4)
\end{align}
$$
Thus, all elements of $D_{4}$ can be represented as products of $(1\ 2)(3\ 4)$ and $(1\ 3)$.
