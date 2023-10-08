---
aliases:
  - The conjugate of a group is a subgroup
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.34 MA-110

> [!problem] Problem 3.34
> Let $H$ be a subgroup of a group $G$, and let $x \in G$ be some element. The *conjugate* of $H$ by $x$ is the set $xHx^{-1}=\{ xHx^{-1}:h \in H \}$. Prove that $xHx^{-1}$ is also a subgroup of $G$.

Let $H$ be a subgroup of a group $G$ and $x \in G$. Consider the conjugate of $H$ by $x$, $xHx^{-1}$.

Let $e_{G}$ be the identity of $G$. By the definition of a group $e_{G} \in G$. To show $e_{G} \in xHx^{-1}$ we must find some element $h \in H$ such that $xhx^{-1} =e_{G}$. Set $h=e_{G}$
$$
xe_{G}x^{-1} = (xe_{G})x^{-1}=xx^{-1} = e_{G}.
$$
Thus $e_{G} \in xHx^{-1}$.

Let $a, b \in xHx^{-1}$. By definition of the conjugate, for some $\overline{a},\overline{b} \in H$, $a=x\overline{a}x^{-1}$ and $b=x\overline{b}x^{-1}$. By definition of a group, $\overline{a}\overline{b} \in H$.
$$
\begin{align}
ab &= (x\overline{a}x^{-1})(x\overline{b}x^{-1})\\
&= (x\overline{a})(x^{-1}x)(\overline{b}x^{-1})\\
&= (x\overline{a})(\overline{b}x^{-1})\\
&= x(\overline{a} \overline{b})x^{-1} \in  xHx^{-1}.
\end{align}
$$

Let $y \in xHx^{-1}$. Then, for some $\overline{y} \in H$, $y=x\overline{y}x^{-1}$. By definition of a subgroup, $\overline{y}^{-1}$ exists and is in $H$.
$$
\begin{align}
y (x\overline{y}^{-1}x^{-1}) &= (x\overline{y}x^{-1})(x\overline{y}^{-1}x^{-1})\\
&= (x\overline{y})(x^{-1}x)(\overline{y}^{-1}x^{-1})\\
&= (x\overline{y})(\overline{y}^{-1}x^{-1})\\
&= x(\overline{y}\overline{y}^{-1})x^{-1}\\
&= x x^{-1}\\
&= e_{G}.
\end{align}
$$
We can similarly show that $(x\overline{y}^{-1}x^{-1})y=e_{G}$. Because we have shown $e_{G}$ to be the identity of $xHx^{-1}$, it is closed under inverses and satisfies all of the criteria to be a subgroup of $G$.
