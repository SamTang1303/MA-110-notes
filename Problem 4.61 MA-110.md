---
aliases:
  - cosets are disjoint
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 4.1 and 5.1 MA-110|coset]]"
---
# Problem 4.61 MA-110

> [!problem] Problem 4.61
> Suppose $H$ is a subgroup of $G$. Prove that for all $a,b \in G$, either $aH=bH$ or $aH\cap bH$ is empty.

We will show the following equivalent statement: for all $a,b \in G$, $\sim(aH=bH)$ implies $aH\cap bH=\emptyset$ *and* $\sim (aH=bH\text{ and } aH\cap bH=\emptyset)$. Clearly, $\sim (aH=bH\text{ and } aH\cap bH=\emptyset)$ is true. Thus, we must only show the implication. Let $H$ be a subgroup of $G$ and suppose $a,b \in G$.

Suppose $aH\neq bH$ and, without loss of generality, there exists some $x \in G$ such that $x \in aH$ and $x \notin bH$. Let $y$ be an arbitrary element of $aH$ and $h$ an arbitrary element of $H$. By [[Problem 4.59 MA-110|Problem 59]], $a \in xH$ and $a \in yH$. So, for some $h_{1}h_{2} \in H$,
$$
\begin{align}
yh_{2}=&\ a= xh_{1}\\
y &= xh_{1}h_{2}^{-1} \\
yh &= x(h_{1}h_{2}^{-1}h) \\
yh &\neq b && h_{1}h_{2}^{-1}h \in  H\text{ and } b \notin  xH
\end{align}
$$
Thus, for an arbitrary $h \in H$, $yh \neq b$, and $b \notin yH$. Equivalently, $y \notin bH$. We did this for an arbitrary $y \in aH$, so the $aH$ and $bH$ are disjoint and $aH\cap bH=\emptyset$. 
