---
aliases:
  - the quotient group is a group
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.76 MA-110

> [!problem] Problem 5.76
> Let $H$ be a [[Definition 5.2 MA-110|normal subgroup]] of a group $G$. Prove that the set $G/H$ is a group under [[Problem 5.74 MA-110|coset multiplication]].

^6bd883

Let $H$ be a normal subgroup of a group $G$, and consider the set $G/H$ under coset multiplication.

Let $A,B,C \in G/H$.
$$
\begin{align}
(AB)C = \{ ab : a \in  A, b \in  B \}\{ c: c \in  C \}&=\{ (ab)c : a \in  A, b \in  B, c \in  C\} \\
A(BC) = \{ a : a \in  A \}\{ bc: b \in  B, c \in  C \}&=\{ a(bc) : a \in  A, b \in  B, c \in  C\} \\
&= \{ (ab)c: a \in  A, b \in  B, c \in  C \}.
\end{align}
$$
Therefore, $G/H$ is associative.

By [[Problem 5.74 MA-110|Problem 74]], $G/H$ is closed under multiplication and therefore a valid binary operation.

Let $A \in G/H$. We can represent $A=aH$ and $H=eH$ where $a \in G$ and $e$ is the identity of $G$. Problem 74 states $AH=(aH)(eH)=(ae)H=aH=A$. Thus, by [[Problem 1.13 MA-110|the test for inverses]], $H$ is the identity of $G/H$.

Let $A \in G/H$. By definition, we can represent $A=aH$, where $a \in G$. By Problem 74, $(aH)(a^{-1}H)=(aa^{-1})H=H$. Therefore, every element of $G/H$ has an inverse.

Thus, $G/H$ under coset multiplication satisfies all of the criteria of a group.
