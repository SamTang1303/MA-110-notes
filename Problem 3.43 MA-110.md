---
aliases: []
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.43 MA-110

> [!problem] Problem 3.43
> Let $G=\langle a\rangle$, where $a$ has in infinite order. Define a map $\phi: \langle \mathbb{Z},+\rangle\longrightarrow\langle G, \cdot\rangle$ by $\phi(i)=a^{i}$. Prove that $\phi$ is an [[Definition 3.1.2 MA-110|isomorphism]].

Let $G=\langle a\rangle$ with identity $e$ where $a$ has infinite order and suppose $\phi: \langle \mathbb{Z},+\rangle \longrightarrow \langle G, \cdot\rangle$ such that $\phi(i)=a^{i}$.

None of our work in [[Problem 3.42 MA-110|Problem 42]] showing $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]] relies on $G$ having finite order, so we know it must also be a homomorphism when $G$ has infinite order. So, we must only show $\phi$ is bijective.

Let $n,m \in \mathbb{Z}$. and suppose $\phi(n)=\phi (m)$. Then,
$$
\begin{align}
a^{n}&=a^{m}\\
a^{n}a^{-n} &=  a^{m}a^{-n}\\
e&= a^{m-n} && \text{Problem 16}
\end{align}
$$
Clearly $m=n$ satisfies this equation, but we must address the possibility that the equation is also satisfied for distinct $m$ and $n$. 

If this were the case, we would have $e=a^{k}$ for some $k\neq0$. Let $h \in G$ be arbitrary. We can represent $h=a^{r}$ in the following form: $a^{kp + v}$, where $p \in \mathbb{Z}$ and $v \in \{ 1,\dots k \}$ ($p$ being the quotient of $r/k$ and $v$ the remainder.) So,
$$
\begin{align}
a^{kp+v} &= a^{kp}a^{v}\\
&= (a^{k})^{p}a^{v}\\
&= e^{p}a^{v}\\
&= ea^{v}\\
&= a^{v}.
\end{align}
$$
This implies every element of $G$ can be represented in the form $a^{v}$ where $v \in \{1 \dots k  \}$. This is impossible because it would create a surjection from a finite set to an infinite set. Therefore, it must be true that $m=n$ and $\phi$ is one-to-one. (Sorry for the clunky proof; I couldn't think of a more elegant way to put it.)

We must now show $\phi$ is onto. Let $g \in G$. By the definition of a cyclic group, $g=a^{m}$ for some $m \in \mathbb{Z}$. Therefore, $\phi(m)=a^{m}=g$. Thus, $\phi$ must be onto as well, proving it is bijective and an isomorphism
