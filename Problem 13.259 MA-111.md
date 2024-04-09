---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.259 MA-111

> [!problem] Problem 13.259
> Let $K$ be the splitting field of $x^{n}-a$ over $\mathbb{Q}$. Suppose that $F\subseteq K$ is an extension of $\mathbb{Q}$ that contains $\mathbb{Q}$ that contains $\omega=e^{2\pi i/n}$, a primitive $n$th root of unity. Show that $\text{Gal}(K/F)$ is abelian.

Let $K$ be the splitting field of $x^{n}-a$ over $\mathbb{Q}$ where $a$ is positive. Suppose that $F\subseteq K$ is an extension of $\mathbb{Q}$ that contains $\mathbb{Q}$ that contains $\omega=e^{2\pi i/n}$, a primitive $n$th root of unity.

The roots of $x^{n}-a$ are $\sqrt[n]{ a }, \omega\sqrt[n]{ a }, \omega^{2}\sqrt[n]{ a }, \dots, \omega^{n-1}\sqrt[n]{ a }$. So, $K=(\omega, \sqrt[n]{ a })$. We are given that $\mathbb{Q}(\omega)\subseteq F$, so the elements of $\text{Gal}(K/F)$ must fix $\omega$. Thus, the elements of $\text{Gal}(K/F)$ are determined entirely by which root of $x^{n}-a$ they send to. Let $\sigma_{k} \in \text{Gal}(K/F)$ denote the map determined by $\sigma_{k}(\sqrt[n]{ a })=\omega^{k}\sqrt[n]{ a }$. Let $\sigma_{b},\sigma_{c} \in \text{Gal}(K/F)$ .
$$
\begin{align}
\sigma_{b} (\sigma_{c}(\sqrt[n]{ a })) &= \sigma_{b}(\omega^{c}\sqrt[n]{ a }) \\
&= \omega^{c}(\omega^{b}\sqrt[n]{ a }) \\
&= \omega^{c+b}\sqrt[n]{ a }\\
\sigma_{c} (\sigma_{b}(\sqrt[n]{ a })) &= \sigma_{c}(\omega^{b}\sqrt[n]{ a }) \\
&= \omega^{b}(\omega^{c}\sqrt[n]{ a }) \\
&= \omega^{c+b}\sqrt[n]{ a }.
\end{align}
$$
Thus, the composition of elements of $\text{Gal}(K/F)$ is commutative, implying the group is abelian.
