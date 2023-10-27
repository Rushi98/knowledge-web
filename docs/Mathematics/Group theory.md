# Centre of group
$$Z(G)=\{a\in G\mid ax=xa \,\forall\, x\in a\}$$
- Centre is a subgroup.
# Centraliser
$$C(a)=\{g\in G|ag=ga\}$$
- $C(a)$ is a subgroup
# Wilson's theorem
$$n\in\mathbb{N}, n>1 \text{ is prime } \Leftrightarrow (n-1)!\equiv -1\mod n$$
**Proof**
1. 
# [[Abelian groups]]
[[Cyclic groups]]
# Lagrange's theorem
If $H$ is a subgroup of $G$, then $|G|=[G:H]\cdot |H|$
# [[Sylow theorems]]
# Fermat's little theorem
If $p$ is a prime number, then for any integer $a$, $$a^p\equiv a\mod p$$
Consider group $U_p=\{1,2,\dots,p-1\}$
$$\left|U_p\right|=p-1$$
$$\therefore \forall a\in U_p\quad a^{p-1}\equiv1\mod p$$
$$\Rightarrow a^p\equiv a\mod p$$

# [[Normal subgroup]]
# Examples
## Klein four-group
$\{e,a,b,ab=ba\}$
$a^2=b^2=e$
**Matrix representation**
## Permutation group / automorphism / symmetry group
## Quaternion group
$\{1,-1,i,-i,j,-j,k,-k\}$
## Residue class mod $n$
## General linear group
## Special linear group

# Problems
<div style="page-break-after: always;"></div>


1. Prove that a group of order $30$ can have at most $7$ subgroups of order $5$.
	Let $G$ be a group of order $30$.
	Lemma: Any two distinct subgroups of order $5$ can have only one element common.
	Let $$A\le G, \quad B \le G, \quad A \ne B, \quad O(A)=O(B)=5$$
	$$X\subset Y \Rightarrow O(X)<O(Y)$$
	$$\quad A \ne B \quad \wedge \quad O(A)=O(B) \quad \therefore \quad A \not\subseteq B \quad \wedge \quad B \not\subseteq A$$
	$$H = A \cap B$$
	$$A\not\subseteq B \quad \wedge \quad  B \not\subseteq A \quad \therefore  H \neq A \quad \wedge \quad H \neq B \quad \therefore O(H) \lt 5$$Also $$ H \le G, \quad H \le A \quad\therefore O(H)|O(A) \quad \therefore O(H)|5 \quad \therefore O(H)=1 \quad \therefore H=\{e\}$$
	$$\boxed{A\cap B=\{e\}}$$

	If possible, let $G$ have $8$ distinct subgroups of order $5$, namely $A_1,A_2,\dots,A_8$.
	By above lemma, 
	for $$i\ne j \Rightarrow A_i\cap A_j=\{e\}$$
	Let, $$A_i=\{e\}\cup B_i \quad where,\quad B_i=A_i\setminus\{e\}$$
	$$\therefore i\neq j \Rightarrow B_i\cap B_j=\phi$$
	That is, all $B_i$ are exclusive of each other.
	Let $$B=\bigcup B_i$$
	$$\therefore O(B)=8\times O(B_i)=8\times4=32$$
	$$X=\bigcup A_i=B\cup\{e\}$$
	$$O(X)=32+1=33$$
	But, $$X\subseteq G$$
	Thus, $O(X)>O(G)=30$ is a contradiction. Hence, $G$ can have at most $7$ distinct groups of order $5$.

<div style="page-break-after: always;"></div>

2. Let $p$ be a prime number. Then show that $$(p-1)!+1\equiv 0\mod p$$ Also, find the reminder when $6^{44}\cdot 22! +3$ is divided by $23$.
	[[Sylow theorems#Wilson's theorem|Wilson's theorem]] $$(p-1)!+1\equiv 0\mod p$$
	$$\therefore 22!\equiv-1\mod 23$$	$$\begin{aligned}
	6^{44}&\equiv 6^{-2}&\mod 23 \\
	&\equiv 4^2&\mod 23\\
	&\equiv 16 &\mod 23\\
	6^{44}\cdot 22! +3&\equiv 16\times(-1)+3&\mod 23\\
	&\equiv 10 &\mod 23
\end{aligned}$$
