---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.207 MA-111

> [!problem] Problem 11.207
> Suppose that $m=a_{0}+b_{0}\sqrt{ 2 }$ and $n=a_{1}+b_{1}\sqrt{ 2 }$ for some $a_{0},a_{1},b_{0},b_{1} \in \mathbb{Q}$. Show that $m+n$, $mn$, and $m/n$ can all be written in the form $a+b\sqrt{ 2 }$ for some $a,b \in \mathbb{Q}$.

Suppose that $m=a_{0}+b_{0}\sqrt{ 2 }$ and $n=a_{1}+b_{1}\sqrt{ 2 }$ for some $a_{0},a_{1},b_{0},b_{1} \in \mathbb{Q}$.
$$
\begin{align}
m+n &= a_{0}+b_{0}\sqrt{ 2 }+a_{1}+b_{1}\sqrt{ 2 } \\
&= (a_{0}+a_{1})+(b_{0}+b_{1})\sqrt{ 2 }.
\end{align}
$$
$$
\begin{align}
mn &= (a_{0}+b_{0}\sqrt{ 2 })(a_{1}+b_{1}\sqrt{ 2 }) \\
&= a_{0}a_{1}+b_{0}a_{1}\sqrt{ 2 }+a_{0}b_{1}\sqrt{ 2 } + 2b_{0}b_{1} \\
&= (a_{0}a_{1}+2b_{0}b_{1})+(b_{0}a_{1}+a_{0}b_{1})\sqrt{ 2 }.
\end{align}
$$
$$
\begin{align}
m/n &= \frac{a_{0}+b_{0}\sqrt{ 2 }}{a_{1}+b_{1}\sqrt{ 2 }} \\
&= \frac{a_{0}+b_{0}\sqrt{ 2 }}{a_{1}+b_{1}\sqrt{ 2 }}  \cdot \frac{a_{1}-b_{1}\sqrt{ 2 }}{a_{1}-b_{1}\sqrt{ 2 }} \\
&= \frac{a_{0}a_{1} + b_{0}a_{1}\sqrt{ 2 }-a_{0}b_{1}\sqrt{ 2 }-2b_{0}b_{1}}{a_{1}^{2}-2b_{1}^{2}} \\
&= \left( \frac{a_{0}a_{1}-2b_{0}b_{1}}{a_{1}^{2}-2b_{1}^{2}} \right) + \left( \frac{b_{0}a_{1}-a_{0}b_{1}}{a_{1}^{2}-2b_{1}^{2}} \right)\sqrt{ 2 }.
\end{align}
$$
