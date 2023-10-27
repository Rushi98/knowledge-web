Let $V$ be a vector space of finite dimension over a field $K$. A bilinear form on  $V$ is a mapping $f:V\times V\rightarrow K$ such that, for all $a,b\in K$ and all $u_i,v_i\in V$ 
1. $f(au_1+bu_2,v)=af(u_1,v)+bf(u_2,v)$
2. $f(u,av_1+bv_2)=af(u,v_1)+bf(u,v_2)$
# Matrix form
$$f(u,v)=[u]^TA[v]$$ Where $A=[a_{ij}]$, where $a_{ij}=f(u_i,u_j)$.
# Change of basis
If $P$ is the [[change of basis]] matrix $$B=P^TAP$$ is matrix of $f$ in the new basis.
## Congruent matrix 
$B\simeq A$ if there is non-singular matrix $P$ such that $B=P^TAP$.
# alternating bilinear form
1. Alternating $f(v,v)=0$
2. Skew symmetric $f(u,v)=-f(v,u)$
Alternating → skew symmetric 
# symmetric bilinear form
$f(u,v)=f(v,u)$
Symmetric form iff any representation of $f$ is symmetric matrix.
- $D=P^TAP$ can be obtained by same sequence of elementary row and column operations.
## Real symmetric bilinear form - Law of inertia / Sylvester's theorem
When field $K$ is of reals $\mathbb{R}$
Let $f$ be a symmetric form on $V$ over $\mathbb{R}$. Then there exists a basis of $V$ in which $f$ is represented by a diagonal matrix. Every other diagonal matrix representation of $f$ has the same number $p$ of positive entries and the same number $n$ of negative entries.
The _rank_ and _signature_ of $f$ is defined as - $$\text{rank}(f)=p+n \quad \text{and} \quad \text{sig}(f)=p-n$$
## Positive definite
A real symmetric bilinear form $f$ is - 
1. _positive definite_ if $q(v)=f(v,v)>0 \quad \forall v \ne 0$
2. _nonnegative semidefinite_ if $q(v)=f(v,v)\ge 0\quad \forall v$
**Example 1** Dot product is positive definite.
## Corollary 
Any real symmetric quadratic form $q$ has a unique representation in the form $$q(x_1,x_2,\dots,x_n)=x_1^2+x_2^2+\cdots+x_p^2-x_{p+1}^2-\cdots-x_r^2$$ where $r=p+n$ is the rank of the form.
_OR_
Any real symmetric matrix $A$ is congruent to the unique diagonal matrix $$D=\text{diag}(I_p,-I_n,0)$$ where $r=p+n$ is the rank of $A$.