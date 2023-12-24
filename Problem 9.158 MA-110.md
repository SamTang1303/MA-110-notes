---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.158 MA-110

> [!problem] Problem 9.158
> Prove that if $I$ is a [[Definition 9.3 MA-110|prime ideal]] of a commutative ring $R$ with unity, then $R/I$ is an [[Definition 8.3 MA-110|integral domain]].

Let $I$ be a prime ideal of a commutative ring $R$ with unity. Let $a+I,b+I \in R/I$ such that neither equals $I$. In other words, $a$ and $b$ are not in $I$. Then, because $I$ is a prime ideal, $ab$ cannot be in $I$ as well. Thus $(a+I)(b+I)=ab+I\neq I$, implying that $R/I$ has no zero divisors and is an integral domain.
