---
aliases:
  - cosets have the same order
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 4.1 and 5.1 MA-110|coset]]"
---
# Problem 4.62 MA-110

> [!problem] Problem 4.62
> Suppose $G$ is a group, $H$ subgroup of $G$, and $a$ an element of $G$. Consider the function $f:H\longrightarrow aH$ defined by $f(h)=ah$ for all $h \in H$. Prove that $f$ is one-to-one and onto. Explain why this implies that, for all $x,y \in G$, $\left| xH \right|=\left| yH \right|$.

Suppose $G$ is a group, $H$ subgroup of $G$, and $a$ an element of $G$. Consider the function $f:H\longrightarrow aH$ defined by $f(h)=ah$ for all $h \in H$.

Let $x,y \in H$ and suppose that $f(x)=f(y)$. This implies
$$
\begin{align}
ax &= ay \\
x&= y. && \text{right cancellation}
\end{align}
$$
Therefore, $f$ is one-to-one.

Let $z \in aH$. By definition, there must be some $h \in H$ such that $ah =z$. $f(z)=ah=z$. Therefore $f$ is onto.

Let $x,y$ be elements of $G$. We have just shown there are bijections $f_x:H\longrightarrow xH$ and $f_{y}:H\longrightarrow yH$. The inverse of a bijection is a bijection, and the composition of two bijections is a bijection. Thus, $f_{x}\circ f_{y}^{-1}:yH\longrightarrow xH$ is a bijection. Two sets are defined to have the same order if there exists a bijection between them.
