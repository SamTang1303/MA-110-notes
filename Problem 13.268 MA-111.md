---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.268 MA-111

> [!problem] Problem 13.268
> Suppose that $f(x) \in \mathbb{Q}[x]$ has degree 5 and is irreducible. Let $K$ be the splitting field of $f(x)$ over $\mathbb{Q}$. Explain why $\text{Gal}(K/\mathbb{Q})$ must contain a 5-cycle.

Suppose that $f(x) \in \mathbb{Q}[x]$ has degree 5 and is irreducible. Let $K$ be the splitting field of $f(x)$ over $\mathbb{Q}$. $K$ is a Galois Extension over $\mathbb{Q}$, so by [[Problem 12.237 MA-11|Problem 237]] $\left| \text{Gal}(K/\mathbb{Q}) \right|=[K:\mathbb{Q}]$. Let $\alpha$ be a root of $f(x)$. Then $[\mathbb{Q}(\alpha):\mathbb{Q}]=5$ by the Algebraic Extension Theorem. By the Degree Multiplication Theorem, $[K:\mathbb{Q}]=[K:\mathbb{Q}(\alpha)][\mathbb{Q}(\alpha):\mathbb{Q}]$. Therefore, $[K:\mathbb{Q}]=\left| \text{Gal}(K/\mathbb{Q}) \right|$ must be a multiple of 5. Cauchy's theorem says that $\text{Gal}(K/\mathbb{Q})$ must have an element of order 5, i.e., a five-cycle.
