---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.111 MA-110

> [!problem] Problem 7.111
> Prove that the set $R/I$ is a ring under coset addition and coset multiplication.

Let $R$ be a ring with ideal $I$.

1 ) [[Problem 7.108 MA-110|Problem 108]] describes why $R/I$ is a commutative group under coset addition.

2 ) Let $a,b,c \in R$.
$$
\begin{align}
[(a+I)(b+I)](c+I) &= (ab+I)(c+I) && \text{coset product}\\
&= ((ab)c+I) && \text{coset product} \\
&= (a(bc)+I) && \text{associativity} \\
&= (a+I)(bc+I) && \text{coset product} \\
&= (a+I)[(b+I)(c+I)]. &&\text{coset product}
\end{align}
$$
Therefore, coset multiplication is associative. Further,
3 )
$$
\begin{align}
(a+I)((b+c)+I) &= a(b+c) + I && \text{coset product} \\
&= (ab+ac) + I && \text{multiplication distributes over addition} \\
&= (ab+I) + (ac+ I) && \text{coset addition} \\
&= (a+I)(b+I) + (a+I)(c+I). && \text{coset multiplication}
\end{align}
$$
We can argue similarly to show the opposite direction of associativity. Thus, it is coset multiplication also distributes over addition.

We have now shown all the criteria for $R/I$ being a ring under coset addition and coset multiplication.
