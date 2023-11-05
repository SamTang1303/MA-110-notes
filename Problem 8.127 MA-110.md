---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.127 MA-110

> [!problem] Problem 8.127
> Show that if $R$ is not an [[Definition 8.3 MA-110|integral domain]], then the uniqueness property of [[Problem 8.126 MA-110|Problem 126]] can fail. In particular, show that in $\mathbb{Z}_{4}[x]$, there are polynomials $q_{1}(x),q_{2}(x),r_{1}(x),r_{2}(x)$ and $g(x)$ with $\deg(r_{1})< \deg(g)$ and $\deg(r_{2})<\deg(g)$ and such that $q_{1}(x)\neq q_{2}(x)$ and $r_{1}(x)\neq r_{2}(x)$, but such that $q_{1}(x)g(x)+r_{1}(x)=q_{2}g(x)+r_{2}(x)$.

Consider polynomials $g(x), q_{1}(x),q_{2}(x),r_{1}(x),r_{2}(x) \in \mathbb{Z}_{4}[x]$ Such that
$$
\begin{align}
g(x) &= 2x + 1 \\
q_{2}(x) - q_{1}(x) &= 2 \\
q_{1}(x) &= 3x+1 \\
q_{2}(x) &= 3x+3 \\
r_{1}(x) &= 2 \\
r_{2}(x) &= 0.
\end{align}
$$
Then
$$
\begin{align}
q_{1}(x)g(x) + r_{1}(x) &= (3x+1)(2x+1) + 2 \\
&= 2x^{2}+3x+2x+1+2 \\
&= 2x^{2}+x+3 \\
&\text{and} \\
q_{2}(x)g(x) + r_{2}(x) &= (3x+3)(2x+1) + 0\\
&= 2x^{2} + 3x + 6x + 3 \\
&= 2x^{2}+x+3.
\end{align}
$$
Thus, $\deg(r_{1})< \deg(g)$ and $\deg(r_{2})<\deg(g)$ and such that $q_{1}(x)\neq q_{2}(x)$ and $r_{1}(x)\neq r_{2}(x)$, but such that $q_{1}(x)g(x)+r_{1}(x)=q_{2}g(x)+r_{2}(x)$. Therefore the uniqueness property from Problem 126 does not hold in all non-integral domains. 
