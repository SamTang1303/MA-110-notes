---
aliases:
  - definition of coset multiplication
  - coset multiplication
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.74 MA-110

> [!problem] Problem 5.74
> Suppose that $H$ is a [[Definition 5.2 MA-110|normal subgroup]] of group $G$. Let $a,b \in G$ and define $X=aH$ and $Y=bH$. Prove that $XY=(ab)H$.

Let $H\trianglelefteq G$ with $a,b \in G$ and define $X=aH$ and $Y=bH$. In [[Problem 5.72 MA-110|Problem 72]] we showed $XY\subseteq(ab)H$.

Suppose that $n \in (ab)H$. Then, for some $h \in H$, $n =(ab)h$. Note this is equivalent to $a(bh)$. $bh \in bH=Y$ by definition, and $a \in aH=X$, so $a(bh) \in XY$. Thus, $(ab)H \subseteq XY$ and $XY=(ab)H$.
