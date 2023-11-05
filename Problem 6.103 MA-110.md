---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 6.103 MA-110

> [!problem] Problem 6.103
> Let $R$ be the set of all real-valued functions on $\mathbb{R}$. That is, $\{ R=f\ |\ f:\mathbb{R}\longrightarrow \mathbb{R} \}$. Such functions can be added and multiplied *pointwise*: If $f$ and $g$ are functions, then $f+g$ and $f \cdot g$ are functions defined by the formulas $(f+g)(x)=f(x) + g(x)$ and $(f \cdot g)(x)=f(x)g(x)$. With these operations, $R$ is a commutative ring.
> 1. Prove that the set $I=\{ f \in R : f(3)=0 \}$ is an ideal of $R$.
> 2. Prove that the set $J = \{ f \in R  : f(3)=1\}$ is not an ideal of $R$.

Let $R$ be the set of all real-valued functions on $\mathbb{R}$. 

1 ) Let $I$ be the set $I=\{ f \in R : f(3)=0 \}$. Then $I$ contains the constant function $0$, which is the identity of $R$.

Let $f \in I$. Consider the additive inverse of $f$, $-f$.
$$
-f(3) = -f(3)=-0=0.
$$
Therefore, $-f \in I$ as well and $I$ is closed under additive inverses.

Let $f,g \in I$. Then $f(3)=0$ and $g(3)=0$.
$$
(f+g)(3) = f(3)+ g(3) = 0 + 0=0.
$$
Further,
$$
(f \cdot g)(3) = f(3)g(3)=0 \cdot 0 =0.
$$
Therefore $f+g$ and $f \cdot g$ are in $I$, and $I$ is closed under addition and multiplication. Thus it is a subring of $R$.

Let $f \in I$ and $g \in R$. Then $f(3)=0$.
$$
(f \cdot g)(3) = f(3)g(3) = 0 \cdot g(3)=0.
$$
Therefore $f \cdot g \in R$. Because $R$ is commutative, $g \cdot f \in R$ as well, and $I$ must be an ideal of $R$.

3 ) Let $J$ be the set $J = \{ f \in R  : f(3)=1\}$. We will show $J$ not to be an ideal by counterexample. Consider the functions $f \in I$ and $g \in R$ such that $f(x)=1$ and $g(x)=2$. Then $(f \cdot g)(x)=f(x)g(x)=1 \cdot2=2$. The constant function $2$ clearly is not in $J$, and thus $J$ cannot be an ideal of $R$.