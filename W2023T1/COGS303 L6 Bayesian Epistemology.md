#cogs 
#research-methods 

[[COGS 303]]

10-13-23

### Pre class readings
Howson and Urbach [[Howson and Urbach Bayesian_Reasoning_in_Science.pdf]]
[[Salmon Bayes Theorem and the History of Science.pdf]]

## Lecture
### Bayesian epistemology:
- rational degree of belief satisfies the axioms of probability
- rational degree of belief is updated according to Bayes' theorem
- "radical" or "orthodox" Bayesians postulate no further requirements for rational degree of belief
#### Bayesian reasoning in science: 
- Scientific inferences are well-modeled using subjective probabilities
- confirmation of a scientific theory is well-modeled using subjective probabilities
#### Bayesian method in statistics: 
- Begin with a distribution of subjective priors
- Run some tests, conditionalizing on the cumulative evidence compiled

#### Can we formalize non-deductive logic? 
**Ampliative / Non-monotonic reasoning** 

#### Relating probability to arguments:
- What happens if we think of posterior probabilities as conclusions, and priors and likelihoods as premises: 
- Refer to Bayes theorem: $P(A|B) = \frac{P(B|A)P(A)}{P(B)}$
- P(A|B) = Conclusion
- P(A), P(B) = Priors
- P(B|A) = Likelihood/expectedness

Posterior probability = The updated probability of the hypothesis, given the evidence
Prior probabilities = The probabilities of the evidence and of the hypothesis considered apart from the evidence

Suppose: 
Ampliative
	1 > P(H|E) > t: then H is accepted, even though not entailed by the evidence
	So, it can be modeled
Non-monotonic (conclusion must change when premise changes)
- P(H|E) > t and then some new evidence E2 is found, such that P(H|E & E2) < t: then acceptance of H needs to be rescinded

Compare Bayes, etc. to Popper; 
	Popper thought hypotheses could not be confirmed, only falsified or corroborated

**Scientific confirmation**
	Confirmation as absolute certainty 
	Confirmation as posterior probability above some threshold (Consider Russel [[COGS303 L3#Bertrand Russell, "On Induction"]])
	Confirmaiton as the degree of support some evidence lends to a hypothesis
	Comparative confirmation: consider a piece of evidence and ask which a pair of competing hypothesis it favors
All of these can be modeled using *Bayes' theorem*

Confirmation as absolute certainty:
	Can be modeled with probability but is unattainable for empirical theories

Confirmation above a threshold
	Similar to *acceptance rule*
	Analogous to legal standards (e.g. beyond a reasonable doubt)

Confirmation as degree of support (Bayesian Confirmation theory)
	Qualitative: does the evidence confirm the hypothesis? (yes or no)
		E confirms H just in case: P(H|E) > P(H)
		Neutral: P(H|E) = P(H)
	Quantitative: how much does the evidence confirm the hypothesis? 
	Let c(H, E) denote the degree of confirmation E gives to H
		Difference: c(H, E) = P(H|E) - P(H)
		Likelihood ratio: c(H, E) = P(E|H) / P(E|~H)

Contrastive confirmation 
	E confirms (or rather, favors) H1 over H2 just in case: 
		P(E|H1) > P(E|H2)
	Likelihood ratio: P(E|H1) / P(E|H2) 
	"Likelihoodism" (Elliot Sober): Quasi-Baysian, because it doesn't include subjective priors

Modeling Explanation
- Is probability the logic for abductive reasoning? 
- What is the "best" explanation? 

**Explanatory Power**
Abductive argument structure: 
- Surprising fact E occurs
- If H were true, E would be expected
- Therefore, H is (probably) true
How might we model with with subjective probabilities? 
* *Surprising* fact E occurs: P(E) is low
* P(E|H) is high
* Therefore, P(H|E) is high

#### Relevance quotient: 
$\frac {P(E|H)}{P(E)}$
- RQ > 1, then E confirms H
- RQ < 1, then E disconfirms H
- RQ = 1, E is neutral for H
- P(E) us low and P(E|H) is high = E confirms H

### Objections to Bayesian philosophy
- Isn't science supposed to be objective?: This is what motivates Sober's Likelihoodist alternative
	- Response 1: objective methods don't tell us as much as it would appear (what does it mean to reject the null hypothesis at the 5% level?)
	- Response 2: Objective methods depend on the experimenters intentions
	- Response 3: The priors have little impact once we've done enough testing
	- Response 4: Deductive logic can't tell you if premises are true: should we expect this from induction?

"Writing down these formulas... Doing something correctly is one thing; knowing that you are doing something correctly, and why, is another thing" (Howson + Urbach)
-> tie to *context of justification*

#### Is Bayesian philosophy too subjective?
