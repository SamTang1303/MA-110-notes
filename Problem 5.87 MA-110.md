---
aliases:
  - Lemma 10.13
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.87 MA-110

> [!problem] Problem 5.87
> Let $H$ and $K$ be normal subgroups of a group $G$ such that $H \cap K = \{e\}$. Prove that $hk = kh$ for all $k \in K$ and $h \in H$, and then show that the map : $H \times K \to HK$ defined by $\phi(h, k) = hk$ is an [[Definition 3.1.2 MA-110|isomorphism]].

Let $H$ and $K$ be normal subgroups of a group $G$ such that $H \cap K = \{e\}$. Let $k \in K$ and $h \in H$. Because $H \trianglelefteq G$ and $K \trianglelefteq G$, $hk=kh_{1}$ for some $h_{1} \in H$, and $hk=k_{1}h$ for some $k_{1} \in K$. Thus,
$$
\begin{align}
kh_{1}&=k_{1}h \\
kk_{1}^{-1} &= h_{1}^{-1}h \\
&=e && kk^{-1}_{1} \in   K\text{ and } h_{1}^{-1}h \in  H
\end{align}
$$
Therefore, $h_{1}^{-1}h=e$, and thus, $h_{1}$ must be equal to $h$. Thus, $hk=kh_{1}=kh$.

Consider the map : $H \times K \to HK$ defined by $\phi(h, k) = hk$. Let $(h_{1},k_{1}), (h_{2},k_{2}) \in H\times K$.
$$
\begin{align}
\phi((h_{1},k_{1})(h_{2},k_{2})) &= \phi(h_{1}h_{2},k_{1}k_{2}) \\
&= (h_{1}h_{2})(k_{1}k_{2}) && \text{definition of }\phi \\
&= h_{1}(h_{2}k_{1})k_{2} && \text{associativity} \\
&= h_{1}(k_{1}h_{2})k_{2} && \text{shown above} \\
&= (h_{1}k_{1})(h_{2}k_{2}) && \text{associativity} \\
&= \phi((h_{1},k_{1}))\phi(h_{2},k_{2}) &&\text{definition of }\phi .
\end{align}
$$
Thus, $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]]. If $hk \in HK$, where $h \in H$ and $k \in K$, $\phi((h,k))=hk$, so $\phi$ is onto.
Suppose $(h_{1},k_{1}),(h_{2},k_{2})\in H\times K$ and $\phi((h_{1},k_{1}))=\phi((h_{2},k_{2}))$. Then 
$$
\begin{align}
h_{1}k_{1}&= h_{2}k_{2} \\
h_{1}h_{2}^{-1} &= k_{2}k_{1}^{-1}=e.
\end{align}
$$
Because $h_{1}h_{2}^{-1}=e$ and $k_{2}k_{1}^{-1}=e$, $h_{1}=h_{2}$ and $k_{1}=k_{2}$. So, by definition, $(h_{1},k_{1})=(h_{2},k_{2})$ and $\phi$ is one-to-one.

We have now shown that $\phi$ is a homomorphism, one-to-one, and onto, making it an isomorphism.