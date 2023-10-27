# Fundamental theorem of cyclic groups
Every subgroup of a cyclic group is cyclic. Moreover, if $|\langle a\rangle|=n$, then the order of any subgroup of $\langle a\rangle$ is a divisor of $n$; and, for each positive divisor $k$ of $n$, the group $\langle a\rangle$ has exactly one subgroup of order $k$.
**Proof**
*Every subgroup is cyclic*
Let $G=\langle a \rangle, H\le G, |H|=d, d\mid n$
If $H=\{e\}$, it is cyclic.
Else -
1. $\exists t\in\mathbb{N}, a^t\in H$
	$G=\langle a \rangle\Rightarrow \forall h\in H, h=a^t, t\in \mathbb{Z}$
	when $t<0$, $a^{-t}\in H, -t>0$
2. $m=\min\{t\mid t\gt 0, a^t\in H\}$
3. $H=\langle a^m \rangle$
	Let $b\in H, b=a^k$
	By division algorithm, $\exists\, q,r, 0\le r \lt m, \quad k=qm+r$
	$a^k=a^{qm}a^r\in H\Rightarrow a^r=a^ka^{-qm}\in H$
	$m$ is minimum, so $k=0$.
	That is $b\in\langle a^m \rangle$
	so, $H=\langle a ^m\rangle$.
3. $$e=a^n\in H\Rightarrow n=mq\Rightarrow m\mid n$$
4. $$\left|a^{m}\right|=\frac{n}{\gcd(n,m)}=\frac{n}{m}=d\Rightarrow m=\frac{n}{d} \text{ is unique}$$
