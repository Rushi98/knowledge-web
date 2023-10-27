($V$ vector space, $K$ field) 
<u>Definition A</u>
A mapping $q:V\rightarrow K$ is a quadratic form if $q(v)=f(v,v)$ for some  [[Bilinear forms#symmetric bilinear form|symmetric bilinear form]] $f$ on $V$.
- if $1+1\ne 0$ $f$ can be obtained as $$f(u,v)=\frac{1}{2} \left[q(u+v)-q(u)-q(v)\right]$$
<u>Definition B</u>
- A quadratic polynomial in $n$ variables $$q(x_1,x_2,\dots,x_n)=\sum_{i}c_ix_i^2+\sum_{i<j}d_{ij}x_ix_j$$
- If there are no cross product terms $x_ix_j$, $q$ is called _diagonal_.
- $q$ determines a real symmetric matrix $A=[a_{ij}]$, where $a_{ii}=c_i$ and $a_{ij}=a_{ji}=\frac{1}{2}d_{ij}$
$q$ can be written in the matrix form $$q(X)=X^TAX$$
where $X=[x_1,x_2,\dots,x_n]^T$ 
# Linear substitution
- A linear substitution of variables $X=PY$ gives $$q(X)=(PY)^TA(PY)=Y^T(P^TAP)A$$
Thus $P^TAP$ is matrix representation of $q$ in new variables.
## Orthogonal substitution
- A substitution $X=PY$ is _orthogonal substitution_ if $P$ is orthogonal and it yields a diagonal quadratic form. _See_ [[Similarity#Real symmetric matrices are orthogonally diagonalisable|orthogonal diagonalisation of symmetric matrices]]
