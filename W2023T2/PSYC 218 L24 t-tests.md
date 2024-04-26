[[PSYC 218]]
03-17-24
![[PSYC218-L24-ttest_single_sample.pdf]]

### Pre-class reading
Ch 13
### Lecture
When using z-test, we know **population mean and standard deviation** ($\mu, \sigma$)
When using t-test, we **set a hypothetical population mean** and **estimate $\sigma$ using sample standard deviation *s***

Formulas for $t_{obt}$ and $z_{obt}$ are identical, except for t we divide by <span style="color:#0070c0">standard error</span> of *s* and not $\sigma$
![[Screenshot 2024-03-20 at 9.06.22 AM.png]]

because *s* <span style="font-weight:bold; color:#0070c0">systematically underestimates</span> $\sigma$: we use degrees of freedom *df*

t/z: the degree to which $\bar{X}_{obt}$  differs from $\mu$, in units of standard error $\sigma_{\bar{X}}$ (*z*) or  $s_{\bar{X}}$ (*t*)

**t-dist approximates z-dist as N increases**

##### *p*-value method
after calculating $t_{obt}$, determine p value, compare p and $\alpha$
we only do this with software

##### t-crit method
you know this one

##### Formatted conclusions
**Single-sample t-test**
"{sample} did x reliably more/less than the population, *t*(df) = X.XX, *p* = .XXX, *d* = X.XX."

**Bivariate correlation**
N-2
"There is a size, sign, and reliable? correlation between X and Y, *r*(N-2) = .XX, $p_{tails}$ = .XXX"

