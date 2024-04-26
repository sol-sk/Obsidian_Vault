#psychology 
#research-methods 

[[PSYC 217]]

11-20-23
[[21.Psyc.217.Wk10Fri.topost.pdf]]
### *t*-test
> A statistical technique: is difference between two means something to be expected from random chance … if the null hypothesis is true? 
- If *t* obtained (pictured below) exceeds critical t value: suggests that the H0 might not be true
![[Screen Shot 2023-11-20 at 12.11.59 PM.png]]
#### t-test Ratio Logic
What could introduce errors in data?:
- Small sample size
- Poorly worded questions
- Effect of uncontrolled variables
- Between versus within subject designs

Determining if two means are significantly different
1. Find "*t* obtained" value
	1. Use formula to convert the mean diff and standard deviation into a *t* value
2. Refer to sampling distribution of t values
	1. Find critical *t* value for that df and alpha
	2. From table appendix C table C.2
	3. Don't need to find for 217
3. Make a decision

##### Step 2: Refer to sampling distribution for comparison
t distribution is actually a family of distributions
- Corresponds to sample size: each sample size has a different t distribution
- Distribution of each possible t value if the null hypothesis is true, at each sample size
**If there is no difference between means → the null hypothesis is true → *t* = 0** 

To locate the appropriate sampling distribution
> Degrees of freedom (***df***) = N - 2 (total sample - number of groups 

*df* is dependent on sample size, the larger the better

#### t-crit
To locate the appropriate $t_{crit}$: 
Alpha level ($a$)
- Stated as probability (0-1, conventionally 0.05)
- How likely are we to incorrectly reject the null hypothesis?
- How likely are we to say that means are significantly different, but it's actually due to chance
- If the null hypothesis is true, how likely are we to mistakenly say that the null hypothesis is not true? 



#### Two tailed, non-directional hypothesis
##### **N = ∞** ==when slides posted, add images==
When alpha = .05, 
2.5% chance in both pos and neg direction that the results are significant: 5% 
±1.96 are **$t_{crit}$ threshold to reject null hypothesis**
**$t_{obt}$ must exceed these**
$t_{obt}$ = 2.7 → we reject the null hypothesis

###### N = 6 (smaller sample size)
Tail end is larger: **$t_{crit}$ becomes ±2.78 to make area under curve equal 
Now, $t_{obt}$ = 2.7 → we do not reject the null hypothesis 

> If $|t_{obt}| > |t_{crit}|$, we reject the null hypothesis
> This primarily applies to two-tailed
#### One tailed, directional hypothesis: 
Most extreme 5% **on one side of distribution**
**$t_{crit}$  = 1.65

tobt has to be considered with directionality

##### Obtained *t* 
- Interval or ratio DV
- Nominal IV
	- Comparison between 2 levels of IV
- Calculation is a signal to noise ratio

##### Obtained *F*
- Interval or ratio DV
- Nominal IV
	- Comparison between >2 levels of IV
- Calculation is a signal to noise ratio

Under one particular condition (where you have 2 groups), *F* = $t^2$

**p value is attached to the statistic being calculated:**
> The probability that we will get obtained statistic in threshold = p value
- p < .05 means its more likely that we have obtained than being due to chance

#### Statistically significant
- Result is unlikely due to chance
- It is unlikely that the difference between the two groups has a *t* of 0


## Type 1 and Type 2 errors

Type 1 error
- False positive
- Null hypothesis is true but we rejected it 

Type 2 error
- False negative
- Null hypothesis is false but we retained it 

In research, Type 1 is more serious than Type 2 due to publication bias
