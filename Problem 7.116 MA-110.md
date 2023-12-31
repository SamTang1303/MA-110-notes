---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.116 MA-110

> [!problem] Problem 7.116
> Let $\mathbb{R}$ denote the ring of real numbers, let $R[x]$ be the ring of polynomials with real coefficients, let $(x^{2}+1)$ be the principal ideal generated by $x^{2}+1$, and let $\mathbb{C}$ denote the ring of complex numbers. Prove that $\mathbb{R}[x]/(x^{2}+1)\simeq \mathbb{C}$.

Consider the evaluation [[Problem 6.98 MA-110|evaluation homomorphism]] $\varepsilon_{i} : \mathbb{R}[x]/(x^{2}+1) \longrightarrow \mathbb{C}$. We have already shown that it is a [[Problem 6.97 MA-110|ring homomorphism]] in Problem 98. If $p(x) \in (x^{2}+1)$, then $p(x)=q(x)(x^{2}+1)$ for some $q(x) \in \mathbb{R}[x]$. Therefore,
$$
\varepsilon_{i}(p(x)) = p(i) = q(x)(x^{2}+1)=q(x)(-1+1)=0.
$$
Thus $p(x) \in \ker(\varepsilon_{i})$ and $(x^{2}+1)\subseteq\ker(\varepsilon_{i})$. If $p(x) \in \ker(\varepsilon_{i})$, then $i$ (and its complex conjugate $-i$) must be roots. The fundamental theorem of algebra tells us that $x-i$ and $x+i$ are factors of $p(x)$. Therefore, $(x+i)(x-i)=x^{2}+1$ is as well, telling us $p(x) \in (x^{2}+1)$. Thus $\ker(\varepsilon_{i})=(x^{2}+1)$.

Finally, we must show $\varepsilon_{i}(\mathbb{R}[x])=\mathbb{C}$. Let $z =a+bi \in \mathbb{C}$. Then $\varepsilon_{i}(xb+a)=ib + a=z$. Therefore, $\varepsilon_{i}$ is onto and $\varepsilon_{i}(\mathbb{R}[x])=\mathbb{C}$.

We have now satisfied the necessary criteria to apply [[Problem 7.113 MA-110|The First Ring Isomorphism Theorem]], which says
$$
\mathbb{R}[x]/(x^{2}+1) = \mathbb{R}[x]/\ker(\varepsilon_{i}) \simeq  \varepsilon_{i}(\mathbb{R}[x]) =\mathbb{C}.
$$
