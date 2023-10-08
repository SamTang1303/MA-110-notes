---
aliases: []
tags:
  - batch/school/class/ma110
  - subject/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-11
# Pre-Work Problems 40 Through 44 MA-110

> [!problem] Problem 3.40
> Draw up an operation table for each of the following groups. Then decide which pairs of these are [[Definition 3.1.2 MA-110|isomorphic]], in the sense of the intuitive "reordering and renaming" description given above; if reordering is necessary, show the reordering; also specify the renaming.
> 1. $\langle \mathbb{Z}_{4}, +\rangle$
> 2. $U(8)$
> 3. $\mathbb{Z}_{2}\times \mathbb{Z}_{2}$, with operation addition modulo 2 on each component.
> 4. $G=\{ 1,-1,i,-i \}$, with operation multiplication in the complex numbers. Recall that $i^{2}=-1$.

^fd9a05

$U(8)$ is [[Definition 3.1.2 MA-110|isomorphic]] to $\langle \mathbb{Z}_{2}\times \mathbb{Z}_{2}, +\rangle$. If rename the following symbols they should have the same multiplication table
$$
\begin{align}
1 &\to (0,0)\\
3 &\to (0,1)\\
5 &\to (1,0)\\
7 &\to (1,1)
\end{align}
$$
<div class="page-break" style="page-break-after: always;"></div> 

| $U(8)$ | 1   | 3   | 5   | 7   |
| ---- | --- | --- | --- | --- |
| 1    | 1   | 3   | 5   | 7   |
| 3    | 3   | 1   | 7   | 5   |
| 5    | 5   | 7   | 1   | 3   |
| 7    | 7   | 5   | 3   | 1   |


| $\langle \mathbb{Z}_{2}\times \mathbb{Z}_{2},+\rangle$ | (0,0) | (0,1) | (1,0) | (1,1) |
| ------------------------------------------------------ | ----- | ----- | ----- | ----- |
| (0,0)                                                  | (0,0) | (0,1) | (1,0) | (1,1) |
| (0,1)                                                  | (0,1) | (0,0) | (1,1) | (1,0) |
| (1,0)                                                  | (1,0) | (1,1) | (0,0) | (0,1) |
| (1,1)                                                  | (1,1) | (1,0) | (0,1) | (0,0) |

- - -

$\langle \{ 1,-1,i,-i \}, \times \rangle$ is [[Definition 3.1.2 MA-110|isomorphic]] to $\langle \mathbb{Z}_{4}, +\rangle$. If we give the following renaming
$$
\begin{align}
1 \to 0\\
i \to 1\\
-1 \to 2\\
-i \to3
\end{align}
$$
then the multiplication tables should match.

| $\langle \{ 1,-1,i,-i \}, \times \rangle$ | 1   | i   | -1  | -i  |
| ----------------------------------------- | --- | --- | --- | --- |
| 1                                         | 1   | i   | -1  | -i  |
| i                                         | i   | -1  | -i  | 1   |
| -1                                        | -1  | -i  | 1   | i   |
| -i                                        | -i  | 1   | i   | -1  |

| $\langle \mathbb{Z}_{4}, +\rangle$ | 0   | 1   | 2   | 3   |
| ------------------------------ | --- | --- | --- | --- |
| 0                              | 0   | 1   | 2   | 3   |
| 1                              | 1   | 2   | 3   | 0   |
| 2                              | 2   | 3   | 0   | 1   |
| 3                              | 3   | 0   | 1   | 2   |

<div class="page-break" style="page-break-after: always;"></div> 

> [!problem] Problem 3.41
> Suppose that $G$ is an abelian group. Prove that the function defined by $\phi(g) = g^{2}$ is a [[Definition 3.1.1 MA-110|homomorphism]] from $G\longrightarrow G$.

Let $G$ be an abelian group. Consider the function $\phi(g)=g^{2}$. Let $g_{1},g_{2} \in G$.
$$
\phi(g_{1})\phi(g_{2}) = g_{1}^{2}g_{2}^{2}
$$
and
$$
\phi(g_{1}g_{2}) = (g_{1}g_{2})^{2} = g_{1}g_{2}g_{1}g_{2} = (g_{1}g_{1})(g_{2}g_{2}) = g_{1}^{2}g_{2}^{2} = \phi(g_{1})\phi (g_{2}).
$$
Therefore, by Definition 3.1, $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]] from $G\to G$.

> [!problem] Problem 3.42
> Let $G=\langle a\rangle$, where $a$ has order $n$. Define a map $\phi: \langle \mathbb{Z},+\rangle \longrightarrow \langle G, \cdot\rangle$ by $\phi(i)=a^{i}$. Prove that $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]], but isn't one-to-one.

^problem-3-42

Let $G=\langle a\rangle$ where $a$ has order $n$ and suppose $\phi: \langle \mathbb{Z},+\rangle \longrightarrow \langle G, \cdot\rangle$ such that $\phi(i)=a^{i}$.

Let $x,y \in \mathbb{Z}$.
$$
\begin{align}
\phi(x) \cdot \phi (y) &= a^{x} \cdot a^{y}\\
&= a^{x+y}\\
&= \phi(x+y).
\end{align}
$$
Therefore, $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]].

$\phi$ cannot be one-to-one because $\mathbb{Z}$ is a countably infinite set, so $G$ would have to be as well, but we know $G$ is finite with order $n$. 

> [!problem] Problem 3.43
> Let $G=\langle a\rangle$, where $a$ has in infinite order. Define a map $\phi: \langle \mathbb{Z},+\rangle\longrightarrow\langle G, \cdot\rangle$ by $\phi(i)=a^{i}$. Prove that $\phi$ is an [[Definition 3.1.2 MA-110|isomorphism]].

Let $G=\langle a\rangle$ with identity $e$ where $a$ has infinite order and suppose $\phi: \langle \mathbb{Z},+\rangle \longrightarrow \langle G, \cdot\rangle$ such that $\phi(i)=a^{i}$.

None of our work in [[#^problem-3-42|Problem 42]] showing $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]] relies on $G$ having finite order, so we know it must also be a [[Definition 3.1.1 MA-110|homomorphism]] when $G$ has infinite order. So, we must only show $\phi$ is bijective.

Let $n,m \in \mathbb{Z}$. and suppose $\phi(n)=\phi (m)$. Then,
$$
\begin{align}
a^{n}&=a^{m}\\
a^{n}a^{-n} &=  a^{m}a^{-n}\\
e&= a^{m-n} && \text{Problem 16}
\end{align}
$$
Clearly $m=n$ satisfies this equation, but we must address the possibility that the equation is also satisfied for distinct $m$ and $n$. 

If this were the case, we would have $e=a^{k}$ for some $k\neq0$. Let $h \in G$ be arbitrary. We can represent $h=a^{r}$ in the following form: $a^{kp + v}$, where $p \in \mathbb{Z}$ and $v \in \{ 1,\dots k \}$ ($p$ being the quotient of $r/k$ and $v$ the remainder.) So,
$$
\begin{align}
a^{kp+v} &= a^{kp}a^{v}\\
&= (a^{k})^{p}a^{v}\\
&= e^{p}a^{v}\\
&= ea^{v}\\
&= a^{v}.
\end{align}
$$
This implies every element of $G$ can be represented in the form $a^{v}$ where $v \in \{1 \dots k  \}$. This is impossible because it would create a surjection from a finite set to an infinite set. Therefore, it must be true that $m=n$ and $\phi$ is one-to-one. (Sorry for the clunky proof; I couldn't think of a more elegant way to put it.)

We must now show $\phi$ is onto. Let $g \in G$. By the definition of a cyclic group, $g=a^{m}$ for some $m \in \mathbb{Z}$. Therefore, $\phi(m)=a^{m}=g$. Thus, $\phi$ must be onto as well, proving it is bijective and an [[Definition 3.1.2 MA-110|isomorphism]].


> [!problem] Problem 3.44
> Let $G$ and $H$ be groups, with identities $e_{G}$ and $e_{H}$, respectively. Let $\phi:G\longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]]. Prove that $\phi(e_{G})=e_{H}$. (Hint: consider $\phi(e_{G}e_{G})$.)

^0d5e59

Let $G$ and $H$ be groups, with identities $e_{G}$ and $e_{H}$, respectively. Further, let $\phi:G\longrightarrow H$ be a [[Definition 3.1.1 MA-110|homomorphism]].
$$
\begin{align}
\phi(e_{G}e_{G}) &= \phi(e_{G})\phi(e_{G}) && \text{Definition of a homomorphism}\\ 
\phi(e_{G}) &= \phi(e_{G})\phi(e_{G}) && \text{Definition of an identity}\\
(\phi(e_{G}))^{-1}\phi(e_{G}) &= (\phi(e_{G})^{-1}\phi(e_{G}))\phi(e_{G}) && \text{Left multiplication}\\
e_{H}&= e_{H} \phi(e_{G}) && \text{Definition of an inverse}\\
e_{H} &= \phi(e_{G}) && \text{Definition of an identity} \\
\end{align}
$$
