---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 6.102 MA-110

> [!problem] Problem 6.102
> Let $\mathbb{Z}[x]$ be the ring of polynomials in $x$ with integer coefficients.
> 1. Let $I$ be the subset of $\mathbb{Z}[x]$ consisting of polynomials with no constant term; that is, $I=\{ a_{1}x + a_{2}x^{2} a_{3}x^{3} + \cdots : a _{i} \in \mathbb{Z} \}$. Is $I$ an [[Definition 6.3 MA-110|ideal]] of $\mathbb{Z}[x]$? Prove or disprove.
> 2. Let $J$ be the subset of $\mathbb{Z}[x]$ consisting of polynomials with only even degree terms; that is, $J=\{ a_{0} + a_{2}x^{2} + a_{4}x^{4}+ \cdots : a_{i} \in \mathbb{Z} \}$. Is $J$ an ideal of $\mathbb{Z}[x]$? Prove or disprove.

Let $\mathbb{Z}[x]$ be the ring of polynomials in $x$ with integer coefficients.

1 ) Let $I$ be the subset of $\mathbb{Z}[x]$ consisting of polynomials with no constant term; that is, $I=\{ a_{1}x + a_{2}x^{2} a_{3}x^{3} + \cdots : a _{i} \in \mathbb{Z} \}$.

Since $p(x)=0$ does not have a constant term, $0 \in I$, and $I$ contains the additive identity of $\mathbb{Z}[x]$. Also, note if $p(x)$ does not have a constant term, neither will $-p(x)$. Therefore, $I$ is closed under inverses.

Let $p_{1}(x),p_{2}(x) \in I$ such that $p_{1}(x)=a_{1}x+a_{2}x^{2} + \cdots$ and $p_{2}(x) = b_{1}x + b_{2}x^{2} + \cdots$. Then
$$
p_{1}(x) + p_{2}(x) = (a_{1}+b_{1})x + (a_{2}+b_{2})x^{2} + \cdots
$$
Because this has no constant term, it is also in $I$, and $I$ is closed under addition. 

Let $p(x) \in I$. Then every term of $p(x)$ is multiplied by some natural number power of $x$. Thus, every term of the product $p(x)r(x)$ (or $r(x)p(x)$) will be as well for any $r(x) \in \mathbb{Z}[x]$. Therefore, $p(x)r(x),r(x)p(x) \in I$ and $I$ is an ideal of $\mathbb{Z}[x]$.

2 ) Let $J$ be the subset of $\mathbb{Z}[x]$ consisting of polynomials with only even degree terms; that is, $J=\{ a_{0} + a_{2}x^{2} + a_{4}x^{4}+ \cdots : a_{i} \in \mathbb{Z} \}$. $J$ is *not* an ideal. Consider the polynomials $p(x) \in J$ such that $p(x) = 2 + x^{2}$, and $r(x) \in \mathbb{Z}[x]$ such that $r(x) = x$.
$$
p(x)r(x) = (2+x^{2})(x) = 2x + x^{3} \notin  J.
$$
Therefore, $J$ cannot be an ideal.