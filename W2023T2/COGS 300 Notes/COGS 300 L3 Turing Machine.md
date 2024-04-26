[[COGS 300]]
1-16-24
![[COGS300-L2-Turing.pdf]]
### Pre-class reading
![[COGS300-clark13-ch1-1.pdf]]

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