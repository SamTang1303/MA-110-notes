---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.277 MA-111

> [!problem] Problem 13.277
> Let $E$ be a splitting field over $\mathbb{R}$ such that $[E:\mathbb{R}]=2^{n}m$, where $m$ is odd. Use [[Problem 12.237 MA-11|Problem 237]], Sylow Theorem I, and [[Problem 13.276 MA-111|Problem 276]] to prove that $m=1$.

Let $E$ be a splitting field over $\mathbb{R}$ such that $[E:\mathbb{R}]=2^{n}m$, where $m$ is odd. Problem 237 says that $\left| \text{Gal}(E/\mathbb{R}) \right|=[E:\mathbb{R}]=2^{n}m$. Sylow Theorem I says that there exists a subgroup of order $2^{n}$, call it $H$. By the Galois correspondence,
$$
[E_{H}:\mathbb{R}]=[\text{Gal}(E/\mathbb{R}):H]=\frac{2^{n}m}{2^{n}}=m.
$$
Therefore, $E_{H}$ is an extension of $\mathbb{R}$ of degree $m$, where $m$ is odd. By [[Problem 13.276 MA-111|Problem 276]], this implies that $m=1$.
