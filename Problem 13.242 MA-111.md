---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.242 MA-111

Let $F\subseteq E\subseteq K$ be a tower of fields, where $K$ and $E$ are splitting fields of polynomials $g(x)$ and $f(x)$, respectively, over $F$, and consider the following map $\Phi:$ ^8b7e0f
$$
\begin{align}
\text{Gal}(K/F)&\longrightarrow^{\Phi } \text{Gal}(E/F) \\
\sigma &\longmapsto  \sigma |_{E}
\end{align}
$$

^5f5e7a

where $\sigma|_{E}$ is the [[Definition 13.1 MA-111|restriction]] of $\sigma$ to the domain $E$. ^abf1dd

> [!problem] Problem 13.242
> Show that $\Phi$ really does take values in $\text{Gal}(E/F)$. (Does the restriction of $\sigma$ really map into $E$?) Does your explanation use the hypothesis that $E$ and $K$ are splitting fields?

Let $\sigma \in \text{Gal}(K/F)$ be an automorphism of $K$ that fixes $F$. Consider the function $\Phi(\sigma)=\sigma|_{E}$. Because $\sigma$ fixes $F$, and $F\subseteq E$, $\sigma|_{E}$ will still fix $F$.

Let $\{ g_{1},g_{2},\dots,g_{n} \}$ be the distinct roots of $g(x)$. For any $e_{i}$, because $\sigma|_{F(e_{i})}$ is an isomorphism out of $F(e_{i})$, we know that it must map $e_{i}$ to another root of $g(x)$. Therefore, $\sigma(e_{i})=\sigma|_{F(e_{i})}(e_{i}) \in E$, because $E$ contains all of the roots of $g(x)$. Thus, every root of $g(x)$ maps to an element of $E$, and every element of $F$ is fixed and must also map to an element of $E$. Thus, $\phi|_{E}(E)=E$ and the restriction of $\sigma$ does really map to $E$, implying the image of $\Phi$ is a subset of $\text{Gal}(E/F)$.

This explanation relies on $E$ being a splitting field.
