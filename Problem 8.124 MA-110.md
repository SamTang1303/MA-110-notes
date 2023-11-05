---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.124 MA-110

> [!problem] Problem 8.124
> Let $X$ be as in [[Problem 8.123 MA-110|Problem 123]], and suppose that $0 \notin X$. Then every element of $X$ has a degree. Let $r(x)$ be an element of minimal degree in $X$, and let $l = \deg(r)$. Then $f(x)=q(x)g(x)+r(x)$ for some $q(x) \in R[x]$, so we just need to show that $\deg(r)<\deg(g)$. Suppose to the contrary that $r(x)=c_{0}+c_{1}+c_{2}+ \cdots+c_{l}x^{l}$ with $c_{l}\neq0$ and $l \geq n$. Show that the degree of the polynomial $r(x)-b_{n}^{-1}c_{l}x^{l-n}g(x)$ is less than $l$.

Suppose to the contrary that $r(x)=c_{0}+c_{1}+c_{2}+ \cdots+c_{l}x^{l}$ with $c_{l}\neq0$ and $l \geq n$. Consider the polynomial $r(x)-b_{n}^{-1}c_{l}x^{l-n}g(x)$.
$$
-b^{-1}_{n}c_{l}x^{l-n}(b_{0} + b_{1}x +  \cdots +b^{}_{n}x^{n}) = -b^{-1}_{n}c_{l}x^{l-n}b_{0} -b^{-1}_{n}b_{1}c_{l}x^{l-n+1} -  \cdots -b_{n}^{-1}b_{n}c_{l}x^{l-n+n}.
$$
Thus, the last term of $r(x)-b_{n}^{-1}c_{l}x^{l-n}$ will be
$$
c_{l}x^{l} - b_{n}^{-1}b_{n}c_{l}x^{l-n+n}=c_{l}x^{l}-1 \cdot c_{l}x^{l}=0.
$$
Therefore, the coefficient on the $x^{l}$ term will be zero, and the degree of $r(x)-b_{n}^{-1}c_{l}x^{l-n}$ must be less than $l$. 