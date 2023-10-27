$G, \bar G$ : Groups
$G\approx \bar G$ if  $\exists\phi: G\rightarrow \bar G$ such that -
1. $\phi$ is one-one
2. $\phi$ is onto
3. $\phi(ab)=\phi(a)\phi(b)\,\forall\,a,b\in G$
# Cayley's theorem
Every group is isomorphic to the a group of permutations.
**Proof**
Let $n=|G|$
For any $g$ in $G$, let a mapping $T_g:G\rightarrow G$ such that $T_g(x)=gx$.
$T_g$ is a permutation on $G$.
$$\bar G=\{T_g\mid g\in G\}$$
$\bar G$ is a group under binary operation of composition.
$\bar G$ is a permutation group of order $n$.
$\phi:G\rightarrow\bar G$ defined as $\phi(g)=T_g$ is one-one, onto homomorphism.
$\therefore G\approx\bar G$
