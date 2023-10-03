---
aliases: 
tags:
  - batch/math
  - batch/school/class/ma110
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-25
# Pre-Work Problems 60 Through 63 MA-110

> [!problem] Problem 4.60
> Prove that if $a \in H$, then $aH=H$. (This is the converse of the statement in [[Pre-Work Problems 54 Through 59 MA-110#^2d7d15|Problem 58]].)

Let $G$ be a group with subgroup $H$, and let $a \in H$. First, let $x \in H$. $a^{-1}x \in H$ because $H$ is a subgroup, and $a(a^{-1}x)=x$, so $x \in aH$. Thus, $H \subseteq aH$. Now, let $y \in aH$. This implies $ah =y$ for some $h \in H$. Because $ah$ is the product of two elements of subgroup $H$, it must be in $H$ as well. Therefore $y \in H$ and $aH \subseteq H$. Combining these two results yields $aH=H$.

> [!problem] Problem 4.61
> Suppose $H$ is a subgroup of $G$. Prove that for all $a,b \in G$, either $aH=bH$ or $aH\cap bH$ is empty.

^0d748d

We will show the following equivalent statement: for all $a,b \in G$, $\sim(aH=bH)$ implies $aH\cap bH=\emptyset$ *and* $\sim (aH=bH\text{ and } aH\cap bH=\emptyset)$. Clearly, $\sim (aH=bH\text{ and } aH\cap bH=\emptyset)$ is true. Thus, we must only show the implication. Let $H$ be a subgroup of $G$ and suppose $a,b \in G$.

Suppose $aH\neq bH$ and, without loss of generality, there exists some $x \in G$ such that $x \in aH$ and $x \notin bH$. Let $y$ be an arbitrary element of $aH$ and $h$ an arbitrary element of $H$. By [[Pre-Work Problems 54 Through 59 MA-110#^2e0634|Problem 59]], $a \in xH$ and $a \in yH$. So, for some $h_{1}h_{2} \in H$,
$$
\begin{align}
yh_{2}=&\ a= xh_{1}\\
y &= xh_{1}h_{2}^{-1} \\
yh &= x(h_{1}h_{2}^{-1}h) \\
yh &\neq b && h_{1}h_{2}^{-1}h \in  H\text{ and } b \notin  xH
\end{align}
$$
Thus, for an arbitrary $h \in H$, $yh \neq b$, and $b \notin yH$. Equivalently, $y \notin bH$. We did this for an arbitrary $y \in aH$, so the $aH$ and $bH$ are disjoint and $aH\cap bH=\emptyset$. 

<div class="page-break" style="page-break-after: always;"></div> 

> [!problem] Problem 4.62
> Suppose $G$ is a group, $H$ subgroup of $G$, and $a$ an element of $G$. Consider the function $f:H\longrightarrow aH$ defined by $f(h)=ah$ for all $h \in H$. Prove that $f$ is one-to-one and onto. Explain why this implies that, for all $x,y \in G$, $\left| xH \right|=\left| yH \right|$.

^ed1852

Suppose $G$ is a group, $H$ subgroup of $G$, and $a$ an element of $G$. Consider the function $f:H\longrightarrow aH$ defined by $f(h)=ah$ for all $h \in H$.

Let $x,y \in H$ and suppose that $f(x)=f(y)$. This implies
$$
\begin{align}
ax &= ay \\
x&= y. && \text{right cancellation}
\end{align}
$$
Therefore, $f$ is one-to-one.

Let $z \in aH$. By definition, there must be some $h \in H$ such that $ah =z$. $f(z)=ah=z$. Therefore $f$ is onto.

Let $x,y$ be elements of $G$. We have just shown there are bijections $f_x:H\longrightarrow xH$ and $f_{y}:H\longrightarrow yH$. The inverse of a bijection is a bijection, and the composition of two bijections is a bijection. Thus, $f_{x}\circ f_{y}^{-1}:yH\longrightarrow xH$ is a bijection. Two sets are defined to have the same order if there exists a bijection between them.

> [!problem] Problem 4.63
> Consider the subgroup $H=\langle (1\,2\,3\,4)\rangle$ of $S_{5}$.
> 1. What is $\left| S_{5} \right|$?
> 2. What is $\left| H \right|$?
> 3. How big are the cosets of $H$ in $S_{5}$?
> 4. How many distinct cosets of $H$ in $S_{5}$ are there? (Use [[#^0d748d|Problem 61]].)
> 5. Do you think that $S_{5}$ has a subgroup of order 7? Why or why not?

1. $\left| S_{5} \right|=5! =120$.
2. $\left| H \right|=4$
3. As proved in the problem above, all the cosets will have the same order as $H$, 4.
4. In [[#^0d748d|Problem 61]], we showed that cosets are either disjoint or equal. So, if each distinct coset has order 4, there must be 30 distinct cosets comprising the group.
5. No, if it had a subgroup of order 7, our answers would indicate we could "partition" the set into distinct cosets each with order 7. But 120 does not divide 7 evenly, so this does not seem possible.