---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.85 MA-110

> [!problem] Problem 5.85
> Let $G=\langle a\rangle$, where $\langle a\rangle$ has order $n$. Use the result of [[Problem 5.84 MA-110|Problem 84]] and the homomorphism of [[Problem 3.42 MA-110|Problem 42]] to prove that $\mathbb{Z}/\langle n\rangle\simeq G$.

Let $G=\langle a\rangle$ where $a$ has order $n$ and suppose $\phi: \langle \mathbb{Z},+\rangle \longrightarrow \langle G, \cdot\rangle$ such that $\phi(i)=a^{i}$. From Problem 42, we know $\phi$ is a homomorphism.

Since $G=\langle a\rangle$, $e=a^{n}$, and $a^{k}=e$ if and only if $k$ is a multiple of $n$ (i.e. in $\langle n\rangle$.) Therefore, $\ker(\phi)$ is exactly equal to $\langle n\rangle$. So, [[Problem 5.84 MA-110|The First Isomorphism Theorem]] tells us $\mathbb{Z}/\langle n\rangle \simeq G$.