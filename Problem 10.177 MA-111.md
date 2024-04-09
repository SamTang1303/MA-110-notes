---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.177 MA-111

> [!problem] Problem 10.177
> Let $G$ be a group and let $X=\{ H\mid H\leq G \}$ be the set of all subgroups of $G$. For any $g \in G$, define $\phi_{g}(H)=gHg^{-1}$. Show that this definition describes a group action. Characterize the elements of $X_{G}$.

Let $G$ be a group and let $X=\{ H\mid H\leq G \}$ be the set of all subgroups of $G$. For any $g \in G$, define $\phi_{g}(H)=gHg^{-1}$.

Let $H \in X$. First we seek to show $\phi_{e}(H)=H$$\phi_{e}(H)=eHe^{-1}=H$ by absorption. Let $g,h \in G$. 
$$
\begin{align}
\phi_{gh}(H) &= (gh)H(gh)^{-1} \\
&= (gh)H(h^{-1}g^{-1}) && \text{shoes socks principle} \\
&= g(hHh^{-1})g^{-1} && \text{associativity} \\
&= g\phi_{h}(H)g^{-1} \\
&= \phi_{g}(\phi_{h}(H)).
\end{align}
$$
Thus, conjugation defines a valid group action. The [[Definition 10.7 MA-111|fixed points]], $X_{g}$ of this group action are the subgroups $H \in G$ such that $\phi_{g}(H)=gHg^{-1}=H$ for all $g \in G$, i.e., the normal subgroups of $G$.
