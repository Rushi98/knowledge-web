$$\mathcal{L}\{f(t)\}=\int_0^\infty{e^{-pt}f(t)dt}$$
$$f'(t) \rightarrow pF(p)-f(0)$$
$$f''(t) \rightarrow p^2F(p)-pf(0)-f'(0)$$
$$e^{at} f(t) \rightarrow F(p-a)$$
$$t f(t)\rightarrow -F'(p) $$
$$\frac{1}{t} f(t) \rightarrow \int_p^\infty{F(x)dx}$$

|$f(t)$|$\mathcal {L}\{f\}$|
|---|---|
|$\delta(t)$  |$1$  |
|$u(t)$|$\frac{1}{p}$|
|$t$|$\frac{1}{p^2}$|
|$t^2$|$\frac{2}{p^3}$|
|$t^3$|$\frac{6}{p^4}$|
|$t^{n+\frac{1}{2}}$|$\frac{\Gamma(n+1.5)}{p^{n+1.5}}$|

# PYQs
1. Prove $\mathcal{L}\{t^{n+\frac{1}{2}}\}=\frac{\Gamma(n+1+\frac{1}{2})}{p^{n+1+\frac{1}{2}}}$ 
	$$\mathcal{L}\{t^{ n+\frac{1}{2}} \} = \int_0^\infty{ e^{-pt} t^{n + \frac{1}{2}}dt } = \int_0^\infty{\frac{(pt)^{n+\frac{1}{2}}e^{-pt}}{p^{n+\frac{3}{2}}}
	 pdt}
	 = \int_0^\infty{\frac{x^{n+\frac{1}{2}}e^{-x}}{p^{n+\frac{3}{2}}}dx}
	 = \frac{\Gamma(n+\frac{3}{2})}{p^{n+\frac{3}{2}}}
	 $$