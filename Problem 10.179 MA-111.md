---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.179 MA-111

> [!problem] Problem 10.179
> Let $H$ be a subgroup of a group $G$ (not necessarily a normal subgroup). Let $X=\{ gH \mid g \in G \}$ be the set of left cosets of $H$ in $G$ (not necessarily a group). Then $H$ acts on $X$ by left multiplication: $\phi_{h}(gH)=hgH$. Prove that $kH \in X_{H}$ if and only if $k^{-1}Hk=H$.

Let $H$ be a subgroup of a group $G$ and let $X=\{ gH \mid g \in G \}$. Let $\phi_{h}(gH)=ghH$.

Let $kH \in X_{H}$. Then $\phi_{h}(kH)=hkH=kH$ for all $h \in H$. For this equation to hold true, $hk$ must be in $kH$. Thus $hk=kh_{1}$ for some $h_{1} \in H$. Left multiplying by $k^{-1}$ yields $k^{-1}hk = h_{1} \in H$. Thus $k^{-1}Hk\subseteq H$. Right multiplying by $k^{-1}$ yields $h=kh_{1}k^{-1}=(k^{-1}h_{1}k)^{-1}$ (**This is wrong. Check the wiki for a corrected version)**. Because $k^{-1}Hk$ is a group it is closed under inverses. Thus $h \in k^{-1}Hk$, and $H=k^{-1}Hk$.

Suppose $k^{-1}Hk=H$ for some $k \in G$. Left multiplying this equation by $k$ yields $Hk=kH.$ Let $h \in H$. 
$$
\begin{align}
\phi_{h}(kH)&=h(kH) \\
&= h(Hk) \\
&= Hk && \text{absorption} \\
&= kH.
\end{align}
$$
Therefore $kH \in X_{H}$ if and only if $k^{-1}Hk=H$.
