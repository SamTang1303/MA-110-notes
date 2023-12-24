---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.166 MA-110

> [!problem] Problem 9.166
> Let $R$ be a [[Definition 9.5 MA-110|PID]], and suppose that $I$ and $J$ are ideals with $I\subseteq J$, and that $I$ is a nonzero [[Definition 9.3 MA-110|prime ideal]]. Justify each stem of the following argument.
> 1. $I=(a)$ and $J=(b)$ for some non-zero $a,b \in R$.
> 2. $a=rb$ for some $r \in R$.
> 3. Either $r \in I$ or $b \in I$.
> 4. If $b \in I$, then $I=J$.
> 5. If $r \in I$, then $J=R$.

1. Definition of a [[Definition 9.5 MA-110|PID]] and the fact that $I$ and $J$ are non trivial.
2. $a \in I$ and $I\subseteq J$; definition of an [[Definition 6.4 MA-110|principal ideal]].
3. $a =rb\in I$ and $I$ is a [[Definition 9.3 MA-110|prime ideal]].
4. If $b \in I$ then $b=ka$ for some $k \in R$. Then for any $j \in J$, $j=r(ka)$ for some $r \in R$. Thus $j \in I=(a)$, and $J\subseteq I$. By assumption $I\subseteq J$, so $I=J$.
5. If $r \in I$, then $a=(am)b$ for some $m \in R$, and $1=mb$. This implies $1 \in (b)=J$. By [[Problem 7.107 MA-110|Problem 107]], this means $J=R$.
