---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.276 MA-111

> [!problem] Problem 13.276
> Use [[Problem 13.275 MA-111|Problem 275]] to prove that there are no extension fields $E$ of $\mathbb{R}$ such that $[E:\mathbb{R}]$ is odd.

Suppose to the contrary that $E$ were an extension of $\mathbb{R}$ such that $[E:\mathbb{R}]$ is odd. Then, for some $\alpha \in E\setminus \mathbb{R}$, $[\mathbb{R}(\alpha):\mathbb{R}]$ will be odd. By the algebraic extension theorem, this implies that $\alpha$ is the root of an irreducible polynomial $p(x)$ of degree $[\mathbb{R}(\alpha):\mathbb{R}]$. But, because $p(x)$ is of odd degree, Problem 275 says it will have a real root, contradicting it being irreducible. Thus, there cannot be any extension of $\mathbb{R}$ of odd degree.
