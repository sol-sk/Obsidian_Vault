## [[COGS 300 L2 Foundations of COGS]]
1-11-24
[[COGS300-L2-foundations.pdf]]
### Pre-class reading
Debunking the AI myth (youtube)
### Lecture
**Overview of "Debunking"**
ChatGPTs existence already presents a challenge to Chomsky's ideas of language: learning a language and understanding its grammar without having any real understanding of semantics or having the generative restrictions (and strengths) that language typically has–
- i) Language should be generative of every possible sentence
- ii) within that language only and fitting within the restrictions of its grammar

### Big Ideas in Cognitive Science
#### Foundations of Cognitive Science
**Behaviorism** - early 20th c
- Psychology is an experimental science
- "Extreme" version: stimulus/reinforcement is the *sole* method of language acquisition
- This is core issue: rejects the "mind" as part of study; all psych is stim-response + conditioning (cf. linguistic structuralism)
- Mind as "middle man" between stim-behavior

Is it dead? Chomsky says it "keeps coming back" despite being refuted countless times

**Computation** → **Representation**
- Birth of computing machines: computation (~ cognition / thought) as a physically fully specified and implemented process
- Turing machine (theorized and then later implemented in the 40s)
- **Cogntition as physically implemented process**
- **Cognition as operation of computational processes on representations**
	- Negation of behaviorism, focusing on the mind between stim-behavior
- De-abstracting

Parallel development of programming languages and models of cognition

**Neural networks**
- Computations inspired by brain 
Two false starts:
- Perceptron
- Parallal distributed processing
Deep neural networks
- Do their own pattern recognition
- Multiple hidden layers
- Siri, google translate, self-driving cars, 
- ChatGPT, Dall-E
- Primarily applied, but informing theory 

**Extended mind**
Cognition is beyond brain: relies on tools
- Physical: calculator, pen + paper, etc. 
- Behavioral: language, sketching, visualization

**Cultural evolution**
- Cognitive tools and culture are the products of a long process of cultural evolution
	- Cumulative cultural evolution
- Features of cultural evolution may explain many properties of cognition that were previously attributed directly to the brain
	- Some features of language, cognition may be innate, or due to shaping by cultural evolution 

## [[COGS 300 L3 Turing Machine]]
1-16-24
[[COGS300-L2-Turing.pdf]]
### Pre-class reading
[[COGS300-clark13-ch1-1.pdf]]
[Online Turing Machine demo](https://turingmachine.io/)
### Lecture
Is cognition computation?

**Heavily computational leanings of early cognitive science inspired by:** 
- systems of formal logic 
- Turing machine 
- physical computers

#### Formal logic
**Syntax:** primitive symbols, operator symbols, rules of inference

#### Turing machine
Counting in reverse binary (1000 = 1, 0100 = 2, etc.)
'#' = head - but what if we don't need special symbol? 

Extra component = *states*
- Now can remember previous symbol on tape 
- Return/compute

Algorithm 2: if tape is empty, start anywhere after the initial 1 in return
1. Compute: 0 → 1, move left, return
2. Return: 0 → 0, move left, return
3. 1 → 0, move right, compute
4. 1 → 1, move right, compute

##### Universal Turing Machine
- Church-Turing thesis: a function is *algorithmically computable iff it can be computed by a Turing Machine*
- A Turing-complete comptuer is a device that can implement algorithms for any computable function

→ **Is the human brain a computer?**
Technically yes? Brain *could be a machine* but is this helpful for our understanding?

##### [Turing Drawings](https://maximecb.github.io/Turing-Drawings/#3,4,0,1,3,2,3,0,0,1,2,0,2,3,1,2,3,1,3,0,0,1,3,2,1,2,2,1,3,1,1,1,1,1,1,1,1,0)
2 dimensional rather than 1

##### Turing Test
a proposed threshold for identifying something/someone as an intelligent agent • human + hidden conversational partner • ongoing open-ended conversation • human thinks it’s talking to another human: intelligent agent!

## [[COGS 300 L4 Language as PSS]]
1-23-24
[[COGS300-L4-langage_as_SS.pdf]]
### Pre-class reading
[[COGS300-pinker07-ch4.pdf]]
[[COGS300-newellandsimon76.pdf]]
### Lecture


#### Pre lab
Robot movement in a tunnel

If obstacle is hit: search for opening; if opening on L, move L. if opening on R, move R. If opening not on L or R, halt. 

## [[COGS 300 L5 Tomasello v. Pinker]]
1-25-24
[[COGS300-L4-langage_as_SS.pdf]]
[[COGS300-L5-language_not_instinct.pdf]]
### Pre-class reading
[[COGS300-tomasello05.pdf]]
> First, I argue that although many people bandy about rather loosely the notion of an innate language module, ***the oniy theoretically coherent version of such a module that has ever been proposed is that of Generative Grammar***-in which resides a priori the theoretically-specific linguistic structures of Universal Grammar. This and only this is Pinker’s “language instinct.” Second, I argue that this view of language and its development, though coherent, is wrong. All of the most important lines of evidence that Pinker’s new book adduces for an innate Universal Grammar are also compatible with a less rigidly nativistic view of language acquisition in which there is a biological foundation for language, just not in the form of specific linguistic structures preformed in the human genome. Finally, I argue that there is an alternative linguistic theory, or group of theories, that should be especially attractive to cognitive developmentalists because they are much more compatible with what is known about development in other domains of human cognition. (133)

> Generative Grammar takes as its model of natural language formal languages such as mathematics and propositional logic. From this original metaphor, everything else in the theory flows. Most important, in formal languages the distinction between syntax and semantics is absolute and rigorously maintained (134)

> The issue, then, is not whether human beings are biologically prepared for language acquisition; they are. The issue is whether human beings come into the world equipped with an innate linguistic module that contains from the outset adult linguistic structures of the Generative Grammar kind. (137)

> Universality is just as consistent with a view in which human beings all over the world are faced with similar communicative problems and have similar cognitive and physical re- sources with which to solve them. Bates’ (1984a) well-known analogy is that all human beings eat mostly with their hands, but that does not mean that there is an eating-with-the-hands gene (137)

> Modularity is very often the result of developmental processes, not their cause. In this view, instead of being seen as an innate encapsulated module already containing its adult structures, language may be seen as “a new machine made out of old parts” that becomes modularized and localized in the brain as ontogeny proceeds (144)

>  If children’s analogizing is not based on abstract linguistic symbols but rather on concrete words and semantically based classes of words, then we would never expect the errors that Generative Grammarians hypothesize as “logical.” (145)
* see Bates

> The major opposition in language is not between syntax and semantics, but between linguistic symbols and their meanings: **signifiers and signifieds**, forms and functions, symbols and meanings. Within the signifier/form/symbol pole, we may then distinguish between different types of linguistic signs, for example, lexical, morphological, and syntactic. Within the signified/function/meaning pole we may distinguish between semantic and pragmatic functions. (149)

> For Cognitive and Functional linguists, the creativity of language comes from the tendency of human beings to create categories in their language, (150)

> All groups of human beings have certain experiences they wish to communicate to others and have evolved the ability to use conventional symbols to do so. All groups of human beings have the ability to categorize these symbols and form combinations of them, and to extract schematic patterns of those combinations involving hierarchical organization. All groups of human beings engage in certain forms of social interaction and attention directing. All groups of human beings have the same vocal-auditory channel, which requires them to communicate their experiences by expressing symbols linearly, one at a time. 
> Given these “constraints,” all groups of human beings have at their disposal some combination of four and only four linguistic devices for communicating experience: individual symbols (lexical items), markers on symbols (grammatical morphology), ordering patterns of symbols (word order), and prosodic variations of speech (e.g., stress, intonation) (Bates & MacWhinney, 1982). (150)

> None of this is to deny that language skills may become more modularized during development, as do many domains of cognition (Karmiloff- Smith, 1992). But this developmental fact does not negate the phylogenetic and ontogenetic roots of language in such things as the basic cognitive processes involved in the understanding of event structures (Nelson, 1985, 1986) and on children’s growing understanding of the intentions of adults, including their linguistic intentions (Tomasello, in press;Tomasello, Kruger, & Ratner, 1993). (151)

> At heart, Chomskyan nativism is a philosophical endeavor language is Not an Instinct 153 to discern by means of logic what is uniquely and innately human. Cogni- tive and Functional approaches are scientific endeavors aimed at under- standing how people learn and use natural languages (153)
### Lecture
(L4 cont.)
##### Chomsky Hierarchy
- Word chain devices don't have memory: will generate ungrammatical sentences bc. they don't remember previous word choice (keep track of previous dependencies)

##### Elaborating our PSS
**X-bar theory**
- Template that all phrases in any language conform to 
- Pinker says this is *innate*: language acquisition = figuring out how lang. realises these meta-rules

***Disclaimer***: Principles + parameters approach to grammar is no longer mainstream in syntax

**Innateness, weak version**: language relies on species-specific, genetically coded cognitive and physiological features that are present (though not necessarily expressed) in humans from birth
- **Descended larynx**

**Modularity**: 
- The language faculty = an “organ” whose internal representations & processes are domain-specific and is informationally encapsulated (i.e. does not need to continuously refer to other cognitive systems to operate) 
- evidence: 
	- uniqueness of structures (no parallels to phrase- structure outside of language?) 
	- double dissociations (general cognitive deficits do not necessarily affect language and vice versa) 

**Innateness, strong version**: 
- Language relies on a modular language faculty that is species-specific, genetically coded and is present (though not necessarily expressed) in humans from birth


 🐧🍴🤢🐟 
 🤢🐟 🍴 🐧
 🐧🍴🤢🐟🍴🤢🪸

#### Tomasello
Arguments against innateness
- universality of languages 
	- We are just all using our shared tools to fulfill shared needs
- univerally present/species-specificity ≠ genetic coding
- language universals
	- are they actually? 
	- english centric

 
 Arguments against modularity
 - domain-specific representations (chess connection)
 - double dissociation
	 - Linguistic savants: do have issues in multiple areas of language production
	 - specific language impairment: is it truly specific? 
	 - Brain localization can change w/o genetic encoding
	 - Localizaiton: Broca's, Wernicke's area: close to where auditory nerve connects to brain

## [[COGS 300 L6 Emergence and Self Organization]]
1-30-24
[[COGS300-L6-self-organisation.pdf]]
### Pre-class reading
pp. 1-15 [[kelso-ch1.pdf]]
### Lecture
#### Emergence & Self organization 
> I view the brain not as a box with compartments that contain sadness, joy, color, texture, and all the other "objects" and categories that one might think of. Instead, I envisage it as a constantly shifting dynamic system; more like the flow of a river in which patterns emerge and disappear, than a static landscape. "Meaningful patterns," as Sherrington said, "but never abiding ones." This is an entirely different image from the brain as a computer with stored contents or subroutines to be called up by a program. In nature's pattern-forming systems, contents aren't contained anywhere but are revealed only by the dynamics. Form and content are thus inextricably connected and can't ever be separated.
> [[kelso-ch1.pdf]]

Order emerges thru local interactions between parts of a system without control of an active agent

Individ rules → applied at large → pattern emerges

Moguls on ski hills formed from same motion + behavior direction repetitively; path formation
- Winding paths necessary for skiing (turns) → kickback, compression → indentation 
- No overarching control; individual skiiers control own actions but can't control formation of moguls

**Positive Feedback Loops**
- Given event makes the recurrence of that event more likely
**Negative Feedback Loop**
- Given event makes the recurrence of that event less likely 

**Combination → Predation, Population**
				![[Screenshot 2024-04-19 at 11.33.02 AM.png]]

**Control vs order parameters**
- Each cell can decide to keep or change color based on majority rule
	- Based on ratio required to change color pattern changes
	- Parameters → patterns
- Control parameter: something that can be manipulated/change
- Order parameter: is affected by control parameter

##### Terminology of dynamic analysis
**Open non-equilibrium systems**
- Open: exchanging energy/matter/info w/ env. 
- Non-equilibrium: without external output, system collapses
- Phase transitions: config 1 → config 2

**Rayleigh-Bénard instability**
**eg. heating oil** 
- Open system 
- Heated molecules want to rise: contact with cool air causes sink → circular motion, *convection cells*
- *Preferred states*
	- Weak heat: no pattern/movement is stable state
	- Strong heat: **instability**, system wants to roll (in one direction or the other, random but does not change once started)
		- Unstable bc pattern will stop w/o continuous heat
		- *Collective effect*: pattern is property of multiple molecule interaction

*q* = order parameter (large graph: y axis, other graphs: x axis)
- Here: amplitude of convection rolls
R (or V) = control parameter 
- Once certain point is reached → bifurcation
Dot = stable states w/in landscape
**Adaptive landscapes**

## [[COGS 300 L7 Kelso, Fireflies]]
2-01-24
[[COGS300-L7-self_org_examples.pdf]]
### Pre-class reading
[[camazineetal-ch10.pdf]]
### Lecture
Finger wagging; easier to perform symmetrical than asymmetrical movements, esp. at higher speeds
- Order parameter: phasing relationship
- Control parameter: speed

Termites
- Way more complicated nest than their intelligence level would suggest 
- Chewed mud puts pheremones into walls of nest
- Deposit mud balls in locations that have more - positive feedback loop

Fireflies
- Synchronize light flashing w/ artificial light
- Algorithm designed to describe flashing: rising, falling
	- 100-200 millisecond delay from excitation to flash, excitation resets after flash
	- Flash during excitation build: *resets* to zero in order to synchronize
	- Early reset during falling phase speeds up cycle to synchronize

## [[COGS 300 L8 Perceptron]] ** <span style="color:#ffff00">write out notes from slides</span>
2-06-24
[[gurney97-ch1-4.4.pdf]]
![[annotated-COGS300-L8-perceptron.pdf]]
## [[COGS 300 L9 ANNs]] ** <span style="color:#ffff00">write out notes from slides</span>
2-08-24
### Pre-class reading
[[clark13-ch4.pdf]]
### Lecture
![[annotated-COGS300-L9-connectionism.pdf]]

## [[COGS 300 L10 Deep learning]]
2-13-24
[[annotated-COGS300-L10-deep_learning.pdf]]
### Pre-class reading
[[lecunetal15.pdf]]
### Lecture
Computer: PSS or Connectionist? 
- Connectionist sys implemented by symbol sys, implementing symbol sys
- Marr's levels of analysis
	- Implemental lvl (physical?) → algorithmic/representational (rep./processes?) → computational lvl (what does it do?)

##### Connectionist networks
**Fully connected (feed forward)**
- All connections go in same direction, not skipping layers
- ![[Screenshot 2024-03-23 at 11.58.33 AM.png]]
- Sequential, no loops (= recurrent)
- Deep networks: at least 3 layers 
- If even one connection is dropped, no longer fully connected

##### Distributed representations
- Representation is formed from *distributed pattern* (PSS has 1:1 representation)
- Superpositional representations: similar activation patterns (diff types of 2s)

##### Subsymbolic representations
- The component parts of the "2" drawing light up diff neurons but mostly similar
- Not spatially organized, but
- Some NNs are sequentially/spatially dependent

##### Graceful degredation
- Performance doesn't plumment w removal of few units; not case w PSS

##### Convolutional network
- Convolutes pixels algorithmically, then pooling of convoluted mapping
- https://adamharley.com/nn_vis/

##### Recurrent network
- ![[Screenshot 2024-03-23 at 12.06.55 PM.png]]

##### CycleGAN
- First network converts input image x to output G(x)
- AI is trained to minimise difference between x and F(G(x))

## [[COGS 300 L11 AI Ethics]]
2-15-24
[[annotated-COGS300-L11-AI_ethics.pdf]]
### Pre-class reading
[[vallorandbekey17.pdf]]
### Lecture
##### AI ethics: 
> Should govt. implement regulations on AI uses? 

##### Benefits vs. harms
- Utilitarianism
- Kantian ethics; categorical imperative

##### Valor & Bekey
**Training**
- utilitarian perspective: 
	- benefit– driverless cars might make roads safer, save lives
	- harm– training is potentially unethical, public as nonconsenting test subj., can cause accidents
Unforseen errors: 
- NNs as complex self-organizing systems
- unpredictable emergent behavior–bias
Responsibility & oversight: 
- Boeing 737 crashes due to auto-adjusting system
- Who's responsible? 
The dreaded hungarian third person pronoun

AI TA–overhyped?

## [[COGS 300 L12 LLMs]]
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

## [[COGS 300 L13 Knowing vs Understanding]]
2-29-24
No slides today
### Pre-class reading
[[mitchell-krakauer-2023-the-debate-over-understanding-in-ai-s-large-language-models.pdf]]
### Lecture
What does it mean to *understand* speech? → Understanding in LLMs
- Repetition ≠ understanding
- Aid understanding through *analogy*

**Phonemes and Allophones**
- Allophone = specific realization of abstract unit (phoneme)
- /p/: can be realized in different ways in speech
	- $p^h, p, p^7$
	- pat = /$p^h$/
	- spat = /$p$/
	- Cutting off /s/ from spat sounds like bat because the p is unaspirated
- Allophones are in complementary distribution to each other 

From highest level to lowest level 
(Self)-Awareness of things 
Understanding things
Doing things
## [[COGS 300 L14 Embodied Cognition]]
3-05-24
[[annotated-COGS300-L14-embodiment.pdf]]
### Pre-class reading
[[wilsonandgolonka13-1.pdf]]
### Lecture
**Layers of embodiment:**
- Traditional "disembodied" cognitive science
- Body-cognition interactions
- Radical embodied cognition (replacement hypothesis)
	- cognitive processes do not stop at brain–occur throughout body

Algorithmic walking vs "passive walker"
- walking can be purely mechanical, reducing the complex <span style="color:#0070c0">*cognitive processes*</span><span style="color:#0070c0"> relying on *mental representations*</span> to a *simpler problem* in context of *<span style="color:#0070c0">body & environment</span>* 

Coordination does not require 'central' cognition
1. <span style="color:#ffff00">Task</span>: coordinate limb movements to wakl
2. <span style="color:#ffff00">Organism's resources</span>: joints natural springiness, skeleton, muscles, counterbalancing w arm swings, limited knee flexion
3. <span style="color:#ffff00">How can it use these</span>: see video
4. <span style="color:#ffff00">Any evidence that this is how we do task</span>: unsure! but we clearly do more than use algorithms

##### Tidy robots
[[annotated-COGS300-L14-embodiment.pdf#page=5&annotation=653R]]
	sensors; send signal to avoid obstacle
	researchers forgot to add the middle sensor: it doesn’t avoid blocks directly ahead of it
	pushes them to middle bc doesn’t reach wall, piles up 
	put on top of “messy” table: 
	not even designed to do this kind of tidying! 
	simple mechanism → complex behavior

##### Boids (bird flocks)
Easy to model, self organization enabled by *context* of algorithm
1. Separation
2. Alignment
3. Cohesion

##### Outfielder problem
1. <span style="color:#ffff00">What is the task</span>? Follow the ball and catch it
	- *Traditional explanation* Predicting trajectory of ball using initial direction, velocity & angle
	→ mental representation of future location of ball 
2. <span style="color:#ffff00">Organism's resources</span>: 
	- Noisy estimates of distance/direction/velocity/speed (propagating through projection)
	- Continuous kinematic info → infer underlying dynamics
	- ability to detect kinematic information
	- ability to locomote
3. <span style="color:#ffff00">How can it use these</span>:
	- *Heuristic*: using perception & movement to offset some aspect of complex kinematics 
	→ *linear optical trajectory*: outfielder makes initial observation, starts running in a direction such that the ball appears to be going straight
4. <span style="color:#ffff00">Any evidence that this is how we do task</span>:
	- prediction-based solution predicts a straight path
	- real paths are usually curved!

How do humans perceive AI art and its creative works? Is it considered less or more "artistic" and "creative" than human-made art (literary, visual, auditory)? For example, how would we react if we didn't know that the song to compare R and Python was written by an AI?

##### A-not-B problem
1. <span style="color:#ffff00">What is the task</span>?
	- Babies 8-12 mo.
	- Find attractive object hidden in location B after it has been hidden twice in location A. 
	- Using embodiment to understand why babies of this age tend to make the same error
2. <span style="color:#ffff00">Organism's resources</span>: 
	- Visual input
	- Activations in the sensorimotor cortex from previous reaches (~ a memory of those reaches)
	- Visual attn & ability to perform visually guided reaches
3. <span style="color:#ffff00">How can it use these</span>:
	- Memories of previous reaches + visual info interact to create a new reach 
	- *Sensorimotor memory*
4. <span style="color:#ffff00">Any evidence that this is how we do task</span>:
	- Are our predictions confirmed by data? 
	- Error should occur even if obj isn't hidden– confirmed!
	- Error can be reproduced in older children if task is sufficiently complex– confirmed too!

## [[COGS 300 L15 Situated cognition]]  ** <span style="color:#ffff00">write out notes from slides</span>
3-07-24
![[annotated-COGS300-L15-Situated_cognition.pdf]]
### Pre-class reading
[[robbinsandaydede09.pdf]]
### Lecture
**Otto's notebook**

## [[COGS 300 L16 Power Posing]]
3-12-24
### Pre-class reading
[[ranehilletal15.pdf]]
[[carneyetal10.pdf]]
### Lecture
[[COGS300-L16-power_posing.pdf]]

## [[COGS 300 L17 Dead Salmon]]
3-14-24
### Pre-class reading
[[simmonsetal11.pdf]]
### Lecture
[[COGS300-L17-dead_salmon.pdf]]
## [[COGS 300 L18 Evolution]]
3-19-24
[[COGS300-L18-evolution.pdf]]
### Pre-class reading
[[heyes12.pdf]]
**Evolution:** 
### Lecture
- Regards individuals & their genes– not species
##### The replicator 
**<span style="color:#00b050">Things necessary for evolution</span>**
- Molecule floating around: When it floats by the right kind of molecule & it attches, continue till full copy, break apart, do it again
- Able to make copies of itself → exponential growth 
- But...
- <span style="color:#00b050">Limited longevity</span> - perfect copies that last forever = no evolution
- <span style="color:#00b050">Finite resources</span> - w/o → no competition 
- <span style="color:#00b050">Copying w/ errors</span> → variety
- Replicator types: if one is more effective it'll out compete others

##### Evolution
- Variation introduced through copying
- Competition among different types of replicators
- Three ways to outcompete others: 
	- Faster reproduction
	- Higher longevity
	- More faithful copying: too many mutants → not reserving your replicator type 
- **Fitness**: most numerous replicators will be ones who are best at reproducing selves

Weapons: replicators can destroy other replicator types

"**Selfish**" replicators in evolution– from pov of evolution, all replicators care about is replicating themselves
- Maximize own type
- Replicators are more about type than individuals 

**Replicators vs. vehicles; genotype vs. phenotype**
- Replicators with more successful vehicles will outcompete replicators with less successful vehicles; vehicles are what are "doing the competing"
- "arms races" – positive feedback → leads to development of complex structures

**"Replicators" conceptually:** 
- Cultural ideas as replicators - religion, ideas, memes
	- Some ideas are better at replicating than others
	- suicide cults??? 

**Single celled organisms: Precambrian - Archean era**
- Cognition?: Yes, has behaviors, responds, but.. ? 
- Is a nervous system necessary for cognition? 

**Multicellular organisms: Precambrian - Proterozoic era**
- Colonies of multiple cells
- Not complex enough to have better cognition than archean

***Ediacaran*: origins of the nervous system**
- "Nerve ref(?)" - organized, distributed across the body

**Nerve nets in Cnidarians**

How is the nervous system advantageous from the POV of a replicator? 

***Cambrian/Ediacaran* origins of bilateria**
- Bilateral → CNS only exists in bilateral animals
- Simple brains!

Most parts of human-like brains already in place by *Permian* 

##### Evolution of Human Cognition
- Tricky to study
- reliance on indirect evidence
	- brain size lol 
	- allometric growth; size of brain to body ratio → can make educated guesses about cognition of species
	- products of brain: **tools** - complexity shows cognition
	- comparisons with close relatives, but parallel evolution, and closest live relatives separated from us 7 Mya

#### Heyes (2012)
##### 2 alt. views of human cogn. evolution:
- Swiss army-knife (traditional)
	- Encapsulated
	- Specialized
	- Evolved for specific purposes
- "New thinking"
	- integrated
	- domain-general
	- more complex evo. history
Which is the same kind of debate as ...
##### Language
**Pinker:** 
- innate langauge module
- separate linguistic operations
- linguistic knowledge unique
- linguistic modules evolved for specific purposes
Highlighting differences from other communication systems - MERGE (lang is result of mutation that allows for recursion and other higher level complexity)

**Tomasello:**
- non-modular, integrated, lang. relying on domain general mechanisms
- evo. in tandem with other abilities
Highlighting continuity (eg. gestural vocal systems in other mammals) - gradual evo. of language

##### Coevolutionary processes crucial to cogn. evo. 
1. Techno-social coevolution
- Loop between tool use and social organization 
- Coevolved:
	More effective tools 
	→ allows incr. social organization (to use the tools), high level specialization, division of tasks 
	→ development of more tools, refinement of existing ones ... 
	→ more effective tools etc. 

2. Gene-culture coevolution
- Non-cogn. example: lactose tolerance / milk production 

**Cultural evolution:**
- study of the evo. of cultural products such as tool use, language, art
- eg. cumulative cultural adaptation


## [[COGS 300 L19 Tool Use and Structure]] ** write out notes from slides
3-21-24
![[COGS300-L19-cognitive_technology.pdf]]
### Pre-class reading
[[clark13-ch8-2.pdf]]
### Lecture
##### Cognitive technology

## [[COGS 300 L20 Cultural evolution]]
3-26-24
![[COGS300-L20-Cultural_evolution.pdf]]
### Pre-class reading
[[henrichandmcelreath03.pdf]]
### Lecture
Burke and Willis
Saw aboriginees eating nardoo but didn't colonialists know how to prepare safely → blocks B1 absorption

#### Cultural evolution
**Individual learning**
- learning without reliance on other individ. 
- trial and error, sci. discovery
**Social learning**
- learning that involves reliance on others
- imitation, explicit instruction
- <span style="color:#ffff00">Product of lots of individ. discoveries</span>
***Lifetime knowledge: both***
- Only individ; very limited 
- Only social, no progress, just same facts over and over 

Both individ and social learning are biologically costly
- big brain (instead of muscles)
- time spent learning/doing R&D (instead of gathering)
- prosociality (sharing food, helping others)
How is social learning adaptive? 

Speed of adaptation: 
- Biological adaptation relies on generational turnover
	- If environmental changes are relatively slow, biological adaptation can keep up 
	- If env. changes are too fast, can't keep up → **cultural adaptation!** (ie. changing clothes to respond to rapid weather changes)
	- If env. change is incredibly rapid, adaptation is impossible

Brain size relative to body size correlates pos. w/ social learning + indiv learning across species
- Increases in brain size relative to body size in diff mammalian lineages over 14 mill years 
- Increases in env variability (ie climate/ice age) over same period 
- but correlation ≠ causation

Now discounted theory: adaptive adv. of social learning
- indiv learning can be very costly (ie discovering what's edible)
- social learning less costly
- in a variable env the fitness advantage conferred by social learning decr as # of indiv learners falls
	- too much social learning = not enough indiv generation
			![[Screenshot 2024-03-26 at 12.13.38 PM.png]]
Social learning becomes less and less useful over time as social knowledge incr., until point at which there aren't enough indiv.; equilibrium point where neither have advantage over other

<span style="color:#ffff00">Social learning can only increase avg fitness of a pop if it allows the accumulation of behaviors that no indiv could acquire in their lifetime</span> 
→ must have mutually reinforcing relationship w indiv learning
				![[Screenshot 2024-03-26 at 12.16.32 PM.png]]
			"evolutionary <span style="color:#00b050">game theory</span>"

## [[COGS 300 L21 Cultural evolution cont.]]
3-28-24
[[COGS300-L20-Cultural_evolution.pdf]]
### Pre-class reading
None
### Lecture

**Why is cultural evo (mostly) unique to humans?** → <span style="color:#00b050">"True" imitation</span>, <span style="color:#0070c0">theory of mind</span>, <span style="color:#ffff00">symbolic communication</span>

##### Imitation
Children predisposed to copy, even if they're copying wrong action -- chimps don't, so they appear to be doing better 
- scenario 1: 
	- modest degree of social learning individuals hang around others who have discovered e.g. a new means to extract food (e.g. cracking nuts); more likely to rediscover the same adaptive behaviour 
- scenario 2: 
	- true imitation individuals learn directly from other individuals, and can build atop their innovations (e.g. devise a more efficient method for cracking nuts)

##### Theory of mind
- Asking children if snoopy knows what's in the box even if he didn't see it. 
- Everybody sees what I see and thinks how I think

*4 y/o develops theory of mind*

##### Symbolic communication 
- certain concepts can only be learned by communication ie. "the vacuum of space will kill you in a matter of minutes" 

*costly cognitive capacities!*

##### Costly information hypothesis
- When maximally accurate info is costly to acquire, evolution favours the extraction of (potentially less accurate) info from other members of group 
- Content vs context biases

**Model based biases**
- Prestige & success bias 
	- Ability to rank indiv in terms of success observed in other species, but not to *selectively learn from indiv.*
	- Challenges: 
		- Teasing apart random variation from true success
		- Determining what makes him successful 
- Conformity biases
	- Majority behavior is typically more efficient

## Robot Tournament!
4-02-24
[[kirbyetal08.pdf]]
## [[COGS 300 L22 Iterated Learning]]
4-04-24
[[COGS300-L22-Iterated_learning.pdf]]
### Pre-class reading
[[kirbyetal08.pdf]]
### Lecture
##### Iterated learning
- Errorful transmission → cultural evolution
- Stereotypically, parent to child 
- Transmission gets more stable in later generations (fewer changes)
	- Features that are harder to transmit get weeded out quickly
	- Features that are easier to transmit = *higher fitness*
- **Transmission error**: the difference between two adjacent generations at a given point in the transmission chain 
	- Transmission error != the overall amount of distortion between the first vs. last generation

##### Kirby et al (2008)
Language is far older than writing, w/ no fossilized remains → create artificial language to see how it evolves

Participants were English speakers
Word corresponds to particular shape with distinct movement pattern

Some words were not shown in training → task becomes impossible
- How do they change language when they can't fully transmit from one gen. to next

<span style="color:#0070c0">Transmission error</span> goes down w gen: <span style="color:#00b050">structure</span> (correlation between meaning & form) goes up
- Participants did not know they were "training" next person (their inputs for results to task would be fed to next)

→ Systematic underspecification: collapsing word distinctions in a systematic way (all spiralling obj. = "poi")

Next experiment; if words were repeated they would be eliminated from training set

→ compositionality: the component parts of a word are descriptive and specific (prefix = color, suffix = movement, middle syllable= shape)

## [[COGS 300 L23 Revision]]
4-09-24
### Pre-class reading
{pdfs-links}?
### Lecture


2-3 paragraphs, no longer than reading responses 
- doesn't have to be original, just coherent
Diagram>??

##### Cognition
embodied/embedded = subcat. of situated

Embedded (env is separate from us)– 
	*offloading*; env is crucial to cog processes but not part of cog sys

Extended: we are not just offloading, env. *is* part of cog sys
##### Neural Networks

## Quizzes
[[COGS 300 Quiz 1 Review]]
[[COGS 300 Quiz 2 Review]]
[[COGS 300 Quiz 3 Review]]
[[COGS 300 Quiz 4 Review]]
