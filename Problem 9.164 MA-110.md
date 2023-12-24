---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.164 MA-110

> [!problem] Problem 9.164
> Let $M$ be an ideal of a commutative ring $R$ with unity. Prove that $M$ is maximal if and only if $R/M$ has no proper nontrivial ideals. (Use [[Problem 9.163 MA-110|Problem 163]].)

Let $M$ be an ideal of a commutative ring $R$ with unity.

We will prove the forward direction of the implication by contraposition. Let $X$ be a nontrivial proper ideal of $R/M$. By Problem 163, the set $J=\{ r \in R\mid r+M \in X \}$ is an ideal of $R$. Let $m \in M$. Then $m+M=M \in X$ and $m \in J$. Because $X$ is non-trivial, there exists some $b +M \in X$ such that $b\notin M$. But $b$ must be in $J$, so $M\subsetneq J$. Thus $M$ is not maximal.

We will also prove the backward direction by contraposition. Suppose $M$ is not maximal and there exists some ideal $N$ such that $M\subsetneq N\subsetneq R$. Consider the set $N/M=\{ n + M\mid n \in N \}$. $M$ is an ideal of $N$, so we know that $N/M$ is an additive group. So, we only need to show it is closed under multiplication with ring elements. If $n+M \in N/M$ and $r+M \in R/M$, then $(n+M)(r+M)=nr+M \in N/M$ because $nr \in N$ by the properties of ideals. Thus $N/M$ is an [[Definition 6.3 MA-110|ideal]] of $R/M$.

It must also be. non-trivial, because there exists some $n \in N\setminus M$, so $n+M\neq M$. Further, it cannot be proper because we assumed that $M\neq R$. Thus we have shown both directions of the implication and the proof is complete.
