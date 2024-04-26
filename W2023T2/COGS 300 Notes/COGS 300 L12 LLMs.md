[[COGS 300]]
2-27-24
[[annotated-COGS300-L12-LLMs.pdf]]
### Pre-class reading
[[mahowald.pdf]]
### Lecture
Quiz: 
-  PSS don't use distributed representations and don't degrade gracefully

Mahowald et al ‘23: 
- argue against formal/functional distinction?
- Overview of chatGPT progress since paper written? 

[https://dl.acm.org/doi/10.1145/3649468](https://dl.acm.org/doi/10.1145/3649468)  [https://dl.acm.org/doi/10.1145/3498366.3505816](https://dl.acm.org/doi/10.1145/3498366.3505816)

##### AI Hype: LLMs
**N-gram models**
- unigram: probability of target word
- bigram: probability of target word *given previous word*
- trigram: probability of target word *given previous 2 words*
	- beyond tri: too difficult/too much

**Deep learning**
- RNNs/LSTMs
- Better performance
	- Starts to forget beginning of sentence

![[Screenshot 2024-03-23 at 12.28.42 PM.png]]
**Transformer architectures**
- Specific type of NN used for LMs
- Allows for *attention*: can weight more important words for context
- Encoder transformer: BERT
- Decoder transformer: GPT

##### Large Language Models LLMs
- Main differences from earlier models: 
- Training: 
	- unsupervised pre-training, learns general patterns, probabilities, structures
	- supervised fine-tuning, smaller data sets used to fine-tune for specific tasks
- Black box: it can "tell" us what it knows
- Size: 
	- Ginormous (biggest at 530B), but human brain is more advanced w far fewer "parameters" aka neurons
	- Incr. parameters → new emergent behaviors (unpredictable)
	- GPT-3: 570GB text for pre-training: most of internet!

##### GPT-3
- Reinforcement Learning from Human Feedback (RLHF)
	- System completes task, gets feedback, learns

#### Mahowald et. al. (2023)
Examples of functional language competence: 
1. formal reasoning: relies on language but goes beyond rules of grammar
2. world knowledge and common sense reasoning: goes off on tangents
3. situation modeling: not good at keeping track of situation
4. social reasoning (pragmatics and intent)
