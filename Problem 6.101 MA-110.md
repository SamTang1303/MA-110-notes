---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Problem 6.92 MA-110]]"
---
# Problem 6.101 MA-110

> [!problem] Problem 6.101
> Let $\phi:R \longrightarrow S$ be a ring homomorphism, and let $K=\ker(\phi)$.
> 1. Explain why $\langle K,+\rangle$ is a subgroup of $\langle R,+\rangle$.
> 2. Prove that, if $k \in K$ and $r \in R$, then $kr \in K$ and $rk \in K$.
> Explain how the result you just proved shows that $K$ is a [[Problem 6.96 MA-110|subring]] of $R$, and in fact is a stronger condition.

Let $\phi:R \longrightarrow S$ be a ring homomorphism, and let $K=\ker(\phi)$.

1 ) Consider $\langle K,+\rangle$. Because $\phi$ is a ring homomorphism, $\phi(0_{R})=0_{S}$, meaning $0_{R} \in \ker(\phi)$. We know $\langle K,+\rangle$ is closed under multiplication and inverses because kernels are groups. Therefore, $\langle K, +\rangle \leq \langle R,+\rangle$.

2 ) Let $k \in K$ and $r \in R$.
$$
\begin{align}
\phi(kr) &= \phi(k)\phi(r) && \text{definition of ring homomorphism} \\
&= 0_{S}\phi(r) && \text{definition of kernel} \\
&= 0_{S}. && \text{Problem 92}
\end{align}
$$
This shows $kr \in \ker(\phi)=K$. We can argue similarly to show $rk \in K$.

We already know $K$ contains the additive identity of $R$, is closed under additive inverses, and is closed under the addition of $R$, because it is a subgroup of $R$. As we have now shown it is also closed under multiplication, it must be a subring of $R$. Moreover, we have shown that not only any two elements of $K$ multiplied together will yield an element of $K$, we have shown that every element of $K$ multiplied by any element of the larger group $R$ will also yield an element in $K$—a stronger condition than just closure under multiplication.
