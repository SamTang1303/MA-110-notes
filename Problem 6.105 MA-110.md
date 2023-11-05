---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 6.105 MA-110

> [!problem] Problem 6.105
> Let $R$ be a commutative ring. Fix an element $a \in R$. Define the set $I \subseteq R$ by $I=\{ ra \mid r \in R \}$. Prove that $I$ is an ideal of $R$.

1. $0 \in R$, so $0 \cdot a =0 \in I$, and $I$ contains the additive identity of $R$.
2. Let $r_{1}a,r_{2}a \in I$. $r_{1}a+r_{2}a =(r_{1}+r_{2})a$. $r_{1}+r_{2} \in R$ because $R$ is a group under addition. Therefore $r_{1}a+r_{2}a \in I$ and it is closed under addition.
3. Let $ra \in I$. $ra+(-r)a=(r+(-r))a=0 \cdot a=0$. Because $-ra \in I$, $I$ is closed under additive inverses.
Therefore, $I$ is a subgroup of $\langle R,+\rangle$. 

Let $R$ be a commutative ring and fix an element $a \in R$. Define $I\subseteq R$ by $I=\{ ra \mid r \in R \}$.

Let $b \in I$ and $r \in R$. Then
$$
\begin{align}
rb &= r(r_{1}a) && \text{for some }r_{1} \in  R; \ b \in  I \\
&= (r_{1}r)a &&\text{multiplication is associative} \\
&= r_{2}a && \text{for some }r_{2} \in  R; \text{ multiplication is closed}  \\
&= ar_{2} && R\text{ is commutative} \\
& \in  I. && \text{by definition}
\end{align}
$$
We can argue similarly to show $br \in I$ as well. Therefore, $I$ is an ideal of $R$.
