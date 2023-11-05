---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.122 MA-110

> [!problem] Problem 8.122
> Find polynomials $q(x)$ and $r(x)$ guaranteed by the division algorithm in $\mathbb{Z}[x]$ when $f(x)=4x^{3}+3x^{2}+2x+1$ and $g(x)=x^{2}-x-1$. Is this the answer uniquely defined?

Let $f(x)=4x^{3}+3x^{2}+2x+1$ and $g(x)=x^{2}-x-1$.
$$
\begin{align}
f(x)=4x^{3}+3x^{2}+2x+1 &= (4x+7)(x^{2}-x-1) + (13x+8). \\
\end{align}
$$
So, $(4x+7)$ is the quotient and $13x+8$ is the remainder.

This answer is unique. In order for the product of the quotient and $g(x)$ to be of order $3$, the quotient must be of order $1$. The $x$ coefficient must be $4$ in order to guarantee the $x^{3}$ term in the product also has a remainder of $4$. Further once the $x$ coefficient in the quotient is fixed, in order for the $x^{2}$ term in the product to have a coefficient of $3$, the constant term in the quotient must be $7$. Once the product of the quotient and $g(x)$ is fixed, the remainder can only have one value.