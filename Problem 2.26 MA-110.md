---
aliases:
  - The cartesian product of two groups is a group
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.26 MA-110

> [!problem] Problem 2.26
> Prove that if $G$ and $H$ are groups, then $G\times H$, with operation defined component-wise, is a group.

Let $G$ and $H$ be groups. Consider $G\times H$ with operation defined component-wise and identities $e_{g}$ and $e_{h}$ respectively. Let $g_{1},g_{2} \in G$ and $h_{1},h_{2} \in H$. Because $G$ and $H$ are groups, $g_{1}g_{2} \in G$ and $h_{1}h_{2}\in H$. Therefore,
$$
(g_{1},h_{1})(g_{2},h_{2}) = (g_{1}g_{2},h_{1},h_{2}) \in  G\times H.
$$
Because we have done this for arbitrary elements $g_{1},g_{2}\in G$ and $h_{1},h_{2} \in H$, multiplication is a valid binary operation for any two elements of $G\times H$.

Suppose $(g,h)$ is an arbitrary element of $G\times H$.
$$
(g,h) (e_{g},e_{h}) = (ge_{g},he_{h}) = (g,h)
$$
Thus, $(e_{g},e_{h})$ is a valid identity element for $G\times H$.

Again, let $(g,h)$ be an arbitrary element of $G\times H$. By the definition of groups, $g^{-1}$ exists and is in $G$ and $h^{-1}$ exists and is in $H$. Therefore, $(g^{-1},h^{-1}) \in G\times H$.
$$
(g,h)(g^{-1},h^{-1}) = (gg^{-1},hh^{-1}) = (g_{e},g_{h})
$$
Thus, any element $(g,h)$ has an inverse $(g^{-1},h^{-1})$.

Let $(g_{1},h_{1}),(g_{2},h_{2}),(g_{3},h_{3}) \in G\times H$.
$$
\begin{align}
[(g_{1},h_{1})(g_{2},h_{2})](g_{3},h_{3}) &= (g_{1}g_{2},h_{1}h_{2})(g_{3},h_{3})\\
&= ((g_{1}g_{2})g_{3}, (h_{1}h_{2})h_{3})
\end{align}
$$
and,
$$
\begin{align}
(g_{1},h_{1})[(g_{2},h_{2})(g_{3},h_{3})] &= (g_{1},h_{1})(g_{2}g_{3},h_{2}h_{3})\\
&= (g_{1}(g_{2}g_{3}), h_{1}(h_{2}h_{3}))\\
&= ((g_{1}g_{2})g_{3},(h_{1}h_{2})h_{3}).
\end{align}
$$
Because these two quantities are equal, $G\times H$ is associative under the component-wise defined operation. Thus, it satisfies all the criteria for a group.
