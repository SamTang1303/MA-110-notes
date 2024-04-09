---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.269 MA-111

> [!problem] Problem 13.269
>     By graphing, check that $x^{5}-4x+2$ has exactly three real roots. Explain why it must therefore have two complex roots, $a+bi$ and $a-bi$. Use these observations to conclude that if $K$ is the splitting field of $x^{5}-4x+2$ over $\mathbb{Q}$, then $\text{Gal}(K/\mathbb{Q})$ must contain a 2-cycle.

As seen from graphing below, $x^{5}-4x+2$ has three real roots.
![[Screenshot 2024-03-17 at 4.10.48 PM.png|300]]
Conjugating complex numbers defines an automorphism on $\mathbb{C}$. Denote this map as $\phi$. Also, note that $\phi$ fixes all of the real numbers. If we consider the map $\phi|_{K}$, it will be an automorphism of $K$ that fixes the real numbers, and sends $a+bi$ to $a-bi$. i.e., it is an element of $\text{Gal}(K/\mathbb{Q})$ that fixes the real roots of $x^{5}-4x+2$ and swaps the complex roots, making it a two-cycle.
