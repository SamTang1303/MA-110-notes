---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.178 MA-111

> [!problem] Problem 10.178
> Let $S$ be a set, and let $X = \{ (x_{0},x_{1},\dots,x_{n-1}) \mid x_{i} \in S \}$ be the set of all n-tuples of elements of $S$. Show that the group $\mathbb{Z}_{n}$ acts on $X$ by shifting: $\phi_{k}(x_{0},x_{1},\dots x_{n-1})=(x_{0+k},x_{1+k},\dots,x_{n-1+k})$, where the subscripts are taken modulo $n$.

Let $S$ be a set, and let $X = \{ (x_{0},x_{1},\dots,x_{n-1}) \mid x_{i} \in S \}$ be the set of all n-tuples of elements of $S$. Show that the group $\mathbb{Z}_{n}$ acts on $X$ by shifting: $\phi_{k}(x_{0},x_{1},\dots x_{n-1})=(x_{0+k},x_{1+k},\dots,x_{n-1+k})$, where the subscripts are taken modulo $n$.

Let $(x_{0},x_{1},\dots x_{n-1}) \in X$. First, we show $\phi_{0}$ is an identity function.
$$
\phi_{0}((x_{0},x_{1},\dots x_{n-1})) = (x_{0+0},x_{1+0},\dots x_{n-1+0}).
$$
Let $a,b \in \mathbb{Z}_{n}$.
$$
\begin{align}
\phi_{a+b}((x_{0},x_{1},\dots x_{n-1})) &= (x_{a+b},x_{1+a+b},\dots x_{n-1+a+b}) \\
&= \phi_{a}(x_{b},x_{1+b},\dots x_{n-1+b}) \\
&= \phi _{a}(\phi_{b}((x_{0},x_{1},\dots x_{n-1}))).
\end{align}
$$
