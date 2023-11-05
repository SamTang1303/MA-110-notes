---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.115 MA-110

> [!problem] Problem 7.115
> Let $R$ be a ring with unity. Prove that $R$ has a subring that is isomorphic to either $\mathbb{Z}$ or $\mathbb{Z}/(n)$ for some $n$.

Let $R$ be a ring with unity. Consider the map $\phi: \mathbb{Z}\longrightarrow R$ defined by the formula
$$
\phi(n) = 1 \cdot n.
$$
**Note that the  multiplication used here is repeated ring addition, not ring multiplication**. First, we will show $\phi$ is a [[Problem 6.97 MA-110|ring homomorphism]]. Let $n,m \in \mathbb{Z}$.
$$
\phi(n) + \phi(m) = 1n + 1m = 1(n+m) = \phi(n+m).
$$
Further,
$$
\begin{align}
\phi(n) \cdot \phi(m) &=(1 \cdot n)  (1 \cdot m) \\
&= \underbrace{(1+1+\cdots+1)}_{n}\underbrace{(1+1+\cdots+1)}_{m} \\
&= \underbrace{1\underbrace{(1+\cdots+1)}_{n} + 1\underbrace{(1+\cdots+1)}_{n} + \cdots 1\underbrace{(1+\cdots+1)}_{n}}_{m} && \text{distributing} \\
&= \underbrace{(1+\cdots+1)}_{n \cdot m} \\
&=\phi(n \cdot m).
\end{align}
$$
Therefore, $\phi$ is a homomorphism.

An element $n \in \mathbb{Z}$ is in the kernel if and only if $1 \cdot n=0$. This is true if and only if $n$ is a multiple of the order of $\langle 1\rangle$ (where the only multiple of the order of an infinite group is $0$). Therefore, the kernel of $\phi$ is exactly $(k)$, where $k$ is the order of the group if it is finite, and $0$ if it is infinite. Then [[Problem 7.113 MA-110|The First Ring Isomorphism Theorem]] tells us
$$
\mathbb{Z}/(k) =\mathbb{Z}/\ker(\phi) \simeq \phi(\mathbb{Z}).
$$
Observe that $\phi(\mathbb{Z})$ must be a subring of $R$ because $\phi$ is a ring homomorphism.