---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.125 MA-110

> [!problem] Problem 8.125
> Let $r$ and $X$ be as in [[Problem 8.124 MA-110|Problem 124]], so $r(x)=f(x)-q(x)g(x)$. Substitute the formula $f(x)-q(x)g(x)$ for $r(x)$ to show that the polynomial $r(x)-b_{n}^{-1}c_{l}x^{l-n}g(x)$ is in $X$. Explain why this conclusion results in a contradiction.

We know $r(x)=f(x)-q(x)g(x)$ for some $q(x) \in R[x]$ by definition. Therefore
$$
\begin{align}
r(x)-b_{n}^{-1}c_{l}x^{l-n} &= f(x)-q(x)g(x) - b_{n}^{-1}c_{l}x^{l-n}g(x) \\
&= f(x) - (q(x) + b^{-1}_{n}c_{l}x^{l-n})g(x).
\end{align}
$$
Thus, $r(x)-b_{n}^{-1}c_{l}x^{l-n}$ is in $X$, because $b^{-1}_{n}c_{l}x^{l-n} \in R[x]$ by our assumption that $l\geq n$. This is a contradiction. In the last problem we showed $r(x)-b_{n}^{-1}c_{l}x^{l-n}$ has a lesser degree than $r(x)$, but our initial assumption was that $r(x)$ has greater $X$. Therefore, the remainder with minimal degree must be less than $n$, and the conclusion of [[Theorem 8.6 MA-110|The Division Algorithm]] holds.