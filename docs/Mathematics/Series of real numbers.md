# Convergence tests

|test name|test|converges if|diverges if|fails if|use cases|
|-----|--------|---------------|---------|-------|-------|
|Ratio|$\frac{u_n}{u_{n+1}}=l$|$l>1$|$l<1$|$l=1$|
|Raabe|$n\left(\frac{u_n}{u_{n+1}}-1\right)=l$|$l>1$|$l<1$|$l=1$|not involving $e$|
|Log|$n\log\frac{u_n}{u_{n+1}}=l$|$l>1$|$l<1$|$l=1$|involves $e$|
|Bertrand 1|$\left(n\log\frac{u_n}{u_{n+1}}-1\right)\log n=l$|$l>1$|$l<1$|$l=1$|
|Bertrand 2|$\left(n\left(\log\frac{u_n}{u_{n+1}}-1\right)-1\right)\log n=l$|$l>1$|$l<1$|$l=1$|
|Gauss|$\frac{u_n}{u_{n+1}}=1+\frac{\lambda}{n}+O(\frac{1}{n^2})$|$l>1$|$l\le 1$|NA|
|nth root|$(u_n)^\frac{1}{n}=l$|$l<1$|$l>1$|$l=1$||
|Cauchy condensation|decreasing and $\sum{2^n a(2^n)}$||||converge or diverge together|
# Strictly alternating series
|test name|test|
|----|----|
|Leib|decreasing, tends to 0|

# Cauchy sequence
$|x_p-x_q|<\epsilon\ \forall p,q\ge m$
