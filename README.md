# meta_learned_crossover
peliminary idea


Given the paper from A Modern Self-Referential Weight Matrix That Learns to Modify Itself. The idea that directly comes to mind is can we use this to improve GA's, one of the big problems with GA's is the fact that crossover will not produce healty offspring.

So if we use the trick used in SRWM we can make it so that we learn to not only update the network but also mate/ create offspring succesfully.

The networks that want to mate would need to "communicate" during the mating process to discuss about the multiple updates that build up the offspring.
These updates can then be again through inner product and a sum of general inner products can build any matrix. 
So through this trick agents would successfully build offspring while meta learning to inifinity this building process.


I chose here for genetic algorithms that are multimodal in their approach, unlike the ES algorithm discussed in  "Evolution Strategies as a Scalable Alternative to Reinforcement Learning". This is because if you're able to meta learn how to put information from two different parents together that use different approaches and as such explore probably different parts of the search space you will definitally get better offspring then when 
the difference between agents is a linear pertubation from a mean.
As now the agents can behave totally different from eachother maybe have totally different approaches and still share information so their offspring 
has benifits of possibly both.


