---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.153 MA-110

> [!problem] Problem 9.153
> Explain why a polynomial of degree $n$ over a field $F$ can have at most $n$ distinct roots in $F$.

If a polynomial of degree $n$ over a field $F$ were to have more than $n$ distinct roots, $a_{1},\dots a_{m}$ with $m<n$, then by [[Problem 9.152 MA-110|Problem 152]] it would have to have $m$ distinct factors of the form $(x-a_{1}),\dots(x-a_{m})$. But by [[Problem 8.121 MA-110|Problem 121]] the degree would have to be greater than or equal to $m$, contradicting the statement that the polynomial was of degree $n$.
