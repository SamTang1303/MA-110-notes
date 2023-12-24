---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.160 MA-110

> [!problem] Problem 9.160
> Let $F$ be a field, and suppose that $p(x) \in  F[x]$ is a reducible polynomial. Show that $(p(x))$ is not a prime ideal of $F[x]$.

Let $F$ be a field, and suppose that $p(x) \in  F[x]$ is a reducible polynomial. Then $p(x)=f(x)g(x)$ for some $f(x),g(x) \in F[x]$ such that $\deg(f),\deg(g) <\deg(p)$. Because all elements of $(p(x))$ are multiples of $p(x)$, [[Problem 8.121 MA-110|Problem 121]] guarantees that all the elements of $(p(x))$ have degree greater than or equal to $p(x)$. Thus, $f(x)$ and $g(x)$ are not in $(p(x))$. But, their product is $p(x)$, so $(p(x))$ is not a prime ideal.
