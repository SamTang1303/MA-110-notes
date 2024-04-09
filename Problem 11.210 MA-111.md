---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.210 MA-111

> [!problem] Problem 11.210
> Let $\beta \in F(\alpha)$ as in the [[Problem 11.209 MA-111|previous problem]]. Use the fact that $\{ 1,\beta,\beta^{2},\dots,\beta^{n} \}$ is a depended set to explain why $\beta$ must be algebraic over $F$. (Use Definition 11.2 in your explanation.) Find a relationship between the dimension of $F(\beta)$ as a vector space over $F$ and the dimension of $F(\alpha)$ as a vector space over $F$.

Let $\beta \in F(\alpha)$ as in the [[Problem 11.209 MA-111|previous problem]]. We have shown that $\{ 1,\beta,\beta^{2},\dots \beta^{n} \}$ is a dependent set, meaning for some $k_{0},\dots, k_{n}$
$$
k_{0}1+k_{1}\beta+k_{2}\beta^{2} + \dots + k_{n}\beta^{n} = 0.
$$
This means that $\beta$ is a root of the polynomial $k_{0}+k_{1}x+k_{2}x^{2}+\dots+k_{n}x^{n}$. Thus $\beta$ is algebraic over $F$ by definition 11.2. We know that $\{ 1,\beta,\beta^{2} ,\dots,\beta^{n}\}$ is a dependent set, so the dimension of $F(\beta)$ must be less than or equal to $n$.
