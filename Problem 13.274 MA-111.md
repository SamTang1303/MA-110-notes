---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.274 MA-111

> [!problem] Problem 13.274
> Use [[Problem 13.273 MA-111|Problem 273]] to prove that there are no extension fields $E$ of $\mathbb{C}$ such that $[E:\mathbb{C}]=2$.

Suppose that there were an extension field $E$ of $\mathbb{C}$. Because $E$ is a prime degree extension, it must be a simple extension. Let $\alpha \in E$ such that $E=\mathbb{C}(\alpha)$. By the fundamental theorem of algebra, $\alpha$ is the root of some irreducible polynomial $p(x)=x^{2}+bx+c$ for some $b,c \in \mathbb{C}$. The quadratic formula still holds for complex polynomials, and in Problem 273 we showed that the complex numbers are closed under square roots. Thus, all quadratic polynomials in $\mathbb{C}[x]$ split. Therefore, $p(x)$ cannot be irreducible, producing a contradiction. Thus, there cannot exist an extension $E$ of $\mathbb{C}$ of degree 2.
