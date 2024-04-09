---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.220 MA-111

> [!problem] Problem 11.220
> Let $\alpha$,$\beta$, and $\gamma$ be the roots of $x^{3}-2$. Show that the fields $\mathbb{Q}(\alpha)$,$\mathbb{Q}(\beta)$, and $\mathbb{Q}(\gamma)$ are all different.

Let $\alpha$,$\beta$, and $\gamma$ be the roots of $x^{3}-2$. From [[Problem 11.219 MA-111|Problem 219]] we know $\alpha=\sqrt[3]{ 2 }$, $\beta=\sqrt[3]{ 2 }e^{(2\pi/3)i}$, and $\gamma=\sqrt[3]{ 2 }e^{(4\pi/3)i}$. The Algebraic Extension Theorem gives the following bases for $\mathbb{Q}(\alpha)$, $\mathbb{Q}(\beta)$, and $\mathbb{Q}(\gamma)$:
$$
\begin{align}
\mathbb{Q}(\alpha) &: \{ 1,\sqrt[3]{ 2 },\sqrt[3]{ 4 } \}\\
\mathbb{Q}(\beta ) &: \{ 1,\sqrt[3]{ 2 }e^{(2\pi/3)i},\sqrt[3]{ 4 }e^{(4\pi/3)i} \}\\
\mathbb{Q}(\gamma ) &: \{ 1,\sqrt[3]{ 2 }e^{(4\pi/3)i},\sqrt[3]{ 4 }e^{(2\pi/3)i} \}\\
\end{align}
$$
Because $\mathbb{Q}(\alpha)$ does not span $i$, it cannot be the same as $\mathbb{Q}(\beta)$ or $\mathbb{Q}(\gamma)$. Note that
$$
-(\sqrt[3]{ 2 }e^{(2\pi/3)i}+\sqrt[3]{ 2 }e^{(4\pi/3)i})=\sqrt[3]{ 2 }.
$$
So, if you have $\gamma$ and $\beta$, using field properties, you can get $\alpha$. Thus $\mathbb{Q}(\alpha,\beta,\gamma)=\mathbb{Q}(\beta,\gamma )$. $\mathbb{Q}(\alpha)$ is a degree $3$ extension of $\mathbb{Q}$. Because $\beta \notin \mathbb{Q}(\alpha)$, $\mathbb{Q}(\alpha,\beta)$ must be a non-trivial extension of $\mathbb{Q}(\alpha)$. Thus, by the Algebraic extension theorem, $\mathbb{Q}(\alpha,\beta)$ must have dimension $>3$ as a vector space over $\mathbb{Q}$. $\mathbb{Q}(\beta)$ is also a degree three extension of $\mathbb{Q}$. $\mathbb{Q}(\gamma ,\beta)$ must be an extension of degree $>1$ of $\mathbb{Q}(\beta)$, because $\mathbb{Q}(\alpha,\beta)=\mathbb{Q}(\alpha,\beta,\gamma )$ has dimension $>3$ as a vector space over $\mathbb{Q}$. Thus, $\gamma$ cannot be an element of $\mathbb{Q}(\beta)$. 
