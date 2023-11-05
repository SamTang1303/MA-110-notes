---
aliases:
  - The Third Isomorphism Theorem
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.90 MA-110

> [!problem] Problem 5.90
> Let $H$ and $K$ be a [[Definition 5.2 MA-110|normal subgroup]] of a group $G$ with $K \trianglelefteq H$. Consider the map
> $$
> \phi: G \longrightarrow (G/K)/(H/K)
> $$
> defined by $\phi = (gK)(H/K)$. Use this map and the [[Problem 5.84 MA-110|The First Isomorphism Theorem]] to prove that $G/H \simeq (G/K)/(H/K)$.

Let $H$ and $K$ be normal subgroups of a group $G$ with $K \trianglelefteq H$. Consider the map $\phi: G \to (G/K)/(H/K)$ defined by $\phi = (gK)(H/K)$.

First, we will verify the given map is a [[Definition 3.1.1 MA-110|homomorphism]]. Let $a, b \in G$.
$$
\begin{align}
\phi(ab) &=  ((ab)K)(H/K) && \text{definition of }\phi \\
&= (aKbK)(H/K) && \text{coset multiplication (with cosets of }K) \\
&= ((aK)(H/K))((bK)(H/K)) && \text{coset multiplication (with cosets of} (H/K)) \\
&= \phi(a)\phi(b). && \text{definition of }\phi 
\end{align}
$$

Secondly, we will show $\phi$ is onto and $\phi(G)=(G/K)/(H/K)$. Let $X \in (G/K)/(H/K)$. Then, by definition, $X=(gK)(H/K)$ for some $g \in G$. So $\phi(g)=(gK)(H/K)=X$ and $\phi$ is onto.

Finally, we will show $\ker(\phi)=H$. Note that because $(G/K)/(H/K)$ is a quotient group, $H/K$ is the identity of the group. Let $h \in H$, then $hK \in H/K$, and
$$
\phi(h) = (hK)(H/K) = (H/K). \qquad  \text{by absorbtion}
$$
Therefore, $h \in \ker(\phi)$ and $H \subseteq\ker(\phi)$.

Let $x \in \ker(\phi)$. Then $\phi(x)=(xK)(H/K)= (H/K)$ by definition of a [[Definition 3.4 MA-110|kernel]]. By [[Problem 4.58 MA-110|Problem 58]], $xK \in (H/K)$, implying $x \in H$. Therefore, $\ker(\phi)\subseteq H$. Further, $\ker(\phi)=H$.

We have now shown $\phi$ is an onto homomorphism from $G \longrightarrow (G/K)/(H/K)$ with kernel $H$. Thus, the First Isomorphism Theorem implies
$$
G/H \simeq (G/K)/(H/K).
$$
