---
aliases:
  - The Second Isomorphism Theorem
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.88 MA-110

> [!problem] Problem 5.88
> Let $H$ and $K$ be subgroups of a group $G$ with $K \trianglelefteq  G$. Consider the map
> $$
> \phi: H \to (HK)/K
> $$
> defined by $\phi(a) = aK$. Use this map and [[Problem 5.84 MA-110|The First Isomorphism Theorem]] to prove that $(HK)/K \simeq H/(H \cap K)$.

Let $H$ and $K$ be subgroups of a group $G$ with $K \trianglelefteq G$. Consider the map $\phi: H \longrightarrow (HK)/K$ defined by $\phi(a) = aK$. First, we seek to show that $\ker(\phi )=H\cap K$.

Let $x \in H\cap K$ (i.e. $x \in H$ and $x \in K$.)
$$
\begin{align}
\phi(x) = xK = K \text{ by absorbtion}.
\end{align}
$$
$K$ is the identity of $(HK)/K$, so $x \in \ker(\phi)$ and $H\cap K\subseteq \ker(\phi)$.

Let $y \in \ker(\phi)$. Automatically, $y \in H$ because $\ker(\phi)\subseteq H$. Further,
$$
\phi(y)=yK=K.
$$
By [[Problem 4.58 MA-110|Problem 58]], $y \in K$. Therefore, $y \in H\cap K$. Thus, $\ker(\phi)\subseteq H \cap K$, and further, $\ker(\phi)=H\cap K$.

The last thing to be shown before the first isomorphism theorem can be applied is that $\phi(H)=(HK)/K$. Let $aK \in (HK)/K$ where $a \in HK$. Then, we can represent $a=hk$ where $h \in H$ and $k \in K$.
$$
\begin{align}
\phi(h) &= hK && \text{definition of }\phi \\
&= h(kK) && \text{absorbtion} \\
&= (hk)K && \\
&= aK.
\end{align}
$$
Therefore, $\phi(H)=(HK)/K$.

All of the criteria for the First Isomorphism Theorem have been satisfied, implying
$$
(HK)/K \simeq  H/\ker(\phi) \simeq  H/(H\cap K).
$$
