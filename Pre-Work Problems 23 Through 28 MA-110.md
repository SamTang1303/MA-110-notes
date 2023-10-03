---
aliases: []
tags:
  - batch/school/class/ma110
  - subject/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-04
# Pre-Work Problems 23 Through 28 MA-110

> [!problem] Problem 2.23
> Translate each of the following into additive notation:
> 1. $a^{n}=e$
> 2. "There exists an element $x$ such that $ax=b^{-1}$."
> 3. $a^{-1}ba=e$
> 4. $(a^{-1})^{n}=(a^{n})^{-1}$
> 5. $(a^{-1})^{-1}=a$
> 6. $a^{n}a^{m}=a^{n+m}$
> 7. $(a^{n})^{m}=a^{nm}$

1. $na=0$.
2. "There exists an element $x$ such that $a+x=-b$."
3. $-a + b + a=0$.
4. $n(-a) = -(na)$.
5. $-(-a)=a$.
6. $na+ma=(n+m)a$.
7. $m(na) = (mn)a$.

 > [!problem] Problem 2.24
 > Is multiplication modulo 7 a binary operation on $\mathbb{Z}_{7}^{*}$? If so, write out the operation table for multiplication modulo 7 on $\mathbb{Z}_{7}^{*}$. Is $\mathbb{Z}^{*}_{7}$ a group under this operation? If not, explain why not.

| $\times$ | 1   | 2   | 3   | 4   | 5   | 6   |
| ----- | --- | --- | --- | --- | --- | --- |
| 1     | 1   | 2   | 3   | 4   | 5   | 6   |
| 2     | 2   | 4   | 6   | 1   | 3   | 5   |
| 3     | 3   | 6   | 2   | 5   | 1   | 4   |
| 4     | 4   | 1   | 5   | 2   | 6   | 3   |
| 5     | 5   | 5   | 1   | 6   | 4   | 2   |
| 6     | 6   | 2   | 4   | 3   | 2   | 1   |

Yes, it is a group under this operation. It would not be if zero were included, because 0 has no inverse element, but because zero is omitted, it is.

> [!problem] Problem 2.25
> Complete the operation table for $\mathbb{Z}_{2}\times \mathbb{Z}_{3}$, where the operation is defined component-wise. (Use additive notation, since both operations are based on addition.)

| $+,+$ | $(0,0)$ | $(0,1)$ | $(0,2)$ | $(1,0)$ | $(1,1)$ | $(1,2)$ |
| ---------- | ----- | ----- | ----- | ----- | ----- | ----- |
| $(0,0)$      | $(0,0)$ | $(0,1)$ | $(0,2)$ | $(1,0)$ | $(1,1)$ | $(1,2)$ |
| $(0,1)$      | $(0,1)$ | $(0,2)$ | $(0,0)$ | $(1,1)$ | $(1,2)$ | $(1,0)$      |
| $(0,2)$      | $(0,2)$ | $(0,1)$ | $(0,1)$ | $(1,2)$ | $(1,0)$ | $(1,1)$      |
| $(1,0)$      | $(1,0)$ | $(1,1)$ | $(1,2)$ | $(0,0)$ | $(0,1)$ |  $(0,2)$     |
| $(1,1)$      | $(1,1)$ | $(2,1)$ | $(1,0)$ | $(0,1)$ | $(0,2)$ |   $(0,0)$    |
| $(1,2)$      | $(1,2)$ | $(1,0)$ | $(1,1)$ | $(0,2)$ | $(0,0)$ |  $(0,1)$     |

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

> [!problem] Problem 2.27
> Prove or disprove: if $G$ and $H$ are abelian groups, then $G\times H$ is abelian.

^88be9e

Let $G$ and $H$ be abelian groups, and consider the group $G\times H$. Let $(g_{1},h_{1}),(g_{2},h_{2}) \in G\times H$.
$$
\begin{align}
(g_{2},h_{2})(g_{1},h_{1}) &= (g_{2}g_{1},h_{2}h_{1})\\
&= (g_{1}g_{2},h_{1}h_{2}) && \text{by commutivity}.\\
&= (g_{1},h_{1})(g_{2},h_{2})
\end{align}
$$
Thus, commutativity holds for $G\times H$ and it is an abelian group.

> [!problem] Problem 2.28
> Consider the group $\mathbb{Z}_{5}^{*}\times \mathbb{Z}_{2}$. (The operation in the group on the left is multiplication modulo 5, and the operation in the group on the right is addition modulo 2.) Draw up the operation table for this group.

| $\times,+$ | $(1,0)$ | $(1,1)$ | $(2,0)$ | $(2,1)$ | $(3,0)$ | $(3,1)$ | $(4,0)$ | $(4,1)$ |
| ---------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| $(1,0)$    | $(1,0)$ | $(1,1)$ | $(2,0)$ | $(2,1)$ | $(3,0)$ | $(3,1)$ | $(4,0)$ | $(4,1)$ |
| $(1,1)$    | $(1,1)$ | $(1,0)$ | $(2,1)$ | $(2,0)$ | $(3,1)$ | $(3,0)$ | $(4,1)$ | $(4,0)$ |
| $(2,0)$    | $(2,0)$ | $(2,1)$ | $(4,0)$ | $(4,1)$ | $(1,0)$ | $(1,1)$ | $(3,0)$ | $(3,1)$ |
| $(2,1)$    | $(2,1)$ | $(2,0)$ | $(4,1)$ | $(4,0)$ | $(4,1)$ | $(1,0)$ | $(3,1)$ | $(3,0)$ |
| $(3,0)$    | $(3,0)$ | $(3,1)$ | $(1,0)$ | $(1,1)$ | $(4,0)$ | $(4,1)$ | $(2,0)$ | $(2,1)$ |
| $(3,1)$    | $(3,1)$ | $(3,0)$ | $(1,1)$ | $(1,0)$ | $(4,1)$ | $(4,0)$ | $(2,1)$ | $(2,0)$ |
| $(4,0)$    | $(4,0)$ | $(4,1)$ | $(3,0)$ | $(3,1)$ | $(2,0)$ | $(2,1)$ | $(1,0)$ | $(1,1)$ |
| $(4,1)$    | $(4,1)$ | $(4,0)$ | $(3,1)$ | $(3,0)$ | $(2,1)$ | $(2,0)$ | $(1,1)$ | $(1,0)$ |
