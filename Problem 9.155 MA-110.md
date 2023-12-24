---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.155 MA-110

> [!problem] Problem 9.155
> Let $F$ be a field, and let $f(x) \in F[x]$ be a polynomial of degree 2 or 3. Prove that $f(x)$ is reducible over $F$ if and only if $f(x)$ has a root in $F$.

Let $F$ be a field, and let $f(x) \in F[x]$ be a polynomial of degree 2 or 3. Suppose $f(x)$ is [[Definition 9.2 MA-110|reducible]] over $F$. Then, for some $p(x),q(x) \in F[x]$ such that $\deg(f),\deg(q) < \deg(f)$ and $f(x)=p(x)q(x)$. Because the degree of $f(x)$ is less than 4, the degree of either $p(x)$ or $q(x)$ must be exactly $1$. (It is impossible for one of them to have degree $0$, because than the degree of the other would equal the degree of $f$.)

Thus, without loss of generality, we are justified in assuming $p(x)$ has degree 1 and can be represented as $p(x)=ax + b$ where $a,b \in F$. Consider evaluating $f(x)$ and $x=a^{-1}(-b)$.
$$
f(a^{-1}(-b)) = (a(a^{-1}(-b))+b)q(x) =(-b+b)q(x)=0.
$$
Thus, $f(x)$ has a root $a^{-1}(-b) \in F$.

Now, suppose $f(x)$ has a root $a \in F$. By [[Problem 9.152 MA-110|Problem 152]], we can write $f(x)=p(x)(x-a)$. Thus $f(x)$ is reducible.
