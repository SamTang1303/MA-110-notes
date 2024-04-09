---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.258 MA-111

> [!problem] Problem 13.258
> Show that the splitting field of $x^{6}+4x^{3}-6$ over $\mathbb{Q}$ is a radical extension.

Let $f(x)=x^{6}+4x^{3}-6 \in \mathbb{Q}[x]$. The roots of $f(x)$ are
$$
\sqrt[3]{ -2 + \sqrt{ 10 } }, \sqrt[3]{ -2 - \sqrt{ 10 } }, \omega \sqrt[3]{ -2 + \sqrt{ 10 } }, \omega \sqrt[3]{ -2 - \sqrt{ 10 } }, \omega^{2} \sqrt[3]{ -2 + \sqrt{ 10 } }, \omega^{2} \sqrt[3]{ -2 - \sqrt{ 10 } }.
$$
Let $\omega=e^{2\pi i/3}$ and $a_{1}=\sqrt[3]{ -2 + \sqrt{ 10 } }, a_{2}=\sqrt[3]{ -2 - \sqrt{ 10 } }$. The splitting field of $f(x)$ will be
$$
\mathbb{Q}(a_{1},a_{2},\omega a_{1},\omega a_{2},\omega^{2}a_{1},\omega^{2}a_{2})=\mathbb{Q}(a_{1},a_{2},\omega ).
$$
$a_{1}^{3}=-2+\sqrt{ 10 }$, so $\sqrt{ 10 } \in \mathbb{Q}(a_{1},a_{2},\omega)$. Thus, the splitting field of $f(x)$ is equal to
$$
\mathbb{Q}(\omega,\sqrt{ 10 },a_{1},a_{2})
$$
We can verify that this is a [[Definition 13.4 MA-111|radical extension]] of $\mathbb{Q}$.
$$
\begin{align}
\omega^{3}&=1 \in  \mathbb{Q} \\
(\sqrt{ 10 })^{2}&= 10 \in  \mathbb{Q}(\omega ) \\
\left(a_{1} \right)^{3} &= -2+\sqrt{ 10 } \in  \mathbb{Q}(\omega,\sqrt{ 10 })\\
\left(a_{2} \right)^{3} &= -2+\sqrt{ 10 } \in  \mathbb{Q}(\omega,\sqrt{ 10 }, a_{1}).
\end{align}
$$
Furthermore, because $E$ contains $\omega$, $f(x)$ is solvable by radicals over $\mathbb{Q}$.
