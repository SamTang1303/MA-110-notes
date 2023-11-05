---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.123 MA-110

> [!problem] Problem 8.123
> Let $X=\{ f(x)-g(x)p(x) \mid p(x) \in R[x] \}$. Suppose that $0 \in X$. Show that the conclusion of the division algorithm (i.e., the last sentence) follows in this case.

Let $X=\{ f(x)-g(x)p(x) \mid p(x) \in R[x] \}$ and suppose that $0 \in X$. Then for some $p(x) \in R[x]$
$$
\begin{align}
0&=f(x) - g(x)p(x) \\
f(x) &= g(x)p(x)+ 0.
\end{align}
$$
Thus in this case the remainder is $0$ and the conclusion of [[Theorem 8.6 MA-110|The Division Algorithm]] follows.