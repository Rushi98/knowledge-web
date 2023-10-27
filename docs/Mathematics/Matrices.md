# Cayley-Hamilton theorem
# Eigenvalues and eigenvectors
# Idempotent matrices
$$M^2=M$$
## $2\times2$ idempotent matrices
$$ \begin{bmatrix}
a & b \\
c & d 
\end{bmatrix} \times
 \begin{bmatrix}
a & b \\
c & d 
\end{bmatrix}
=
 \begin{bmatrix}
a^2+bc & b(a+d) \\
c(a+d) & d^2+bc 
\end{bmatrix}$$
### Case 1: $$a+d=1$$
$$a^2+bc=a$$
$$d^2+bc=d$$
$$\therefore ad=bc$$
$$\begin{bmatrix}
1 & 1 \\
0 & 0 
\end{bmatrix},
\begin{bmatrix}
1 & 0 \\
1 & 0 
\end{bmatrix},
\begin{bmatrix}
0 & 1 \\
0 & 1 
\end{bmatrix}
$$
### Case 2: $$a+d\ne 1$$
$$b=c=0;\quad a=d=1$$
$$\begin{bmatrix}
1 & 0 \\
0 & 1 
\end{bmatrix}$$
Hence, basis $$\left\{\begin{bmatrix}
1 & 1 \\
0 & 0 
\end{bmatrix},
\begin{bmatrix}
1 & 0 \\
1 & 0 
\end{bmatrix},
\begin{bmatrix}
0 & 1 \\
0 & 1 
\end{bmatrix},
\begin{bmatrix}
1 & 0 \\
0 & 1 
\end{bmatrix}
\right\}
$$

## Real symmetric matrices
- All eigenvalues are real.
- Eigenvectors of distinct eigenvalues are orthogonal.