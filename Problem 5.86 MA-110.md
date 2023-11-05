---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
related:
  - "[[Definition 5.2 MA-110|normal subgroup]]"
---
# Problem 5.86 MA-110

> [!problem] Problem 5.86
> Prove that if $H$ and $K$ are subgroups of a group $G$, and $K \trianglelefteq G$, then $HK$ is a subgroup of $G$ and $K \trianglelefteq HK$.

Let $H$ and $K$ be subgroups of a group $G$, and $K\trianglelefteq G$. First, we will show the set $HK$ is a subgroup of $G$.

1 ) Since $H$ and $K$ are groups, $e \in H$ and $e \in K$. Therefore, $e=e e \in HK$.
2 ) Let $h_{1}k_{1},h_{2}k_{2} \in HK$.
$$
\begin{align}
(h_{1}k_{2})(h_{2}k_{2}) &= (k_{3}h_{1})(h_{2}k_{2}) && \text{for some }h_{3} \in  H, K\trianglelefteq G\\
&= k_{1}(h_{3}h_{2})k_{2} \\
&= (k_{1}h_{4})k_{2}&& \text{for some }h_{4} \in  H, K\trianglelefteq G\\
&= h_{5}(k_{1}k_{2})&& \text{for some }h_{5} \in  H, K\trianglelefteq G \\
&= h_{5}k_{3} && \text{for some } k_{3} \in  H, K \text{ is a group} \\
& \in  HK.
\end{align}
$$
Therefore, $HK$ is closed under multiplication
3 ) Let $hk \in HK$. Consider $k^{-1}h^{-1}$. We know $k^{-1}h^{-1}=h'k^{-1}$ for some $h' \in H$ by the normality of $K$. $k^{-1} \in K$ because $K$ is a group, and $h' \in H$, so $k^{-1}h^{-1} \in HK$. We will now justify that $h^{-1}k^{-1}$ is in fact the inverse of $hk$ in $HK$.
$$
\begin{align}
(hk)(k^{-1}h^{-1}) &= h(kk^{-1})h^{-1} \\
&= heh^{-1} \\
&= hh^{-1} \\
&= e.
\end{align}
$$
Thus, by [[Problem 1.13 MA-110|the test for inverses]] $HK$ is closed under inverses and satisfies all the criteria of a group.

Now, we will show $K\trianglelefteq HK$. Let $k_{1} \in K$ and $a \in HK$ where $a=hk_{2}$ and $h \in H, k_{2} \in K$.
$$
\begin{align}
ak_{1}a^{-1} &= (hk_{2}) k_{1}(hk_{2})^{-1} \\
&= hk_{2}k_{1}k_{2}^{-1}h^{-1} \\
&= hk_{3}h^{-1} && \text{where }k_{3}=k_{2}k_{1}k_{2}^{-1} \\
&= hh^{-1}k_{4} &&\text{for some }k_{4} \in  K, K \trianglelefteq G \\
&= k_{4} \\
& \in  K
\end{align}
$$
Therefore, by the [[Problem 5.73 MA-110|test for normal subgroups]], $K \trianglelefteq HK$.