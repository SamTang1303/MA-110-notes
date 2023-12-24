---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.169 MA-110

> [!problem] Problem 9.169
> Let $p(x)=x^{3}+x+1 \in \mathbb{Z}_{2}[x]$.
> 1. Explain why $p(x)$ is irreducible.
> 2. Explain why $\mathbb{Z}_{2}[x]/(p(x))$ is a field.
> 3. Explain why every nonzero element of $\mathbb{Z}_{2}/(p(x))$ can be written as $f(x)+(p(x))$, where $f(x)$ has degree at most $2$.
> 4. List eight distinct elements of $\mathbb{Z}_{2}[x]/(p(x))$.

1. $p(x)$ is of degree $3$ and neither $0$ nor $1$ are roots of it, so [[Problem 9.155 MA-110|Problem 155]] says that it is irreducible.
2. $\mathbb{Z}_{2}$ is a field, so [[Problem 9.168 MA-110|Problem 168]] says that $\mathbb{Z}_{2}[x]/(p(x))$ must be a field.
3. For any polynomial $f(x)$, let $x^{n}$ be a term with degree greater than two. For the following, keep in mind that every element is its own inverse in $\mathbb{Z}_{2}[x]$$$\begin{align}x^{n}+(p(x))&=x^{n-3}x^{3} +(p(x))\\&= x^{n-3}x^{3} + x^{n-3}(x^{3}+x+1)&& \text{absorption} \\&= x^{n-3}(x+1) \\&= x^{n-2}+x^{n-3}.\end{align}$$Thus, we can rewrite any term of coset representative $f(x)$ as a lower-degree polynomial. We can continue this process inductively until we represent $f(x)+(p(x))$ with a coset representative degree $2$ or less.
4. $0,1,x,x+1,x^{2},1+x^{2},x+x^{2},1+x+x^{2}$.
