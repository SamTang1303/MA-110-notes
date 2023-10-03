---
aliases: []
tags:
  - batch/school/class/ma110
  - subject/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-06
# Pre-Work Problems 29 Through 34 MA-110

> [!problem] Problem 2.29
> 1. Identify all of the subgroups of $\langle \mathbb{Z},+\rangle$
> 1. Identify all of the subgroups of $\langle \mathbb{Z}_{6}, +\rangle$
> 1. Identify all of the subgroups of $\langle \mathbb{Z}_{5}^{*},\times \rangle$

^1df4b6

1 ) A group $G$ is a subgroup of $\langle \mathbb{Z}, +\rangle$ if and only if it is of the form $\langle \{ n \cdot m : m \in \mathbb{Z} \}, +\rangle$  where $n \in \mathbb{N}$ (the set of all factors of $n$ with operation addition.) I can prove this but it's a little tedious, and the problem only asks to identify the groups. 

2 ) $\{ 0 \},\{ 0,2,4 \}, \{ 0,3 \}, \text{ and } \mathbb{Z}_{6}$ are all the possible subgroups of $\mathbb{Z}_{6}$ under addition.

3 ) $\{ 1 \}, \{ 1,4 \}$ are all the possible subgroups of $\mathbb{Z}_{5}^{*}$ under multiplication.

> [!problem] Problem 2.30
> Find five different subgroups $S_{4}$, all of different orders.

$$
\begin{align}
&\{ (1) \} \text{ (order 1)}, \\
&\{ (1),  (1\,2\,3), (1\,3\,2)\} \text{ (order 3)},\\
& \{ (1)\, (1\,2\,3\,4), (1\,3) (2 \, 4), (1\,4\, 3\, 2) \} \text{ (order 4)},\\
&\{ (1),  (1\,2\,3), (1\,3\,2), (2 \, 3), (1 \, 2), (1 \, 3)\} \text{ (order 6)},\\
&S_{5}(\text{order 24}) 
\end{align}
$$

<div class="page-break" style="page-break-after: always;"></div> 

> [!problem] Problem 2.31
> In the introductory activity, we saw that the elements of the group $D_{4}$ can be written in cycle notation, and that composition of permutations corresponds to the composition of symmetries. Use cycle notation and permutation composition to do this problem.
> 1. Identify all the subgroups of $D_{4}$.
> 2. Based on the results of this problem and the previous two problems, formulate a conjecture about the order of a subgroup compared to the order of the group.

1 )
$$
D_{4} = \{ (1), (1 \, 2 \, 3), (1 \, 3 \, 2), (1 \, 2), (2 \, 3), (1 \, 3) \} \qquad \text{(order 6)}
$$
This has subgroups of
$$
\begin{align}
\{ (1) \} &\text{ (order 1)},\\
\{ (1), (1 \, 2) \}, &\text{ (order 2)},\\
\{ (1), (1 \, 3) \}, &\text{ (order 2)},\\
\{ (1), (2 \, 3) \}, &\text{ (order 2)},\\
\{ (1), (1 \, 2 \, 3) (1 \, 3 \, 2) \} &\text{ (order 3)},\\
D_{4} &\text{ (order 6)}.
\end{align}
$$
2 ) Based on the results of this problem and problems 29 and 30, I would conjecture that the order of a subgroup must be a factor of the "parent" group.

> [!problem] Problem 2.32
> Prove that if $H$ and $K$ are subgroups of a group $G$, then their intersection $H\cap K$ is a subgroup of $G$.

Let $H$ and $K$ be subgroups of a group $G$. Consider the set $H\cap K$ with operation defined similarly to $G$.

$G$ is a group, so it must have an identity element $e$. $H$ and $K$ are both subgroups, so by definition they must also contain $e$. Thus $e \in H\cap K$.

Let $x,y \in H\cap K$. By definition of the intersection operator, $x,y \in H$ *and* $x,y \in K$. $H$ is a subgroup, it is closed under its operation, and $xy \in H$. Similarly, $xy \in K$. Thus,
$xy \in H\cap K$, implying $H\cap K$ is closed under the operation of $G$.

Let $z \in H\cap K$ (i. e. $z \in H$ and $z \in K$.) By the definition of a subgroup $z^{-1} \in H$ and $z^{-1} \in K.$ Therefore, $z^{-1} \in H\cap K$ and $H\cap K$ is closed under taking inverses.

Thus $H\cap K$ fulfill all the requirements for a subgroup of $G$.

> [!problem] Problem 2.33
> Suppose $G$ and $H$ are groups, with $S$ a subgroup of $G$, and $T$ a subgroup of $H$. Prove or disprove as appropriate: $S\times T$ is a subgroup of $G\times H$.

Let $G$ and $H$ be groups with $S$ a subgroup of $G$ and $T$ a subgroup of $H$. We will prove $S\times T$ is a subgroup of $G\times H$ with operation defined component-wise.

Let $(e_{G},e_{H})$ be the identity element of $G\times H$. Consider an arbitrary $(g,h) \in G\times H$. By definition of an identity,
$$
(g,h)(e_{G},e_{H})  = (ge_{G}, he_{H}) = (g,h),
$$
implying $ge_{G}=g$ and $he_{H}=h$. We could argue similarly to show $e_{G}g=g$ and $e_{H}h=h$. Therefore, $e_{G}$ and $e_{H}$ must be the identities of $G$ and $H$ respectively. By the definition of a subgroup, $S$ must contain $e_{G}$ and $T$ must contain $e_{H}$. Therefore, $(e_{G},e_{H}) \in S\times T$ and the first criterion for $S\times T$ being a subgroup is satisfied.

Let $(s_{1},t_{1}), (s_{1},t_{2}) \in S\times T$. By definition, $s_{1},s_{2} \in S$ and $t_{1}, t_{2} \in T$. By definition of a subgroup $s_{1}s_{2} \in S$ and $t_{1}t_{2} \in T$. So, $(s_{1},t_{1})(s_{2},t_{2}) = (s_{1}s_{2},t_{1}t_{2}) \in S\times T$. Therefore, $S\times T$ is closed under the operation of $G\times T$.

Finally, let $(s,t) \in S\times T$. Thus, $s \in S$ and $t \in T$. Because $S$ and $T$ are both subgroups, $s ^{-1} \in S$, $t^{-1} \in T$, and $(s ^{-1}, t^{-1}) \in S\times T$.
$$
(s,t)(s ^{-1}, t^{-1}) = (s s ^{-1}, t t^{-1}) = (e_{G}, e_{H}). \text{ The reverse order of mulitplication is shown similarly.}
$$
We have already shown this to be the identity of $S\times T$ and in $S\times T$, so this is the last piece needed to show $S\times T$ is a subgroup of $G\times H$.

> [!problem] Problem 3.34
> Let $H$ be a subgroup of a group $G$, and let $x \in G$ be some element. The *conjugate* of $H$ by $x$ is the set $xHx^{-1}=\{ xHx^{-1}:h \in H \}$. Prove that $xHx^{-1}$ is also a subgroup of $G$.

Let $H$ be a subgroup of a group $G$ and $x \in G$. Consider the conjugate of $H$ by $x$, $xHx^{-1}$.

Let $e_{G}$ be the identity of $G$. By the definition of a group $e_{G} \in G$. To show $e_{G} \in xHx^{-1}$ we must find some element $h \in H$ such that $xhx^{-1} =e_{G}$. Set $h=e_{G}$
$$
xe_{G}x^{-1} = (xe_{G})x^{-1}=xx^{-1} = e_{G}.
$$
Thus $e_{G} \in xHx^{-1}$.

Let $a, b \in xHx^{-1}$. By definition of the conjugate, for some $\overline{a},\overline{b} \in H$, $a=x\overline{a}x^{-1}$ and $b=x\overline{b}x^{-1}$. By definition of a group, $\overline{a}\overline{b} \in H$.
$$
\begin{align}
ab &= (x\overline{a}x^{-1})(x\overline{b}x^{-1})\\
&= (x\overline{a})(x^{-1}x)(\overline{b}x^{-1})\\
&= (x\overline{a})(\overline{b}x^{-1})\\
&= x(\overline{a} \overline{b})x^{-1} \in  xHx^{-1}.
\end{align}
$$

Let $y \in xHx^{-1}$. Then, for some $\overline{y} \in H$, $y=x\overline{y}x^{-1}$. By definition of a subgroup, $\overline{y}^{-1}$ exists and is in $H$.
$$
\begin{align}
y (x\overline{y}^{-1}x^{-1}) &= (x\overline{y}x^{-1})(x\overline{y}^{-1}x^{-1})\\
&= (x\overline{y})(x^{-1}x)(\overline{y}^{-1}x^{-1})\\
&= (x\overline{y})(\overline{y}^{-1}x^{-1})\\
&= x(\overline{y}\overline{y}^{-1})x^{-1}\\
&= x x^{-1}\\
&= e_{G}.
\end{align}
$$
We can similarly show that $(x\overline{y}^{-1}x^{-1})y=e_{G}$. Because we have shown $e_{G}$ to be the identity of $xHx^{-1}$, it is closed under inverses and satisfies all of the criteria to be a subgroup of $G$.