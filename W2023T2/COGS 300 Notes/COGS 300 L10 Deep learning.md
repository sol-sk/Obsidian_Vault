[[COGS 300]]
2-13-24
[[annotated-COGS300-L10-deep_learning.pdf]]
### Pre-class reading

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
