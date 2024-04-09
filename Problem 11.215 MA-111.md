---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.215 MA-111

> [!problem] Problem 11.215
> Suppose that $[E:F]=p$, a prime number. Prove that $E$ is a simple extension of $F$.

Let $[E:F]=p$, a prime number. Then there exists a basis set $\{ \alpha_{1},\alpha_{2},\dots,\alpha_{n} \}\subseteq E$ that spans $E$ over over $F$. Because $E$ is a finite extension of $F$, it is algebraic. Choose an $\alpha_{k}$ in the basis of $E$ over $F$ such that $\alpha_{k} \in E\setminus F$. The Algebraic Extension Theorem says that $F(\alpha_{k})$ will be a vector space over $F$ with basis set $\{ \alpha_{k},\alpha_{k}^{2},\dots,\alpha_{k}^{n} \}$ where $n$ is the degree of $\text{Irr}(F,\alpha_{k})$. Note that because we chose $\alpha_{k} \notin F$, this cannot be a trivial extension. Further, by field properties, all the basis elements of $F(\alpha_{k})$ will be elements of $E$ as well. Therefore, $F(\alpha_{k})\subseteq E$. By the degree multiplication theorem, $F(\alpha_{k})$ must be of degree $p$ as well.

We can argue similarly to show that $F(\alpha_{k},\alpha_{j})\subseteq E$ for any $j \in \{ 1,\dots n \}$. If $\alpha_{j}$ were not in $F(\alpha_{k})$, then $F(\alpha_{k},\alpha_{j})$ would have dimension greater than 1 as a vector space over $F(\alpha_{j})$. Thus the Dimension Multiplication Theorem would imply the dimension of $F(\alpha_{k},\alpha_{j})$ over $F$ is greater than $p$. We know this to be impossible because $F(\alpha_{k},\alpha_{j})\subseteq E$. Thus, every basis vector of $E$ over $F$ is in $F(\alpha_{k})$ over $F$. Because the two vector spaces contain each other's bases over $F$, they must be equal. Therefore, $E=F(\alpha_{k})$.

