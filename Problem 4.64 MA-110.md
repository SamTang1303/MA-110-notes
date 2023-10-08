---
aliases:
  - the order of a subgroup divides the order of the group
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 4.64 MA-110

> [!problem] Problem 4.64
>     Suppose that $G$ is a finite group and $H$ is a [[Definition 2.3 MA-110|subgroup]] of $G$. Prove that $\left| H \right|$ divides $\left| G \right|$. Explain why it follows that the order of any element of $G$ also divides $\left| G \right|$

Let $G$ be a finite group and $H$ a subgroup of $G$. Consider the set of all
$$
X=\{ gH: g \in  G \}.
$$
We can interpret this as the set of all left cosets of $H$. Let $A \in X$. For some $a \in g$, $aH=A$. By [[Problem 4.62 MA-110|Problem 62]], we know $\left| H \right|=\left| aH \right|=\left| A \right|$ and $\left| A \right|=\left| B \right|$. Thus, the order of every of $X$ is $\left| H \right|$. For any $g \in G$, $g \in gH\in X$. So $\cup_{O \in X} O=G$. Further, [[Problem 4.61 MA-110|Problem 61]] tells us that all the distinct elements of $X$ are pairwise disjoint, so
$$
\begin{align}
\left| G \right| &=\left| \bigcup\limits_{O \in  X}O \right|  \\
&=  \sum\limits_{O \in  X} \left| O \right| && \text{elements of X are disjoint}  \\
&= \sum\limits_{O \in  X}\left| H \right| && O\text{ is a coset of }H \\
&= \left| X \right| \left| H \right| .
\end{align}
$$
Thus, we can see the order of $H$ divides the order of $G$. This implies the order of every element of $G$ also divides $\left| G \right|$ because the order of an element is determined by the [[Definition 2.5 MA-110|cyclic subgroup]] it generates.

