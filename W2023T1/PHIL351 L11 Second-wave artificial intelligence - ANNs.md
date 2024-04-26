#philosophy 
#cogs 

[[PHIL 351]]

10-24-23
### Review
#### Classic multilayer ANNs
- relies on "supervised" learning algorithms that use labelled pre classified data to calculate the error signal/cost function
	- "feedback" on how well it's doing
***Successes:*** 
- solves pattern detection problems that would be wildly difficult for a serial processor, given the large number of parameters of variation
- fault tolerance and graceful degradation; good with ambiguous data, identify similarities and differences between different examples in training set
- mesh with prototype theory of concepts
***Worries:***
- technical limitations
- conceptually: supervised learning seems problematic from the perspective of real-world learning–is it learning if the solution is already given? 

### Deep learning and hierarchical multilayer networks
> Biologically inspired by the hierarchical organization of the mammalian brain, where hidden layers closer to the input layer are ‘earlier’ in the processing hierarchy than those closer to the output layer. Different layers thus correspond to different levels of complexity, abstraction, and scale.

**more biologically realistic/evolutionarily sensible -> more computationally powerful**

Fed with raw data, automatically discover representations

**Hierarchy of representations:**
One layer provides inputs to another, which correspond to levels in a representational hierarchy


#### Unsupervised learning 
##### Wake-Sleep algorithm: 
> alternates between perceiving, *recognizing patterns* (awake) and classifying, *generating the training set* (asleep)

Knowledge "bootstrapping"
No innate knowledge of the target mapping

##### Autoencoders:
> reproduce the input state after a process of data-compression – encoding and decoding
> "charades"
> "bottleneck" facilitates the construction of more abstract representations of the stimulus

#### Convolutional networks (ConvNets)
##### Sparse connectivity
- Unlike traditional ANNs, each unit projects forward only to a small number of units further down (functionally akin to a retinotopic field)
##### Shared weights
- Unlike traditional ANNs, multiple units either share the same weight or have weights that are a systematic function of other units (non-isolated learning)
##### Invariance under translation
- Solves the selectivity/invariance problem: e.g. a visual representation of a samoyed must be selective enough to distinguish samoyed from a wolf, but invariant enough to register many different individual samoyeds or perspectives on a samoyed

#### Deep reinforcement learning
> Neither supervised nor unsupervised: reward based
> AlphaGoZero

### Language and propositional thought
- Long seen as the main strength of classical cognitive science. However, machine learning is emerging as a serious rival. Even early ANNs were remarkably resilient in the face of noisy, incomplete linguistic data, produced human-like errors, etc.  
- More recently, ConvNets have been applied to natural language processing (large language models) with considerable success. After all, ConvNets excel at information presented in a grid-like format, and a written sentence is just a 1-D grid!

ANNs lack a language-like structure: LOT theorists argue ANNs cannot explain the most central feature of human thought
Nothing to prevent an ANN from being a "punctate mind"
