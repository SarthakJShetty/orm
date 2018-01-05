# Operations-Research
## Building a program for visualization of Critical Path in Critical Path Method which is an integral tool in Operations Research.

### Introduction
This project is in the process of being developed for the effective visualization of Critical Path, Best Starting time and Lagging time.

#### This code has not fully developed. Some portions of it are still incomplete.

#### Terminologies
1. Nodes: Symbolize the start or end (sometimes both), of events. A node can be the starting (or terminating) point of one or more events.
2. Event: The sequence of events in between two nodes.

##### Note: The theory surrounding Critical Path Method is analogous to the concepts that form the foundation of Graph Theory.

- Depth First Search soon to be integrated, to determine the Critical Path of the given network.

### Functioning
- Initially the program requests for the number of nodes involved in the network.
- Building upon the network of nodes, the relations between the different nodes are assigned (Check the Build Log for a list of assignments that are currently possible.)
- Following up on the previous relations, the program then assigns the absolute times of the events in between the different nodes.

### Build Log:

#### 12/30/2017
- Build has not (yet) been configured to handle multiple events leading to a single node.

#### 12/31/2017 (Happy New Year!)
- Incorporated the last node concept.
- Can now calculate Critical Path in the forward direction.
- Need to obtain the Critical Path in the reverse direction to confirm the Critical Path.
- Working on theory to obtain the Reverse Start Times.