[[PSYC 218]]
4-08-24
![[PSYC218-L30-ANOVA.pdf]]
### Pre-class reading

### Lecture
- Why is it called analysis of variance? 
- What are $MS_{between}, MS_{within}, F_{ratio}$
- What is the shape of the F-distribution? 
- What are *df* for ANOVA?
- What conclusion follows from ANOVA? What follow-ups? 


ANOVA used w 2< groups, but if used for 2 groups, $F = t^2$

"One-way" ANOVA = 1 IV
"Factorial" ANOVA = multiple IVs

(t-test tends to be more reliable, easier to understand effect size)

**Assumptions**
1. Sampled pop.s are normally dist. 
2. DV is interval or ratio
3. Homogeneity of variance
	1. Like t-test, we avg variance from diff conditions 
ANOVA is fairly robust to violations of assumptions (altho less than *t*) assuming N is relatively large and *n*s are relatively equal 

Why not just multiple t-tests? Each comes with its own $\alpha$ →  increases T2 error rate
- ANOVA has "family wise" $\alpha$: we can put in all data at once, do all comparisons at once → exactly .05 $\alpha$, max. power
- **Limitation**: <span style="color:#0070c0">always non-directional</span>

ANOVA hypotheses;
$H_0: \mu_{digits} = \mu_{letters} = \mu_{words}$
$H_1$ = At least one mean differs

##### ANOVA Formula
<span style="color:#ffff00">![[Screenshot 2024-04-08 at 11.19.22 AM.png]]</span>
![[Screenshot 2024-04-08 at 11.29.36 AM.png]]
**Computational:**

<span style="font-weight:bold; color:#00b050">df = number of conditions</span>
- *numerator df*: corrects SS between-groups = k - 1 (one $s^2$) 
- *denominator df*: corrects SS within-groups = N - k (k number of $s^2$s)

**Numerator**: 
- SS for difference between each group mean and the grand mean: $MS_{between}$

**Denominator:**
- SS for scores within each group: $MS_{within}$

##### $MS_{between}$
- Effect variance
- Systematic, groups
- How much DV varied as function of IV

##### $MS_{within}$
 - Error
 - Residual, observations
 - How much DV varied as function of indiv. differences
 
 **F-distribution is *asymmetrical***
#### F-ratio
 ![[Screenshot 2024-04-08 at 11.38.42 AM.png]]


**$\alpha$ is either .01 or .05 for F**
