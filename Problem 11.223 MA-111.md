---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.223 MA-111

> [!problem] Problem 11.223
> Show that a homomorphism of fields must be injective if it isn't trivial.

Suppose that $\phi:F_{1} \longrightarrow F_{2}$, a homomorphism of fields, is not injective. Then there exists some $a,b$ such that $a\neq b$ and $\phi(a)=\phi(b)$. This implies $a-b\neq0$.
$$
\begin{align}
\phi(a-b)&= \phi(a)-\phi(b) \\
&= \phi(a)-\phi(a) \\
&= 0.
\end{align}
$$
Thus $a-b \in \ker(\phi)$. This means the kernel of $\phi$ is non-trivial. But, [[Problem 6.101 MA-110|Problem 101]] shows the kernel is an ideal of $F_{1}$. [[Problem 8.120 MA-110|Problem 120]] says that the only non-trivial ideal of $F_{1}$ is itself, implying that $\phi$ is trivial.
