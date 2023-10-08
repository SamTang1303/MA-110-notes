---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.13 MA-110

> [!problem] Problem 1.13
> Suppose $G$ is a group, with $a$ and $b$ in $G$. Prove that if $a*b=e$, then $b*a=e$. Use this to prove that if $G$ is a group, with $a$ and $b$ in $G$ and $a*b=e$, then $a$ is the inverse of $b$.

^f23d7c

Let $\langle G, *\rangle$ be a group with $a,b \in G$ and suppose $a*b = e$. Because $\langle G,*\rangle$ is a group, $a^{-1}$ exists and is we can apply it to both sides and preserve equality.
$$
\begin{align}
a^{-1}*a*b &= a^{-1}*e\\
b&= a^{-1}
\end{align}
$$
Thus, if $a*b=e$, then $b=a^{-1}$. By definition of an inverse, this implies $b*a=e$.
