[[COGS 300]]
3-05-24
[[annotated-COGS300-L14-embodiment.pdf]]
### Pre-class reading
{pdfs-links}
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