---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.163 MA-110

> [!problem] Problem 9.163
> Let $I$ be an ideal of a commutative ring $R$ with unity, and suppose that $X$ is an ideal of $R/I$. Let $J=\{ r \in R\mid r+I \in X \}$. Prove that $J$ is an ideal, that $I\subseteq J$, and that $X=J/I$. (In other words, prove that every ideal of a quotient ring $R$ is a quotient ring of an ideal of $R$.)

Let $I$ be an ideal of a commutative ring $R$ with unity, and suppose that $X$ is an ideal of $R/I$. Let $J=\{ r \in R\mid r+I \in X \}$.

Let $r \in R$ and $j \in J$. Then $j+I \in X$, so $(r+I)(j+I)=rj+I \in X$ because $X$ is an ideal. Thus $rj \in J$. Since $X$ is an ideal, $I \in X$. Because $0 \in X$, $0$ is therefore in $J$. Let $a \in J$. Then $a+I \in X$, and so $-a+I=-(a+I) \in X$ as well. Thus $-a \in J$ and $J$ is closed under additive inverses. Lastly, if $a,b \in J$, then $a+I$ and $b+I$ are in $X$. Because $X$ is a ring, $a+b+I \in X$, so $a+b \in J$ and $J$ is closed under addition. Thus $J$ satisfies all the criteria to be an [[Definition 6.3 MA-110|ideal]].

Let $i \in I$. Then $i+I=I \in X$, so $i \in J$, and $I\subseteq J$.

Let $a+I \in X$. Then $a \in J$ definitionally and $a+I \in J/I$, also definitionally. Let $j+I \in J/I$. Then $j \in J$ and $j+I \in X$. Thus $X=J/I$.