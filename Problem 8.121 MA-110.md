---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 8.5 MA-110|Definition of the degree of a polynomial]]"
---
# Problem 8.121 MA-110

> [!problem] Problem 8.121
> Let $R$ be an [[Definition 8.3 MA-110|integral domain]], and let $p(x),q(x) \in R[x]$ be nonzero polynomials. Prove that $\deg(pq)=\deg(p)+\deg(q)$. Use this fact to explain why $R[x]$ must also be an integral domain.

Let $R$ be an integral domain, and let $q(x),q(x) \in R[x]$ be nonzero polynomial such that $\deg(q)=k_{1}$ and $\deg(q)=k_{2}$ and $q(x) = q_{1}+q_{2}x+  \cdots q_{k_{1}}x^{k_{1}}, q(x) = q_{1}+q_{2}x+  \cdots q_{k_{2}}x^{k_{2}}$.
The product of two polynomials is the sum of the product of every pairwise combination of terms in the polynomials. Expressed symbolically,
$$
p(x)q(x)= \sum\limits_{m=1,n=1}^{m\leq k_{1},n\leq k}p_{m}x^{m}q_{n}x^{n} = \sum\limits_{m=1,n=1}^{m\leq k_{1},n\leq k}(p_{m}q_{n})x^{m+n}.
$$
Thus, we will achieve the highest degree term only when $m=k_{1}$ and $n=k_{2}$, and that term will have degree $k_{1}+k_{2}=\deg(p)+\deg(q)$. We know that the coefficient $p_{k_{1}}q_{k2}$ is non-zero because $p_{k}$ and $q_{k}$ are non-zero by the definition of the degree of a polynomial, and the fact that $R$ is an integral domain, meaning it has no zero divisors. Thus $\deg(pq)=\deg(p)+\deg(q)$.

Given, this fact, $R[x]$ must not have any zero divisors. If it did, we would have
$$
p(x)q(x) = 0
$$
for two polynomials with non-zero degrees, violating the property above. Thus $R[x]$ must be an integral domain.
