[[PSYC 218]]
2-02-24
[[PSYC218-L12-Regression_part2.pdf]]

### Pre-class reading
None
### Lecture
**Flipped class**
[Lecture videos](https://canvas.ubc.ca/courses/132566/pages/week-4-linear-regression?module_item_id=6473681)

Calculate $s_{Y|X}$
![[Screenshot 2024-02-10 at 7.21.42 PM.png]]
How far off, on average, is our regression line from the actual data? 
68% of scores will be within 1 standard error 

Homoscedasticity = consistent error
**Standard errors are only meaningful if the variability in Y is constant over values of X**
- if scatter is same = homoscedastic 

##### Multiple regression
**Symbols**
r = normal distribution
$r_s$ non-normal distribution, outliers = spearman's
$r_pb$ = one continuous (interval, ratio) variable, one dichotomous (binary) variable 
$\phi$ = two dichotomous variables (chi square!)

$\beta$ = standardized slope coefficient = $z_x$, $z_y$
$b$ = unstandardized slope coefficient = $X_i, Y_i$
$r^2$ = variability explained by predictor variable
$R^2$ = variability explained by regression model  

![[Screenshot 2024-02-10 at 7.52.46 PM.png]]


##### Meehl's 6th Law of Psychology
**Stastical "crud":** everything correlates with everything else, but most aren't meaningful = adding more predictors always increases $R^2$ = we need to remove as many *irrelevant* predictors as possible

When reporting $R^2$, **always** also report adjusted $R^2$


##### Categorical predictors in Regression
Arbitrary numbering can mess with regression 
**Multiple regression**
Criterion Y: grumpiness
Predictor $X_1$: Hours of sleep 
Predictor $X_2$: $Rain_{L1}$ or $Shine_{L2}$
	The numerical values are meaningless, it's essentially a binary system which refers to non-numerical meaning aka 1 = rain, 2 = shine

$b_1$ = -8.715
$b_2$ = -1.455
a = 124.442

If $X_2$ is coded as '2' aka shine → 1.455 fewer grumpy units 

If predictor $X_2$ has **3 potential values**: Rain, Clouds, or Shine, *we can no longer assign a slope coefficient ($b_2$)* → "**Dummy variable**"
- Collapse variables Clouds + Shine together and take average, where Clouds or Shine = 0 and Rain = 1
- (Or) Compare Clouds vs Rain for one slope and Clouds vs Shine for another

Coding of categorical predictors changes interpretation of *b*
Dummy coding is most common + simplest, but many other methods exist depending on hypotheses

