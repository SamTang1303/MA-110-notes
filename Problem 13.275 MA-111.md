---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.275 MA-111

> [!problem] Problem 13.275
> Let $p(x) \in R[x]$ be a polynomial of odd degree. Use Axiom 13.8 to prove that $p(x)$ has a real root.

Let $p(x) \in R[x]$ of degree $n$, where $n$ is odd, such that
$$
p(x)=a_{0}+a_{1}x+a_{2}x^{2}+\dots a_{n}x^{n}.
$$
Without loss of generality, assume $a_{n}$ is positive. For a sufficiently positive value for $x$, the $x^{n}$ term will dominate the sum $a_{0}+a_{1}x+a_{2}x^{2}+\dots a_{n-1}x^{n-1}$ and $p(x)$ will evaluate to be positive. Likewise, for a sufficiently negative $x$ value, $p(x)$ will be negative. Thus, Axiom 13.8 implies that $p(x)$ has a real root.
