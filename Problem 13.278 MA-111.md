---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.278 MA-111

> [!problem] Problem 13.278
> Let $p(x) \in \mathbb{R}[x]$, and let $E$ be the splitting field of $(x^{2}+1)p(x)$ over $\mathbb{R}$. Notice that $E$ contains $\mathbb{C}$. Use [[Problem 13.277 MA-111|Problem 277]] to prove that $\left| \text{Gal}(E/\mathbb{C}) \right|=2^{k}$ for some $k\geq0$.

Let $p(x) \in \mathbb{R}[x]$, let $E$ be the splitting field of $(x^{2}+1)p(x)$ over $\mathbb{R}$, and let $K$ the splitting field of $p(x)$ over $\mathbb{R}$. Because $E$ is the splitting field of $(x^{2}+1)p(x)$ over $\mathbb{R}$, it must contain $i$ as well as all the real numbers, i.e., $\mathbb{C}\subseteq E$.

[[Problem 13.277 MA-111|Problem 277]] says that $[E:\mathbb{R}]=2^{k}$ for some $k \in \mathbb{N}$. By the Degree Multiplication Theorem,
$$
[E:\mathbb{C}] = \frac{[E:\mathbb{R}]}{[\mathbb{C}:\mathbb{R}]}= \frac{2^{k}}{2}=2^{k-1}.
$$
Therefore, [[Problem 12.237 MA-11|Problem 237]] says that $\left| \text{Gal}(E/\mathbb{C}) \right|=2^{k-1}$ as well.
