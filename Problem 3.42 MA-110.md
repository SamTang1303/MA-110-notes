---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.42 MA-110

> [!problem] Problem 3.42
> Let $G=\langle a\rangle$, where $a$ has order $n$. Define a map $\phi: \langle \mathbb{Z},+\rangle \longrightarrow \langle G, \cdot\rangle$ by $\phi(i)=a^{i}$. Prove that $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]], but isn't one-to-one.

Let $G=\langle a\rangle$ where $a$ has order $n$ and suppose $\phi: \langle \mathbb{Z},+\rangle \longrightarrow \langle G, \cdot\rangle$ such that $\phi(i)=a^{i}$.

Let $x,y \in \mathbb{Z}$.
$$
\begin{align}
\phi(x) \cdot \phi (y) &= a^{x} \cdot a^{y}\\
&= a^{x+y}\\
&= \phi(x+y).
\end{align}
$$
Therefore, $\phi$ is a homomorphism.

$\phi$ cannot be one-to-one because $\mathbb{Z}$ is a countably infinite set, so $G$ would have to be as well, but we know $G$ is finite with order $n$. 
