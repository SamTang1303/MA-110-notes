---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.184 MA-111

> [!problem] Problem 10.184
> Let $G$ be a group of order $np$, where $p$ is prime and $n \in \mathbb{N}$. Let
> $$
> X=\{ (g_{0},g_{1},g_{2},\dots,g_{p-1}) \mid g_{i} \in  G \text{ and } g_{0}g_{1}g_{2}\cdots g_{p-1} = e \}
> $$
> be the set of all $p$-tuples of elements of $G$ whose product in the identity. Compute $\left| X \right|$. By [[Problem 10.178 MA-111|Problem 178]], the group $\mathbb{Z}_{p}$ acts on $X$ by shifting: $\phi_{k}(g_{0},g_{1},\dots,g_{p-1})$, where the subscripts are taken modulo $p$. Show that this action has a fixed point, then use the class equation to show that it must have more than one fixed point.

There will be $(np)^{k-1}$ different $k$-tuples of elements whose product is any given $g \in G$. (This can be proved inductively using the "sudoku property".) Thus $X$ has order $(np)^{p-1}$. The $p$-tuple consisting of entirely the identity element, $(e,e,e,\dots,e)$ will clearly be a fixed point under the actions of $\mathbb{Z}_{p}$. Because $\left| \mathbb{Z}_{p} \right|=p$, [[Problem 10.182 MA-111 (Presenter)|Problem 182]] says
$$
\left| X_{\mathbb{Z}_{p}} \right| \equiv \left| X \right| =n^{k-1}p^{k-1} \equiv0 \text{ mod }p.
$$
Thus, because $\left| X_{\mathbb{Z}_{p}} \right|$ is not zero, it must be a multiple of $p$ and greater than 0.
