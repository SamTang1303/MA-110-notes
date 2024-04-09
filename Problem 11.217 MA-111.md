---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.217 MA-111

> [!problem] Problem 11.217
> Let $E$ be an algebraic extension field of $F$. Let $\alpha \in E$ be algebraic of odd degree over $F$. Show that $\alpha^{2}$ is algebraic of odd degree over $F$, and $F(\alpha)=F(\alpha^{2})$.

Let $E$ be an algebraic extension field of $F$. Let $\alpha \in E$ be algebraic of odd degree over $F$. The Algebraic Extension theorem says that $\{ \alpha,\dots,\alpha^{n} \}$ is a basis for $F(\alpha)$ over $F$ for some odd natural number $n$.

By field properties, $\alpha^{2} \in F(\alpha)$. Because $\alpha$ is of finite degree, this implies that $F(\alpha)$ has a finite dimension as a vector field over $F$ by the Algebraic Extension Theorem, making it algebraic. Thus $\alpha^{2}$ is algebraic. 

The Algebraic Extension Theorem says $F(\alpha^{2})$ is a vector space over $F$ with basis $\{ \alpha^{2},\alpha^{4},\dots,\alpha^{2m} \}$ for some natural number $m$. Note that all powers of $\alpha$ are contained in $F(\alpha)$ by field properties. Therefore the basis of $F(\alpha^{2})$ over $F$, and by extension, the entire set, is contained in $F(\alpha)$. Thus $F(\alpha^{2})\subseteq F(\alpha)$. The Degree multiplication theorem says that the dimension of $F(\alpha^{2})$ as a vector space over $F$ must be a factor of the dimension of $F(\alpha)$ as a vector space over $F$.

Because a set of basis vectors is minimal, $\{ \alpha^{2},\alpha^{4},\dots,\alpha^{2m},\alpha^{2m+1} \}$ is linearly dependent. Thus, $2m+1$ must be greater than $n$, because all powers of $\alpha$ less than or equal to $n$ are linearly independent. Consider what we now know of the relation between $m$ and $n$.
- $m \mid n$.
- $n$ is odd.
- $2m \geq n$.
This forces $m=n$. Therefore, $F(\alpha )$ and $F(\alpha^{2})$ have the same dimension as vector spaces over $F$. Because we also know $F(\alpha^{2})\subseteq F(\alpha)$, they must be the same set.
