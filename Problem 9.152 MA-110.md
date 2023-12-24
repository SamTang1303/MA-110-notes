---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.152 MA-110

> [!problem] Problem 9.152
> Let $f(x) \in F[x]$, where $F$ is a field, and let $a \in F$. Prove that $a$ is a root of $f(x)$ if and only if $x-a\mid f(x)$.

Let $f(x) \in F[x]$, where $F$ is a field, and let $a \in F$.

Suppose $a$ is a root of $f(x)$. [[Problem 9.151 MA-110|Problem 151]] tells us that the remainder of the division algorithm applied to $f(x)$ and $x-a$, will be equal to $f(a)=0$. Thus, $x-a$ divides $f(x)$.

Suppose $x-a\mid f(x)$. Then $f(x)=p(x)(x-a)$ for some $p(x) \in F[x]$, and $f(a)=p(a)(a-a)=0$. Thus $a$ is a root of $f(x)$.

Therefore, $a$ is a root of $f(x)$ if and only if $x-a\mid f(x)$.