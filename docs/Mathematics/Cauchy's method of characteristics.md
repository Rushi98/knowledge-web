# Given
1. Non linear PDE $f(x,y,z,p,q)=0$
2. Curve $x=f_1(\lambda),y=f_2(\lambda),z=f_3(\lambda)$
# Ask
1. characteristic strips
2. solution of PDE passing through curve
# Method
1. Find $x_0,y_0,z_0,p_0,z_0$ given by $$\begin{aligned}
x_0&=f_1(\lambda)\\ 
y_0&=f_2(\lambda)\\
z_0&=f_3(\lambda)\\
p_0f_1'(\lambda)+q_0f_2'(\lambda)&=f_3'(\lambda)\\
f(x_0,y_0,z_0,p_0,q_0)&=0
\end{aligned}$$
2. Characteristic equations $$\begin{aligned}
x'(t)&=f_p\\
y'(t)&=f_q\\
z'(t)&=pf_p+qf_q\\
p'(t)&=-f_x-pf_z\\
q'(t)&=-f_y-qf_z
\end{aligned}$$
3. Solve characteristic equations with the initial conditions of $x_0,y_0,z_0$ at $t=0$.
4. Characteristic strips $$\begin{aligned}
x&=\phi_1(t,\lambda)\\
y&=\phi_2(t,\lambda)\\
z&=\phi_3(t,\lambda)
\end{aligned}$$
6. Eliminate $\lambda,t$ in the characteristic strips to obtain $\psi(x,y,z)=0$.
# Problems
# 1
Problem
Determine the characteristics of the equation $z=p^2-q^2$, and find the integral surface which passes through the parabola $4z+x^2=0,y=0$.
Solution
PDE
$$f(x,y,z,p,q)=0=z-p^2+q^2$$
Curve
$$\begin{align*}
x_0 & = f_1(\lambda) & & = 2\lambda\\
y_0 & = f_2(\lambda) & & = 0\\
z_0 & = f_3(\lambda) & & = -\lambda^2 \\
p_0\times 2 + q_0 \times 0 &= -2\lambda & \Rightarrow p_0 &= -\lambda\\
-\lambda^2-(-\lambda)^2+q_0^2 & = 0 & \Rightarrow q_0 &= 2\lambda^2
\end{align*}$$
Characteristic equations
$$\begin{align*}
x'(t) &= f_p & &= -2p \\
y'(t) &= f_q & &= 2q \\
z'(t) &= pf_p+qf_q & &= -2p^2 + 2q^2 \\
p'(t) &= -f_x - pf_z & &= -p \\
q'(t) &= -f_y - qf_z & &= -q
\end{align*}$$
Solution of characteristic equations
$$\begin{align*}
p(t,\lambda) &= -\lambda e^{-t} \\
q(t,\lambda) &= 2\lambda^2e^{-t} \\
x(t,\lambda) &= -2\lambda (e^{-t} - 1) \\
y(t,\lambda) &= -2\lambda^2(e^{-t}-1)
\end{align*}$$
