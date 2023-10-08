---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.22 MA-110

> [!problem] Problem 1.22
> Suppose $G$ is a group, with $a$ and $b$ in $G$. Consider the equation $ax=b$.
> 1. Prove that $a^{-1}b \in G$.
> 2. Prove that by substituting that $x=a^{-1}b$ is a solution for the equation.
> 3. Prove that $x=a^{-1}b$ is the only solution for the equation $ax=b$; that is this solution is *unique*.

Let $\langle G,*\rangle$ be a group with $a,b \in G$.

1. By definition of a group, $a^{-1}$ exists and is unique. Because $*$ is a binary operator on $G$ and $a^{-1}$ and $b$ are both elements $G$, $a^{-1}b$ must be as well.
2. Let $x =a^{-1}b$. $a(a^{-1}b)=(aa^{-1})b=b$. Thus $x=a^{-1}b$ is a valid solution to the equation $ax=b$.
3. Let $x=c$ be a solution to the equation $ax=b$. Then, $ac=b$. $\langle G,*\rangle$ is a group, so we know $a^{-1}$ exists and is well-defined. Thus, $a^{-1}*a*c=a^{-1}*b$ and $c=a^{-1}*b$. Because we did this for a general solution, this solution must be unique. 
