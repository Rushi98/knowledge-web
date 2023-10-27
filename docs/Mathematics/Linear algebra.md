[[Similarity]]]
[[Bilinear forms]]
[[Quadratic form]]
Show that $I-BA$ is invertible if $I-AB$ is invertible.
Proof -
Let $$C=(I-AB)^{-1}$$
$$(I-BA)BCA=B(I-AB)CA=BA$$
$$I=BA-BA+I=(I-BA)BCA+I-BA=(I-BA)(BCA+I)$$
$$\therefore (I-BA)^{-1}=BCA+I$$
---
(IFoS 2021)
Consider the following [[quadratic form]]: $$q(x,y,z)=2x^2+2y^2+6z^2+2xy-6yz-6zx$$
where $(x,y,z)$ are the coordinates of the vector $X$ with respect to the standard basis $\{(1,0,0),(0,1,0),(0,0,1)\}$ of $\mathbb{R}^3$. Find the expression of $q(x,y,z)$ with respect to the basis $$B=\left\{\left(\frac{1}{\sqrt{6}},\frac{1}{\sqrt{6}},\frac{-2}{\sqrt{6}}\right),\left(\frac{1}{\sqrt{2}},\frac{-1}{\sqrt{2}},0\right),\left(\frac{1}{\sqrt{3}},\frac{1}{\sqrt{3}},\frac{1}{\sqrt{3}}\right)\right\}$$
Is $q$ positive definite? Justify your answer.
**Solution**
$$A=\begin{bmatrix}
2 & 1 & -3 \\
1 & 2 & -3 \\
-3 & -3 & 6
\end{bmatrix}$$
$$q(X)=X^T A X$$
Change of basis matrix $$P=\begin{bmatrix}  
\frac{1}{\sqrt 6} & \frac{1}{\sqrt 6} & \frac{-2}{\sqrt 6} \\
\frac{1}{\sqrt 2} & \frac{-1}{\sqrt 2} & 0 \\
\frac{1}{\sqrt 3} & \frac{1}{\sqrt 3} & \frac{1}{\sqrt 3}
\end{bmatrix}^T$$
$$P^TAP=\text{diag}(9,1,0)$$
$\text{rank}(q)=2<3=dim(\mathbb{R}^3)$, hence $q$ is **not positive definite**.