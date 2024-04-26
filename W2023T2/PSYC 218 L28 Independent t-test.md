[[PSYC 218]]
3-27-24
[[PSYC218-L28-independent_ttest.pdf]]
### Pre-class reading

### Lecture
> Compare <span style="color:#0070c0">independent</span> vs <span style="color:#00b050">paired</span> vs <span style="color:#ffff00">single sample</span> t-tests

Which test? 
- Mean differs from specific pop mean ($\mu$)? 
- Do we know the pop $\sigma$? 
	- Yes: z-test
	- No: single sample t-test

- Are sample means diff from each other? 
- Are data correlated or independent? 
	- Correlated: correlated samples t-test
	- Independent: independent samples t-test

#### Independent t-test
- between-subjects *t*, Student's *t* (don't use), unpaired *t*
**Requirements**
- Compare 2 groups
- DV is interval/ratio
- DV is ~normal
	- $n_1$ > 30 & $n_2$ > 30
- Absence of outliers
- Homogeneity of variance
**Simplified t-test Formulas**
1. <span style="color:#ffff00">single-sample</span>
2. <span style="color:#00b050">paired</span>
3. <span style="color:#0070c0">unpaired/independent</span>
				![[Screenshot 2024-03-27 at 11.18.38 AM.png]]
$\bar{D}$ = mean difference score
$s_{\bar{D}}$ = standard error of the mean difference
$s_w$ = standard error between $\bar{X_1}$ and $\bar{X_2}$, **weighted**

**Conceptual t-test formulas**
			![[Screenshot 2024-03-27 at 11.23.10 AM.png]]

$n$ = # of people in *one condition*
N = # of participants altogether
3. standard deviation of mean 1 - mean 2, so divide by number of people per condition rather than double counting 
##### Computational formula for independent t-test
			![[Screenshot 2024-03-27 at 11.26.18 AM.png]]
$s^2_w$ = average, corrected by degrees of freedom (w = weighted)
if groups $n_1 = n_2$, no weighting

**Formula 2**
if the variances are different between groups, our IV impacts variability between scores ...  ?
- **Assumption of homogeneity of variance (between group 1 and 2)** 
	- If they are approx similar, we don't need to correct for it - if they are not, we do 
	- We won't have to calculate non-homogeneous things–just matters to know that we make it here because we're getting a weighted average of variance

Cohen's $d_s$
				![[Screenshot 2024-03-27 at 11.46.27 AM.png]]

-.75/.791 = -.95
