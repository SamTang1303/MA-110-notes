---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.218 MA-111

> [!problem] Problem 11.218
> Show that if $F$,$E$, and $K$ are fields with $F\subseteq E\subseteq K$, then $K$ is algebraic over $F$ if and only if $E$ is algebraic over $F$ and $K$ is algebraic over $E$.

Let $F$,$E$, and $K$ be fields with $F\subseteq E\subseteq K$.

Suppose that $K$ is algebraic over $F$. $E$ is a subset of $K$, so clearly $E$ is algebraic over $F$. Likewise, $E$ is a superset of $F$, so clearly $K$ is algebraic over $E$.

Now suppose that $E$ is algebraic over $F$ and $K$ is algebraic over $E$. Let $\alpha \in K$. We must show that $\alpha$ is the root of some polynomial in $F$. There exists a polynomial $p(x) \in E[x]$ where
$$
\begin{align}
p(x)=e_{0}+e_{1}x +e_{2}x^{2}+\dots+e_{n}x^{n} \qquad (1)
\end{align}
$$
and $p(\alpha)=0$.

We know $E$ is algebraic over $F$, so the algebraic extension theorem tells us that $F(e_{0},e_{1},\dots e_{n})$ will be a finite (and therefore algebraic) extension of $F$. Further, consider adjoining $\alpha$ to this field. Equation $(1)$ tells us that $\alpha$ is algebraic over $F(e_{0},e_{1},\dots,e_{n})$, so the Algebraic Extension Theorem says that $F(e_{0},e_{1},\dots,e_{n},\alpha)$ is a finite (and therefore algebraic) extension of $F$. Thus, there exists some polynomial in $F[x]$ such that $\alpha$ is a root.
