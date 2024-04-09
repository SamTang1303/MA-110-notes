---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.201 MA-111

> [!problem] Problem 10.201
> Prove that every group of order $p^{2}$ is isomorphic to either $\mathbb{Z}_{p^{2}}$ or $\mathbb{Z}_{p}\times \mathbb{Z}_{p}$.

Let $G$ be a group of order $p^{2}$ where $p$ is prime. The order of the elements of $G$ must divide the order of the group. i.e. All (non-identity) elements must have order $p$ or $p^{2}$.

Case 1: There exists an element of order $p^{2}$. In this case, the group is cyclic and therefore isomorphic to $\mathbb{Z}_{p^{2}}$.

Case 2: There exists no element with order $p^{2}$. In this case, all (non-identity) elements will have order $p$. Our first task will be to find two normal subgroups of $G$. [[Problem 10.200 MA-111|Problem 200]] says that the center of $G$ will be non-trivial. If $Z(G)=G$ then $G$ is abelian and all subgroups will be normal, so we will consider the case in which $\left| Z(G) \right|=p$. Take any non-identity element $g_{0} \in G$ such that $g_{0} \notin Z(G)$.

Any (non-identity) of a cyclic group of prime order must generate the entire group because there are no non-trivial subgroups. Thus, $Z(G)$ cannot contain any non-identity element of $\langle g_{0}\rangle$ because then it would have to contain all the elements of $\langle g_{0}\rangle$. Therefore, $Z(G)\cap \langle g_{0}\rangle=\{ e \}$. Further, $N[\langle g_{0}\rangle]$ be larger than order $p$, because it contains both $Z(G)$ and $\langle g_{0}\rangle$. Because it is a subgroup of $G$, this implies it is of order $p^{2}$. Thus $N[\langle g_{0}\rangle]=G$ and $\langle g_{0}\rangle$ is normal.

We now have two subgroups, $Z(G)$ and $\langle g_{0}\rangle$, which are normal in $G$ and such that $\langle g_{0}\rangle \cap Z(G)=\{ e \}$. Note that there set product, $Z(G)\langle g_{0}\rangle$ is a proper superset of $Z(g)$ and is a subgroup of $G$. This is only possible if $Z(G)\langle g_{0}\rangle=G$. [[Problem 5.87 MA-110|Lemma 10.13]] can be applied to conclude that
$$
G=Z(G)\langle g_{0}\rangle \simeq Z(G)\times \langle g_{0}\rangle.
$$
$Z(G)$ and $\langle g_{0}\rangle$ are both cyclic groups of order $p$, and therefore isomorphic to the integers. Thus $G\simeq \mathbb{Z}_{p}\times \mathbb{Z}_{p}$.

