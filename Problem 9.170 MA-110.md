---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.170 MA-110

> [!problem] Problem 9.170
> Find an element of $\mathbb{Q}[x]/(x^{2}-2)$ whose square is twice the multiplicative identity of $\mathbb{Q}[x]/(x^{2}-2)$.

$$
\begin{align}
\Big(x+(x^{2}-2)\Big)^{2}&=\Big(x+(x^{2}-2)\Big)\Big(x+(x^{2}-2)\Big) \\
&= x^{2}+(x^{2}-2) \\
&= \Big(x^{2}-(x^{2}-2)\Big) + (x^{2}-2) && \text{absorption} \\
&= 2+(x^{2}-2) \\
&= (2+(x^{2}-2))(1+(x^{2}-2)).
\end{align}
$$
Therefore, $x+(x^{2}-2)$ is an element of $\mathbb{Q}[x]/(x^{2}-2)$ whose square is twice the multiplicative identity of $\mathbb{Q}[x]/(x^{2}-2)$.
