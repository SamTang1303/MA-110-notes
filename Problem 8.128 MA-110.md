---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.128 MA-110

> [!problem] Problem 8.128
> Let $F$ be a field. Use the division algorithm to prove that every ideal of $F[x]$ is a [[Definition 6.4 MA-110|principal ideal]]. That is, prove that if $I$ is an ideal of $F[x]$, then there is some generating polynomial $p(x) \in F[x]$ such that $I=(p(x))$.

Let $F$ be a field with $I$ an ideal of $F[x]$. Let $g(x)$ be a polynomial in $I$ of minimal degree. Consider an arbitrary $f(x) \in I$. By [[Theorem 8.6 MA-110|The Division Algorithm]] there is a unique ($F$ is a field) $q(x), r(x) \in F[x]$ such that
$$
f(x) = q(x)g(x) + r(x).
$$
Where either $\deg(g)>\deg(r)$ or $r(x)=0$. Then $r(x) = f(x)-q(x)g(x)$. Because $I$ is an ideal and $g(x) \in I$, $-q(x)g(x) \in I$. Further, $f(x)$ is in $I$ as well, implying $r(x) \in I$. This rules out the possibility that $\deg(g) > \deg(r)$ because we chose $g(x)$ to be of minimal degree in $R$. Thus $r(x)=0$ and $f(x)=q(x)g(x)$. By definition of a principal ideal, $f(x) \in I$. Therefore, every element of $I$ is in $(g(x))$, and $g(x)=I$.
