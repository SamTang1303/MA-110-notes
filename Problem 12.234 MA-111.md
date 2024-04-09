---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 12.234 MA-111

> [!problem] Problem 12.234
> Let $F=\mathbb{Q}(\sqrt{ 5 })$ and let $E=\mathbb{Q}(i\sqrt[4]{ 5 })$, and notice that $F\subseteq E$. By Theorem 3.1, an automorphism $\phi:F\longrightarrow F$ is determined by setting $\phi(\sqrt{ 5 })\longrightarrow -\sqrt{ 5 }$. Show that $\phi$ cannot be extended to an automorphism $E\longrightarrow E$.

Let $F=\mathbb{Q}(\sqrt{ 5 })$ and let $E=\mathbb{Q}(i\sqrt[4]{ 5 })$, and notice that $F\subseteq E$. By Theorem 3.1, an automorphism $\phi:F\longrightarrow F$ is determined by setting $\phi(\sqrt{ 5 })\longrightarrow\phi(-\sqrt{ 5 })$. Suppose to the contrary that there exists an extension $\psi$ of $\phi$.
$$
\begin{align}
\psi(i \sqrt[4]{ 5 })^{2}&=\psi((i\sqrt[4]{ 5 })^{2}) \\
&= \psi(-\sqrt{ 5 }) \\
&= \sqrt{ 5 }.
\end{align}
$$
Therefore, $\psi(i\sqrt[4]{ 5 })=\pm\sqrt[4]{ 5 }$. But, $\pm\sqrt[4]{ 5 }$ are not elements of $\mathbb{Q}(i\sqrt[4]{ 5 })$, so this is a contradiction. Thus, there cannot be any extensions to automorphisms from $E\longrightarrow E.$