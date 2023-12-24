---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.132 MA-110

> [!problem] Problem 8.132
> Let $a_{1},a_{2},\dots, a_{n} \in R$, a commutative ring. Prove that $(a_{1},a_{2},\dots,a_{n})$ is an ideal of $R$.

Let $a_{1},a_{2},\dots, a_{n} \in R$, a commutative ring.

$0 \in (a_{1},a_{2},\dots,a_{n})$ if we chose all the $r$ coefficients to be zero. Thus it contains the identity of $R$.

Let $x=x_{1}a_{1}+x_{2}a_{2}+\dots x_{n}a_{n} \in (a_{1},a_{2},\dots,a_{n})$ and $y=y_{1}a_{1}+y_{2}a_{2}+\dots y_{n}a_{n} \in (a_{1},a_{2},\dots,a_{n})$.
$$
\begin{align}
x+y &= x_{1}a_{1}+x_{2}a_{2}+\dots x_{n}a_{n} + y_{1}a_{1}+y_{2}a_{2}+\dots y_{n}a_{n} \\
&= (x_{1}+y_{1})a_{1} + (x_{2}+y_{2})a_{2} + \dots+(x_{n}+y_{n})a_{n} \\
&\in  (a_{1},a_{2},\dots,a_{n})
\end{align}
$$
Thus, $(a_{1},a_{2},\dots,a_{n})$ is closed under addition. Further,
$$
\begin{align}
x \cdot y &=  x(y_{1}a_{1}+y_{2}a_{2}+\dots y_{n}a_{n})\\
&= xy_{1}a_{1} + xy_{2}a_{2} + \dots xy_{n}a_{n} \\
& \in  (a_{1},a_{2},\dots,a_{n}).
\end{align}
$$
Thus $(a_{1},a_{2},\dots,a_{n})$ is closed under multiplication as well. Finally, we show that $-x_{1}a_{1}-x_{2}a_{2}-\dots-x_{n}a_{n}$ is the additive inverse of $x_{1}a_{1}+x_{2}a_{2}+\dots x_{n}a_{n}$.
$$
\begin{align}
x_{1}a_{1}+x_{2}a_{2}+\dots x_{n}a_{n}-x_{1}a_{1}-x_{2}a_{2}-\dots-x_{n}a_{n} = 0 + 0 +\dots0 =0.
\end{align}
$$
Thus $(a_{1},a_{2},\dots,a_{n})$ is closed under additive inverses as well.

Let $r \in R$. Then
$$
\begin{align}
rx &= r(r_{1}a_{1}+r_{2}a_{2}+\dots+r_{n}a_{n}) \\
&= rr_{1}a_{1} + rr_{2}a_{2} + \dots + rr_{n}a_{n} \\
&= r'_{1}a_{1} + r'_{2}a_{2} + \dots +r'_{n}a_{n} && \text{for some }r'_{1},\dots,r'_{n} \in  R \\
&\in (a_{1},a_{2},\dots,a_{n}). &&\text{definition of linear combination}
\end{align}
$$
Because $R$ is a commutative ring, we can argue similarly to show $rx \in (a_{1},a_{2},\dots,a_{n})$. Thus $(a_{1},a_{2},\dots,a_{n})$ is an ideal of $R$.