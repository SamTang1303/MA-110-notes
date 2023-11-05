---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.117 MA-110

> [!problem] Problem 8.117
> Let $R$ be a commutative ring. Prove that, if $R$ has the cancellation property, then $R$ has no divisors of zero.

Let $R$ be a commutative ring with the [[Definition 8.1 MA-110|cancellation property]]. Suppose that $R$ has a zero divisor $a$ such that $ar=0$ where $r\neq0$. Then
$$
ar = a \cdot 0
$$
By [[Problem 6.92 MA-110|Problem 92]]. Thus, because $r\neq0$ the cancellation property does not hold. Thus, we have proven by contraposition that, if the cancellation property does hold, then $R$ has no zero divisors.
