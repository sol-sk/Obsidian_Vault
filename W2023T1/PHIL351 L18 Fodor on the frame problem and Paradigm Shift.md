#philosophy 

[[PHIL 351]]

11-21-23
[[PHIL351 (T1 2023) - Lecture 14 (relevance and frame problem).pdf]]
[Lecture video](https://ubc.ca.panopto.com/Panopto/Pages/Viewer.aspx?id=a5e3faf5-ad74-487f-b0cb-b06701013b57)

### Pre class readings
![[Dietrich-Ch-7.mht]]
### Lecture
[[PHIL351 L17 Robot parable cont. and Historical background to frame problem#Historical background the role of abduction in scientific reasoning]]
##### Fodor
- While modules are plausibly computational, *central systems are not* - Narrow vs general AI 

**Two entertwined properties of central cognitive states which resist computational explanation**
1. Being '**Quinean**': epistemic/rational properties of an attitude that are relative to a larger set of attitudes: 
	1. Coherence, simplicity, plausibility (all relative to whole belief system) → Generates the 'globality problem': computational operations are sensitive ot a mental state's local (syntactic) properties, but not to its global/Quinean properties
2. Being **Isotropic**: any member of an attitude set is potentially relevant to any other
	1. Analogical reasoning (metaphor/simile)
	2. Isotropism underlies 'the relevance problem': computational operations are insensitive to relevance

**Fodor gives us two morals from this:**
1. The closer we get to higher levels of cognitive capacity, the more global properties like isotropy show up → global properties are necessary for paradigmatic intelligence
**"Fodor's first law of the nonexistence of cognitive science":**
2. The more global (isotropic) a cognitive process is, (e.g. analogical reasoning,) the less anybody understands it.
#### A change of paradigm? 
##### Paradigm shift #1: ANNs
- May seem more promising architecture than classical GOFAI for addressing *frame problem*
	- Greater ease dealing w context and global properties of stim.i
	- Memory is an evolving state of the network implicitly in the connection weights
- However, insufficient to solve the frame problem, esp. relevance problem
- ANNs tend to assimilate novel cases to pre-existing categories: "overfitting" (see: adversarial examples)
	- Product of their reliance on statistics 

##### Plea for Socratic ignorance? 
![[Screen Shot 2023-11-27 at 3.33.44 PM.png]]
man.. what
- Witness the role of ignorance in abductive reasoning: 
	- System must see target domain as something about which it is ignorant but which it might better understand through creatively repurposing its existing concepts
	- To reason causally, the system must see an effect as a particular with an idiosyncratic history about which it is, and will remain, ignorant but which it can better understand by entertaining plausible hypothetical scenarios that are consistent with one's model of the world and that can isolate causally relevant variables of a situation

##### Paradigm shift #2: 4E cognitive science
> **4E: embodied, embedded, extended, and enactive** 

4E cog scientists: **temporal dynamics** are one of most important properties of cognition
→ "off-loading" cognitive labor to agent's *body* and environment
- More radical 4E (enactivism, ecological psych): reject the idea that cognition can be understood as computation bc this misinterps the temporal structure of cognition
##### Situated robotics
Rodney Brooks' 'subsumption architecture': provides alternative to iterated sequences like SHAKEY
- Brooks' robots: sensors are directly wired to various activity layers (e.g. wander, avoid, explore) which would compete via mutual inhibition
- When an activity layer wins out, the sensors directly and continuously drive behavior proprietary to that layer, no mediating model/plan

Result: smoother in cluttered env., flexible in goal directed ways

Brooks claimed his robots did not have any use for representations

##### Thinking through coupling
Mind/cognititon spans the gap between agent and environment

> It is only for convenience (and from habit) that we think of the organism and environment as separate; in fact, they are best thought of as comprising just one system” 
> Chemero 2001, p.142


> “The emergence of mind takes place in the medium of patterns of activation across neuronal cell assemblies in conjunction with the interaction of their attached sensors (eyes, ears, etc.) and effectors (hands, speech apparatus, etc.) with the environment in which they are embedded. Make no mistake about it, *that* is the stuff of which human minds are made: brains, bodies, and environments.” 
> Spivey 2007, 33, emphasis original

##### Dynamical systems theory
A branch of mathematics used to model a system whose behavior changes continuously over time, including patterns of stability, instability, and meta-stability.
An alternative set of formal tools for desc the activity of ANNs and autonomous robots
Applications to human + animal cognition: 
- outfielder problem;
- the diving gannet, whose behavior can be described mathematically with tau
- modelling cognitive development in infancy
##### Enactive and ecological cognitive science (radical 4E)
- Both meaning and relevance are 'enacted' through active self-maintenance (autopoiesis)
- Ecological psychologists: the info organisms pay attention to is 'ecological information', which is relative to its morphology
- **Common theme**: properties like meaning and relevance do not belong to internal states of an agent (e.g. representations of mind-independent objects and properties) but to an organism's *milieu*: agent and environment are *complementary aspects of an integrated system*
- If so, cognitive agents do not need to solve the frame problem since, in virtue of being alive, they already inhabit a world of salience and significance
	- Elements of the env stand out as 'affordances' with an hinherent bio significance to the organism
##### Critiques of enactive and ecological approaches
(a new kind of) Frame problem:
- **How does the organism become attuned to only the relevant affordances?**
- Is biological agency sufficient for cognitive agency?
	- Intelligence: when something that matters to an organism is not causally coupled to it 
	- Agents engage w world as objective, not just an arena for action (?)

