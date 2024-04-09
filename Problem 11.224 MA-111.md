---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.224 MA-111

> [!problem] Problem 11.224
> Show (without using the upcoming theorem) that there are no nontrivial field homomorphisms $\mathbb{Q}(\sqrt{ 2 }) \longrightarrow\mathbb{Q}(\sqrt{ 3 })$.

Suppose to the contrary that $\phi:\mathbb{Q}(\sqrt{ 2 }) \longrightarrow \mathbb{Q}(\sqrt{ 3 })$ is a nontrivial field homomorphism. [[Problem 11.222 MA-111|Problem 222]] says that $\phi$ fixes the rationals.

Consider $\phi(\sqrt{ 2 })$. We know that it cannot equal any rational $x$, otherwise $\phi(\sqrt{ 2 })=\phi(x)=x$ and [[Problem 11.223 MA-111|Problem 223]] would say that $\phi$ is trivial. Thus, $\phi(\sqrt{ 2 })=a+b\sqrt{ 3 }$ for $a \in \mathbb{Q}$, $b \in \mathbb{Q}\setminus \{ 0 \}$. 

$$
\begin{align}
2&= \phi(2) \\
&= \phi(\sqrt{ 2 } \cdot \sqrt{ 2 }) \\
&= \phi(\sqrt{ 2 })\phi(\sqrt{ 2 }) \\
&= (a+b\sqrt{ 3 })^{2} \\
&= (a^{2}+3b^{2})+(2ab)\sqrt{ 3 }.
\end{align}
$$
Because $b$ is nonzero, for $2ab=0$, $a$ must be $0$. This implies $3b^{2}=2\iff b^{2}=\frac{3}{2}$. Because $b$ is rational, this is impossible and we have reached a contradiction. Therefore, no such nontrivial field homomorphism from $\mathbb{Q}(\sqrt{ 2 })\longrightarrow\mathbb{Q}(\sqrt{ 3 })$ can exist.
