---
aliases:
  - Orbit-Stabilizer Theorem
tags:
  - batch/school/class/ma111
  - batch/math
type: Theorem
---
# Orbit-Stabilizer Theorem

> [!definition] Theorem 10.10 MA-111 (Orbit-Stabilizer)
> If $G$ [[Definition 10.6 MA-111|acts]] on a set $X$, then the [[Definition 10.9 MA-111|stabilizer]] $\text{stab}(x)$ is a subgroup of $G$. Furthermore, $[G:\text{stab}(x)]=\left| Gx \right|$. (For finite groups, the size of the [[Definition 10.8 MA-111|orbit]] times the size of the stabilizer equals the size of the group.)

^86f189

*Proof.* Let $G$ be a group that acts on a set $X$ with $x \in X$. By definition of a group action, $\phi_{e}(x)=x$. This implies $e \in \text{stab}(x)$. Let $a,b \in \text{stab}(x)$. Then,
$$
\phi _{ab}(x)=\phi_{a}(\phi_{b}(x))=\phi_{a}(x)=x.
$$
Thus $ab \in \text{stab}(x)$ and $\text{stab}(x)$ is closed under multiplication. Furthermore,
$$
x=\phi_{e}(x)=\phi_{a^{-1}a}(x)=\phi_{a^{-1}}(\phi_{a}(x))=\phi_{a^{-1}}(x).
$$
Thus $a^{-1} \in \text{stab}(x)$ and $\text{stab}(x)$ is closed under inverses as well. Therefore $\text{stab}(x)$ satisfies all the criteria to be a subgroup of $G$.

Consider any $y \in Gx$. By definition, $y=\phi_{g}(x)$ for some $g \in G$. Define $f(y)= g\ \text{stab}(x)$. We must show that this functions is well defined. Let $y=\phi_{g}(x)=\phi_{h}(x)$. Then $x=\phi_{g^{-1}h}(x)$, and $g^{-1}h \in \text{stab}(x)$. Thus $\text{stab}(x) = g^{-1}h\ \text{stab}(x)$ and $g \ \text{stab}(x)=h \ \text{stab}(x)$.

Now we will show the function to be bijective. Let $\phi _{g_{1}}(x),\phi_{g_{2}}(x) \in Gx$ such that $g_{1}\ \text{stab}(x)= g_{2}\ \text{stab}(x)$. Then $g_{1} = g_{2}s$ for some $s \in \text{stab}(x)$. Thus, $\phi_{g_{1}}(x)=\phi_{g_{2}s}(x)=\phi_{g_{2}}(\phi_{s}(x))=\phi_{g_{2}}(x)$. Therefore $f$ is one-to-one. Let $g\ \text{stab}(x) \in G/\text{stab}(x)$. Then $\phi_{g}(x) \in Gx$ and $f(\phi_{g}(x))=g\ \text{stab}(x)$. Thus $f$ is onto as well as one-to-one. Therefore $\left| Gx \right|=[G:\text{stab}(x)]$.

