---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.142 MA-110

> [!problem] Problem 8.142
> Let $I=(x^{2}+x+1)$ in $\mathbb{Q}[x]$. Find the multiplicative inverse of $x+1+I$ in $\mathbb{Q}[x]/I$, or explain why no such inverse exists.

Let $I=(x^{2}+x+1)$ in $\mathbb{Q}[x]$.
$$
\begin{align}
(x+1)(-x) +I&= -x^{2}-x  +I\\
&= -x^{2}-x +(x^{2}+x+1) +I&& \text{absorption}\\
&= 1+I. 
\end{align}
$$
Therefore, $-x$ is the multiplicative inverse of $x+1$ in $\mathbb{Q}[x]/I$.
