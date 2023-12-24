---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.136 MA-110

> [!problem] Problem 8.136
> Let $R$ be an integral domain, and let $f(x),g(x) \in R[x]$. Suppose that $f(x)$ and $g(x)$ have a greatest common divisor. Prove that it is unique.

glLet $R$ be an integral domain, and let $f(x),g(x) \in R[x]$. Suppose that $f$ and $g$ have a greatest common divisor $d_{1}(x),d_{2}(x)$. Based on the second condition of the definition of a [[Definition 8.8 MA-110|greatest common divisor]], it must be true that both $d_{1}(x)\mid d_{2}(x)$ and $d_{2}(x)\mid d_{1}(x)$. Thus, by [[Problem 8.135 MA-110|Problem 135]] $d_{1}(x)=u(x)d_{2}(x)$ where $u(x)$ is a unit in $R[x]$. [[Problem 8.131 MA-110|Problem 131]] says $u(x)$ must be a non-zero constant. $d_{2}(x)$ is monic, so the only constant multiple whose product would result in another monic polynomial is if $u(x)=1$. Thus $d_{1}(x)=d_{2}(x)$, and the $\gcd$ is unique.

