---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.129 MA-110

> [!problem] Problem 8.129
> Let $F$ be a field, and let $(p(x))$ be an ideal of $F[x]$. Prove that $(p(x))=(m(x))$ for some monic polynomial $m(x)$.

Let $F$ be a field, and let $(p(x))$ be an ideal of $F[x]$ such that $p(x)=p_{1}+p_{2}x+ \cdots p_{n}x^{n}$. Because $F$ is a field, $p_{n}^{-1} \in F$. Let $m(x) \in F[x]$ such that
$$
m(x):=p_{n}^{-1}p(x) =  p_{n}^{-1}p_{1} + p_{n}^{-1}p_{2}x+  \cdots p_{n}^{-1}p_{n}x^{n} = p_{n}^{-1}p_{1} + p_{n}^{-1}p_{2}x+  \cdots x^{n}.
$$
Thus, $m(x)$ is monic. Also note that $p(x)=p_{n}m(x)$.

Let $q(x)p(x) \in (p(x))$ where $q(x) \in F[x]$. Then
$$
q(x)p(x) = q(x)p_{n}m(x) \in  (m(x)).
$$
Thus $(p(x))\subseteq(m(x))$.

Let $r(x)m(x) \in (m(x))$ where $m(x) \in F[x]$. Then
$$
r(x)m(x) = r(x)p^{-1}_{n}p(x) \in  (p(x)).
$$
Thus $(p(x)) \subseteq(m(x))$ and $(p(x))=(m(x))$.