1. LO1 Explain the purpose of using inferential statistics to evaluate sample data. 
2. LO2 Distinguish between the null hypothesis and the research hypothesis. 
3. LO3 Discuss how a sampling distribution is used to determine statistical significance. 
4. LO4 Describe when to use the t-test, and explain the three basic steps to using it. 
5. LO5 Describe the F test, including systematic variance and error variance. 
6. LO6 Compare and contrast Type I and Type II errors, including elements that influence the probability of making them, and their impact on scientific progress. 
7. LO7 Discuss multiple reasons statistically non-significant results may occur. 
8. LO8 Discuss how effect-size and confidence intervals contribute to the validity of conclusion beyond hypothesis tests.

### NHST
##### Null-hypothesis significance testing (NHST)
> The most common form of inferential statistics in psychology
> Any technique that results in the calculation of a p-value

##### Inferential statistics
> Determine whether the difference in group means reflects a real effect of the IV w/in whole population
> Real difference = **statistically significant**

### Statistical significance
##### Significance level/alpha level 
> Threshold for statistical significance
> How willing you are to be wrong if you conclude that there is an effect

###### Significance = p-value is smaller than alpha
> It is unlikely that the difference between sample means (or non-zero correlation) was due to random error
###### Larger sample or larger effect size = more likely to obtain stat. sig. results


### Null & Research hypotheses
##### Research hypothesis = $H_1$ 
For experiment: means are not equal in population
For correlational study: there is association between two variables in population 
##### Null hypothesis = $H_0$
For experiment: IV has no effect
For correlational: there is no relation

#### Alpha (sig.) level = typically set at .05 
> A lower threshold ≠ "more sig."

#### t-test = mean diff between 2 groups
![[Screen Shot 2023-12-15 at 5.06.37 PM.png]]
Larger t values associated with smaller p-values = more likely to reject $H_0$

**Formatted in papers:** t(36) = 4.37, p < .05
> 36 degrees of freedom
> t-obt = 4.37 
> p typically reported to reasonable value (2 sig. figs.)

###### Degrees of freedom (for 2 means) = (n1 + n2 - 2)
> Number of participants in each group minus number of groups

##### F-test = can be used on 3 or more groups
> If there is only IV and 2 groups, $F = t^2$
> **Ratio of systematic variance and error variance**

**Systematic variance** (numerator) = deviation of group means from grand mean (avg across all groups), increases when diff between means increases
> Between-group variance

**Error variance** (denom) = how much each score deviates from its group mean 
> Within-group variance


#### Pearson *r* correlation coefficient
Version of t-test = compares obtained correlation with null correlation 0.00

#### Type 1 & 2 errors
![[Screen Shot 2023-12-15 at 5.19.32 PM.png]]**Type 1 = false positive**
> Occur when, by chance, t-obt or F is large
> NHST framework; Type 1 error depends on alpha level (alpha = .01 = 1% chance of T1 error)

**Type 2 = false negative**
> Probability of making Type 2 error = beta (β)
> β depends on sample size (small sample size = larger β), effect size (larger effect size = smaller β), and alpha (low alpha = higher β) 

See also: **power**

**Consensus: Type I error is worse than Type II error**
However, long term Type II errors → file drawer effect, excluded from meta-anlys.

#### Methodological reform
- Pre-registering methods + analyses
- Adding more info post-publishing
- Journal in support of null hypothesis

### Interpreting Statistically non-sig. results
Could be Type II error
> Procedures, weak IV manip., DV measure unreliable/insensitive
> Alpha too low, sample too small

Retaining null hypotheses: study should be well-designed, manip. check, sensitive DV, evidence from multiple studies
Bayes D:

### Power
##### Power = 1 - P(Type II error)
Power of .80 = 20% chance of Type II error

Higher power = larger sample size
![[Screen Shot 2023-12-15 at 5.29.44 PM.png]]

##### Statistics software
Matlab, SAS, SPSS, R + R Studio

#### Selecting the right test
##### Two variable research
Nominal IV, Nominal DV = Chi-square
Nominal IV (2 groups), Interval/ratio DV = t-test
Nominal IV (3+ groups), Interval/ratio DV = one-way analysis of variance
Interval/ratio IV, Interval/ratio DV = Pearson correlation
##### Multi-variable or predictor variable research
Nominal IVs, Interval/ratio DV = Factorial design
Interval/ratio IVs, Interval/ratio DV = Multiple regression

#### Effect size
Cohen's d often reported w/ t-test results (two-group studies)
$r^2$ also functions as effect size
Any effect size can be significant with large enough sample
#### Confidence intervals
> Determines most likely range of actual population vals. 

In practice; 95% confidence interval = 83% replication interval 
Larger range = smaller sample/higher confidence level

#### Conclusion validity
> Extent to which conclusions are correct or reasonable

Quantitative data: interpreting effect-size and confidence intervals along w sig test results + study design details

#### Review Questions
1. Distinguish between the null hypothesis and the research hypothesis. When does the researcher decide to reject the null hypothesis? How are sampling distributions involved in this decision? 
2. What is meant by statistical significance? What elements influence whether obtained results will be significant? 
3. List and describe the three basic steps involved in using the t-test. 
4. Compare and contrast the t-test and the F test. Consider their numerators and denominators, and reasons to choose either test. 
5. Distinguish between Type I and Type II errors. How does alpha level relate to the probability of making a Type I error if the null hypothesis is true? 
6. How do Type I and Type II errors influence the accuracy of our published research overall? 7. What influences the probability of a Type II error? 
7. What is the difference between statistical significance and practical significance? Between statistical significance and effect-size? 
8. How does effect-size relate to practical or meaningful significance? 
9. Discuss reasons why a study might show non-significant results. 
10. Compare information obtained using a null hypothesis test (e.g., a t- test) with information from effect-sizes and confidence intervals. What information does each analysis provide?