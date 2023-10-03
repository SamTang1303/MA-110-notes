---
aliases: 
tags:
  - batch/math
  - batch/school/class/ma110
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-23
# Pre-Work Problems 54 Through 59 MA-110

> [!problem] Problem 4.54
> Consider the group $D_{4}$, and the subgroup $H=\langle \delta_{1}\rangle=\{ \rho_{0},\delta_{1} \}$ of $D_{4}$. List the distinct left cosets of the form $aH$ for $a \in D_{4}$, and list the elements of each of these. How many distinct (not equal) left cosets are there for $H$?

$$
\begin{align}
&\rho_{0}H = \delta_{1}H =\{ \rho_{0},\delta_{1} \} \\
&\rho_{1}H = \mu_{2}H = \{ \rho_{1}, \mu_{2} \} \\
&\rho_{2}H = \delta_{2}H = \{ \rho_{2}, \delta_{2} \} \\
&\rho_{3}H = \mu_{1}H = \{ \rho_{3}, \mu_{1} \}. \\
\end{align}
$$
Thus, we can see there are four distinct cosets.

> [!problem] Problem 4.55
> Consider the group $S_{3}$, and the subgroup $K=\langle (1\,2\,3)\rangle=\{ (1), (1\,2\,3),(1\,3\,2) \}$ of $S_{3}$. List the distinct left cosets of $K$ in $S_{3}$, and list the elements of each of these. How many distinct left cosets are there for $K$?

^aa0b20

$$
\begin{align}
(1)K = (1\,2\,3)K= (1\,3\,2)K &= \{ (1), (1\,2\,3),(1\,3\,2) \}\\
(1\,2)K = (1\,3)K = (2\,3)K &= \{ (1\,2), (2\,3), (1\,3) \}.
\end{align}
$$
Thus, there are tow distinct left cosets for $K$. 

> [!problem] Problem 4.56
> Consider the group $\mathbb{Z}$, and its subgroup $H=\langle 5\rangle=5\mathbb{Z}$. List the distinct left cosets of the form $n+H$ for $n \in \mathbb{Z}$, and list the elements of each of those. How many distinct left cosets are there for $H$?

$$
\begin{align}
0 + \mathbb{Z} &= \{\dots,-5,0,5, \dots \}\\
1 + \mathbb{Z} &= \{\dots,-4,1,6, \dots \}\\
2 + \mathbb{Z} &= \{\dots,-3,2,7, \dots \}\\
3 + \mathbb{Z} &= \{\dots,-2,3,8, \dots \}\\
4 + \mathbb{Z} &= \{\dots,-1,4,9, \dots \}\\
\end{align}
$$
For every integer $n \in \mathbb{Z}$, $n+\mathbb{Z}$ will be one of the sets listed above, so there are five distinct left cosets for $H$.

> [!problem] Problem 4.57
> Prove or disprove as appropriate: Suppose $G$ is a group, $H$ a subgroup of $G$, and $a$ and $b$ elements of $G$. If $aH=bH$, then $a=b$.

The statement above is false. A counterexample is given in [[#^aa0b20|Problem 55]], where $(1)K=(1\,2\,3)K$, but clearly $(1)\neq(1\,2\,3)$.

> [!problem] Problem 4.58
> Suppose $G$ is a group, $H$ a subgroup of $G$, and $a \in G$. Prove or disprove as appropriate: If $aH=H$, then $a \in H$.

^2d7d15

Let $G$ be a group with subgroup $H$, and $a \in G$. Let $aH=H$.

Suppose to the contrary that $a \notin H$. $e_{H} \in H$ by the definition of a subgroup. Therefore, $ae_{H} \in aH$. But $ae_{H}=a$ and $aH=H$, implying $a \in H$. This is a contradiction, implying that our assumption must be false, and $a \in H$. 

> [!problem] Problem 4.59
> Prove or disprove as appropriate: Suppose $G$ is a group, $H$ a subgroup of $G$, and $a$ and $b$ elements of $G$. If $a \in bH$, then $b \in aH$.

^2e0634

Let $G$ be a group, $H$ a subgroup of $G$ and $a,b \in G$. Suppose $a \in bH$. This implies
$a =bh$ for some $h \in H$. 
$$
\begin{align}
a&=bh\\ 
ah^{-1} &= b.
\end{align}
$$
Because $H$ is a subgroup, $h^{-1} \in H$. Thus, $b \in aH$.