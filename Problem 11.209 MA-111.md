---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.209 MA-111

> [!problem] Problem 11.209
> Let $F(\alpha)$ be an algebraic extension of $F$, where $\text{Irr}(\alpha,F)$ has degree $n\geq1$. Suppose that $\beta \in F(\alpha)$. Regard $F(\alpha)$ as a vector space over $F$. Find a result from linear algebra to explain why the set $\{ 1,\beta,\beta^{2},\dots,\beta^{n} \}$ is a dependent set.

Let $F(\alpha)$ be an algebraic extension of $F$, where $\text{Irr}(\alpha,F)$ has degree $n\geq1$. Suppose that $\beta \in F(\alpha)$. Regard $F(\alpha)$ as a vector space over $F$.

The Algebraic Extension Theorem says that $F(\alpha)$ is a vector space over $F$ with dimension $n$. From linear algebra we know that any set of basis vectors must have the same size. Thus $\{ 1,\beta,\beta^{2},\dots \beta^{n} \}$ cannot be independent, because if it were it would be a basis of size $n+1$.
