---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.186 MA-111

> [!problem] Problem 10.186
> Let $H$ be a subgroup of $G$. Prove that the set $K=\{ k \in G \mid kHk^{-1}=H \}$ is a subgroup of $G$, and that $H \lhd K$.

Let $H$ be a subgroup of $G$. Let $K=\{ k \in G \mid kHk^{-1}=H \}$. Clearly $eHe^{-1}=H$, so $e \in K$. Let $k_{1},k_{2} \in K$.
$$
\begin{align}
k_{1}k_{2}H(k_{1}k_{2})^{-1} &= k_{1}k_{2}Hk_{2}^{-1}k_{1}^{-1} && \text{shoes socks principle} \\
&= k_{1}Hk_{1}^{-1} && k_{2} \in  K \\
&= H && k_{1} \in  K.
\end{align}
$$
Thus, $k_{1}k_{2} \in K$, and $K$ is closed under multiplication.

By definition of being an element of $K$, $k_{1}H=Hk_1$. Therefore, $k^{-1}Hk=Hk^{-1}k=H$ Thus $k_{1}^{-1} \in K$, and $K$ satisfies all the criteria to be a subgroup of $G$.

Clearly $hHh^{-1}=H$ for any $h \in H$, so $H\subseteq K$. Let $k \in K$. By definition, $kHk^{-1}=H$, implying $kH=Hk$. Thus $H\lhd K$.
