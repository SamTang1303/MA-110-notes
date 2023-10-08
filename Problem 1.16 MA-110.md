---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.16 MA-110

> [!problem] Problem 1.16
> 
> Suppose $G$ is a group, with $a \in G$. Using notation like
> $$
> a^{n} = \underbrace{a*a* \cdots*a}_{n}
> $$
> give an informal argument that $a^{m}a^{n}=a^{m+n}$ and $(a^{m})^{n}=a^{mn}$ for all $m,n \in \mathbb{N}$. (It is tedious, but not hard, to show that these statements hold for $m,n \in \mathbb{Z}$ as well. A formal proof requires induction.)

Let $G$ be a group, $a \in G$, and $m,n \in \mathbb{N}$.
$$
\begin{align}
a^{n}*a^{m} &= (\underbrace{ a*a*\cdots  *a }_{ n }) * (\underbrace{ a*a *  \cdots*a }_{ m }) && \text{associativity}\\
&= \underbrace{ a*a*  \cdots*a }_{ n+m }\\
&= a^{n+m}
\end{align}
$$
Similarly,
$$
\begin{align}
(a^{m})^{n} &= (\underbrace{ a*a*\cdots  *a }_{ m })^{n}\\
&= \overbrace{ (\underbrace{ a*a*\cdots  *a }_{ m }) * (\underbrace{ a*a*\cdots  *a }_{ m }) *  \cdots*(\underbrace{ a*a*\cdots  *a }_{ m }) }^{n}\\
&= \underbrace{ a*a *  \cdots *a }_{ m*n }\\
&= a^{mn}.
\end{align}
$$
