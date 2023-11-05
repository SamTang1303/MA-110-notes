---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 6.99 MA-110

> [!problem] Problem 6.99
> Define $\mathbb{Z}_{5} \longrightarrow \mathbb{Z}_{5}$ by $\phi(n) = n^{5}$.
> 1. Show that $\phi$ is a homomorphism of rings.
> 2. Compute $\ker(\phi)$.
> 3. Based on part 2., what do you conclude about $\phi$?

Define $\mathbb{Z}_{5} \longrightarrow \mathbb{Z}_{5}$ by $\phi(n) = n^{5}$.
1 ) Let $a,b \in \mathbb{Z}_{5}$.
$$
\begin{align}
\phi(ab) &= (ab)^{5}  \\
&= a^{5}b^{5} &&\mathbb{Z}_{5}\text{ is abelian} \\
&= \phi(a)\phi (b).
\end{align}
$$
And,
$$
\begin{align}
\phi(a+b) &= (a+b)^{5} \\
&= a^{5} + 5a^{4}b + 10a^{3}b^{2} + 10a^{2}b^{3} + 5ab^{4} + b^{5} \\
&= a^{5 } + b^{5} &&\text{multiplies of 5 equal 0 in } \mathbb{Z}_{5}  \\
&= \phi(a) + \phi(b).
\end{align}
$$
2 )
$$
\begin{align}
&\phi(0)=0^{5}=0\\
&\phi(1)=1^{5}=1\\
&\phi(2)=2^{5}=32 =2\\
&\phi(3)=3^{5}= 243 =3\\
&\phi(4)=4^{5}= 1024 =4.\\
&\end{align}
$$
Therefore, $\ker(\phi)=\{ 0 \}$.
3 ) Based on part 2), by [[Problem 3.52 MA-110|Problem 52]], we know $\phi$ is one-to-one. (This is also obvious by looking at the values of $\phi$.)
