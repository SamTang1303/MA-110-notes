---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.206 MA-111

> [!problem] Problem 11.206
> Suppose that $a_{0},a_{1},b_{0},b_{1}\in \mathbb{Q}$, and that $a_{0}+b_{0}\sqrt{ 2 }=a_{1}+b_{1}\sqrt{ 2 }$. Prove that $a_{0}=a_{1}$ and $b_{0}=b_{1}$.

Suppose that $a_{0},a_{1},b_{0},b_{1}\in \mathbb{Q}$, and that $a_{0}+b_{0}\sqrt{ 2 }=a_{1}+b_{1}\sqrt{ 2 }$.
$$
\begin{align}
a_{0}+b_{0}\sqrt{ 2 }&=a_{1}+b_{1}\sqrt{ 2 } \\
a_{0}-a_{1}&= b_{1}\sqrt{ 2 }-b_{0}\sqrt{ 2 } \\
a_{0}-a_{1} &= (b_{1}-b_{0})\sqrt{ 2 }.
\end{align}
$$
Suppose to the contrary that $b_{1}-b_{0}\neq0$. Then $(b_{1}-b_{0})^{-1}$ exists and will be rational. 
$$
(a_{0}-a_{1})(b_{1}-b_{0})^{-1}=\sqrt{ 2 }.
$$
Because $\sqrt{ 2 }$ is irrational, this is impossible. Thus, $b_{1}-b_{0}=0$ and $a_{0}-a_{1}=0$.
