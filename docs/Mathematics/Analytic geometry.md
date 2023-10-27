# Syllabus
[[Second degree equations in three variables]]
[[Cone]]
[[Cylinder]]
[[Ellipsoid]]
[[Hyperboloid]]
[[Central conicoid]]
[[Conicoid]]
# General points
1. Intersection of two surfaces $F_1=0$ and $F_2=0$ will satisfy $F_1+\lambda F_2=0$ for any $\lambda$ . Use this property when asked to find out new surface which intersects two given surfaces at their point of intersection.
	1. Plane through line $\pi_1=0=\pi_2$ is $\pi_1+\lambda \pi_2=0$.
# Problems
1. Two perpendicular tangent planes to the paraboloid $x^2+y^2=2z$ intersect in a straight line in the plane $x=0$. Obtain the curve to which this straight line touches.
Solution
Given quadratic surface $$F:x^2+y^2=2z$$
$$xx_1+yy_1-z=z_1$$
$$\frac{x_1}{l}=\frac{y_1}{m}=\frac{-1}{n}=\frac{z_1}{p}$$ $$\frac{l^2}{n^2}+\frac{m^2}{n^2}=\frac{-2p}{n}$$

Condition for a plane $lx+my+nz=p$ to be tangent to $F$ is given by $$l^2+m^2+2pn=0$$
Let $L_1$ be the line of intersection given by $$L_1: my+nz=\lambda,\quad x=0$$
Any plane through $L_1$ is given by $$\Pi:my+nz-\lambda+kx=0$$
Condition of tangency $$k^2+m^2+2\lambda n=0$$
Which gives two values of the parameter $k$ as $$k=\pm\sqrt{-2\lambda n-m^2}$$
Two planes of $\Pi$ will be perpendicular if $$k_1k_2+m_1m_2+n_1n_2=0$$
That is $$k_1k_2=m^2+2\lambda n=-m^2-n^2$$
$$\therefore\quad \lambda=\frac{-2m^2-n^2}{2n}$$
$$L_1:2mny+2n^2z+2m^2+2n^2=0,\quad x=0$$
$$L_1:y+\frac{n}{m}z+\frac{m}{n}+\frac{n}{m}=0,\quad x=0$$
$$L_1:y+az+a+\frac{1}{a}=0,\quad x=0$$
We have to find the enveloping curve of the family of lines $L_1(a)$.
$$f(y,z,a)=y+az+a+\frac{1}{a}=0$$
$$\frac{\partial f}{\partial a}=z+1-\frac{1}{a^2}$$
$$\frac{\partial f}{\partial a}=0\Rightarrow a=\sqrt{\frac{1}{z+1}}$$
$$f(y,z,a)=0\Rightarrow y+z\sqrt{\frac{1}{z+1}}$$