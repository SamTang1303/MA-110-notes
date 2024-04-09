---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 12.230 MA-111

> [!problem] Problem 12.230
> Let $p$ be prime. It is a fact that the polynomial $x^{p-1}+x^{p-2}+\dots+x+1$ is irreducible over $\mathbb{Q}$, and that its roots are $\omega,\omega^{2},\dots, \omega^{p-1}$, where $\omega =e^{2\pi i/p}$. Use these facts to determine the group $\text{Gal}(\mathbb{Q}(\omega)/\mathbb{Q})$.

Because every automorphism of $\mathbb{Q}(\omega)$ will fix $\mathbb{Q}$ by [[Problem 11.222 MA-111|Problem 222]], $\text{Gal}(\mathbb{Q}(\omega)/\mathbb{Q})=\{ \text{automorphisms of }\mathbb{Q}(\omega) \}$. By Theorem 12.1 we know that any automorphism on $\mathbb{Q}(\omega)$ will map $\omega$ to a root of $x^{p-1}+x^{p-2}+\dots+x+1$, i.e., $\omega^{n}$ for $0< n< p$. It also says that the image of $\omega$ determines the entire automorphism. Since there are $p-1$ different roots that $\omega$ can map to, $\text{Gal}(\mathbb{Q}(\omega)/\mathbb{Q})$ will be of order $p-1$.
Note that $\omega^{p}=(e^{2\pi i/p})^{p}=e^{2\pi i}=1$. Let $\phi_{a}$ be defined by the map $\phi_{a}(\omega)=\omega^{a}$ and $\phi_{b}$ be defined by the map $\phi_{b}(\omega)=\omega^{b}$.
$$
\begin{align}
\phi_{a}(\phi_{b}(\omega)) &= \phi_{a}(\omega^{b}) \\
&= \underbrace{\phi_{a} (\omega)\phi_{a}(\omega)\cdots\phi_{a}(\omega )}_{b} \\
&= \underbrace{\omega^{a}\omega^{a}\cdots\omega^{a}}_{b} \\
&= \omega^{ab} \\
&= \omega^{ab \text{ mod }p} && \omega^{p}=1.
\end{align}
$$
Thus, any element of $\text{Gal}(\mathbb{Q}(\omega)/\mathbb{Q})$ is determined entirely by the map $\omega\longmapsto \omega^{n}$ and multiplying two elements of $\text{Gal}(\mathbb{Q}(\omega)/\mathbb{Q})$ corresponds to multiplying that exponent mod $p$. Thus $\text{Gal}(\mathbb{Q}(\omega)/\mathbb{Q})$ is isomorphic to $\mathbb{Z}^{*}_{p}$.
