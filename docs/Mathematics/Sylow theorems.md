**Definitions**
Let $G$ be a group, and let $p$ be a prime number
- A group of order $p^k$ for some $k\ge 1$ is called a *p-group*. A subgroup of order $p^k$ for some $k\ge 1$ is called a *p-subgroup*.
- If $|G|=p^k m$ where $p\nmid m$ , then a subgroup of order $p^k$ is called a *Sylow p-subgroup* of $G$.
**Notation**
- $Syk_p(G)$ the set of Sylow p-subgroups of $G$
- $n_p(G)$ the number of Sylow p-subgroups of $G=|Syl_p(G)|$
**Theorems**
Let $G$ be a group of order $p^km$ where $p$ is prime, $m\ge 1$ and $p\nmid m$, then -
1. $Syl_p(G)\ne\phi$ that is Sylow p-subgroups exist.
2. All Sylow p-subgroups are conjugate in $G$, that is - if $P_1$ and $P_2$ are both Sylow p-subgroups, then there is some $g\in G$ such that $P_1=gP_1g^{-1}$. In particular $n_p(G)=[G:N_G(P)]$
3. Any p-subgroup of $G$ is contained in a Sylow p-subgroup
4. $n_p(G)\equiv 1\mod p$ 
## Proof of statement 1
>induction

*Case #1* $|G|=1$
trivially true

*Case #2* Let the statement be true for all groups of order less than $|G|$.
Consider [[#class equation]] $$|G|=|Z(G)|+\sum_{a\not\in Z(G)}[G:C(a)]$$
$$|G|=[G:C(a)]\cdot|C(a)|$$
$$\exists a\in G, |C(a)|\mid p^k\Rightarrow \text{theorem holds}$$
---
When $|C(a)|\nmid p^k\quad \forall a\in G$ :
$$p^k\mid |G|\text{ and } p^k\nmid |C(a)| \Rightarrow p \mid [G:C(a)] \quad \forall a\not\in Z(G)$$
$$\Rightarrow p\mid|Z(G)|$$
By [[#Cauchy's theorem]] $\exists x\in Z(G), |x|=p$
Let $N=\langle x\rangle$
$$N\lhd G$$
$$|G/N|=\frac{|G|}{N}=p^{k-1}m$$
$p^{k-1}m<p^km$, hence by inductive step, $G/N$ has a Sylow p-subgroup $\bar P$ . That is $|\bar P|=p^{k-1}$.
Let, $$P=\{g\in G|gN\in\bar{P}\}$$
$$P\le G$$
 $$N\le P$$
Thus, the homomorphism $f:P\rightarrow\bar P$ given by $f(x)=xN$ is onto.
$$\ker f=P\cap N=N$$
$$P/N\cong\bar P$$
$$\therefore |\bar P|=[P:N]=\frac{|P|}{|N|}$$
$$\Rightarrow |P|=|N||\bar P|=pp^{k-1}=p^k$$
That is $P$ is a Sylow p-subgroup of $G$.
## Proof of statement 3

# Applications
## Wilson's theorem
**Theorem**
$$(p-1)!\equiv -1\mod p$$ for every prime $p$.
**Proof**
Consider a permutation group $S_p$.
$a\in S_p$ and $|a|=p\Rightarrow$ $a$ is a $p$-cycle.
$$\therefore |Syl_p(S_p)|=n_p(S_p)=(n-1)!$$
By Sylow theorem $$n_p(S_p)\equiv 1\mod p$$
$$\therefore (n-1)! \equiv 1\mod p$$