#cogs 
#research-methods 

[[COGS 303]]

9-29-23
## Pre class readings
### Hajek, Interpretations of Probability 
[[Hajek interpretations of probability.pdf]]
Sections 1 and 3.3-3.5

#### Section 1
Bearer of probability: outcome, event, or proposition

## Lecture

### What are probabilities?
How it works / What it means 

#### Mathematical probability
> Probability functions assign numeric values to things
> What are the objects of probability; to what are these values assigned? 
> 	Informally: events, outcomes
> 	Sets of possibilities
> 	Sentences (in a formal language)
> 	These are essentially equivalent

Probability theory was axiomatized by Kolmogorov in 1933

##### Axioms of probability
1. **Non-negativity**: probability P cannot be negative 
2. **Unity/Normalization**: probability of tautology T is one
3. **Finite additivity**: where A and B are mutually exclusive, P(A v B) = P(A) + P(B)

##### Theorems
**Theorem 1**
> The probability that A is false: P(~A) = 1 - P(A)
1. P (A v ~A) = P(T) = 1 (Unity)
2. A and ~A are mutually exclusive
3. Therefore, 1 = P(A) + P(~A)
4. P(~A) = 1 - P(A)

**Theorem 2**
> If A and B are equivalent, then P(A) = P(B)
1. If A and B are equivalent, they must either both be true or both be false
2. So, then P(~A v B) = 1 (one of the disjuncts must be true, so this disjunction is certain)
3. Also, ~A and B are mutually exclusive 
4. So, P(~A) + P(B) = P(~A v B) (Additivity)
5. So, P(~A) + P(B) = 1 (2,4)
6. So, 1 - P(A) + P(B) = 1 (by theorem 1)
7. So, P(A) = P(B)

What is P(A v B) if A and B are not mutually exclusive?
P(A v B) = P(A) + P(B) - P(A & B)
**How do we calculate P(A & B)?**
##### Conditional Probability
When A and B are sentences, and P(B) > 0, then the probability that A is true given that B is true: 
P(A|B) = (P(A & B))/P(B)

Therefore, probability of a conjunction:
P(A & B) = P(A|B)P(B)

**Theorem 3**
> P(A & B) ≤ P(B)

Two possible cases: 
	If P(A|B) = 1, then P(A & B) = P(B)
	If P(A|B) < 1, then P(A & B) < P(B)

Independence: 
A and B are independent just in case (if and only if) P(A|B) = P(A)
Example: A = drawing an ace, B = drawing a heart
	P(A) = 4/52 = 1/13 = P(A|B)
	Corollary, if A and B are independent, P(A & B) = P(A)P(B)
		Suppose A and B are independent 
		Then P(A & B) = P(A|B)P(B)=P(A)P(B)
	Example: probability of drawing the ace of hearts (A & B)
	P(A) = 4/52, P(B) = 1/4, P(A & B) = P(A)P(B) = 1/52

P(A & B) = P(A|B)P(B)
P(B & A) = P(B|A)P(A)
P(B & A) = P(A & B)
**P(A|B)P(B) = P(B|A)P(A)**

##### Bayes Theorem
> $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$

Posterior probability–$P(A|B)$
	The updated probability of A, given that B has occured
Prior probabilities–$P(A), P(B)$
	The probabilities of each independently
Likelihood–$P(B|A)$
	The measure of how likely B would B to occur if A were the case

**Principal of Total Probabilities**
Suppose A,C,D are mutually exclusive and jointly exhaustive
Then P(B) = P(B & A) + P(B & C) + P(B & D)
P(B) = P(B & A) + P(B & ~A)
Equivalent to Bayes theorem: (on slides)

##### Recap
1. P(A) ≥ 0 
2. P(T) = 1
3. Where A and B are mutually exclusive, P(A v B) = P(A) + P(B)
4. P(~A) = 1 - P(A)
5. If A and B are equivalent, P(A) = P(B)
6. P(A & B) ≤ P(A)
7. If A and B are independent, P(A & B) = P(A)P(B)

$P(A|B)$  = 
$\frac{P(A \lor B)}{P(B)}$
$\frac{P(B|A)P(A)}{P(B)}$ 
$\frac {P(B|A)P(A)}{P(B|A)P(A)+P(B|\lnot A)P(\lnot A)}$

**Example: Restaurant**
	70% ordered fries (F)
	40% ordered burgers (B) 
	20% ordered both (B & F)

$P(F|B) = \frac {P(B \land F)}{P(B)}$
.2/.4 = .5

**Example: Spam filter**
	40% of emails are spam 
	10% of spam emails use phrase = P(S|P)
	.001% of P($\lnot$S|P)
	P(P) = 10.001%

$P(S|U) = \frac {P(U|S)P(S)}{P(U|S)P(S)+P(U|\lnot S)P(\lnot S)}$
### Interpretations of probability
1. Epistemological/evidential
2. Subject (degree of confidence)
3. Physical (mind independent), eg coin flips

Alternatively: 
Objective (mind-independent)
	Frequencies
	Propensities
	Logical
	Think: chance
Subjective (mind-dependent)
	Classical 
	Bayesian (personalist)
	Evidential 
	Think: degree of confidence/belief
Unconstrained personalism: people's actual degrees of belief regardless of constraints of rational logic 
Orthodox Bayesianism: conforms to axioms and update according to Bayes' theorem 
Other constraints: math frequencies (that beliefs should conform to mathematical probability) / reflection 