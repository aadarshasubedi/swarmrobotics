Swarm intelligence (SI) is an artificial-intelligence domain based on the collective behavior of decentralized, self-organized systems.
SI systems are typically made up of a population of simple agents interacting locally with one another and with their environment. These agents follow very simple rules, and although there is no centralized control structure dictating how individual agents should behave, local interactions between such agents lead to the emergence of complex global behavior. Natural examples of SI include ant colonies, bird flocking, animal herding, bacterial growth, and fish schooling.
The application of swarm intelligence principles to robots is called Swarm Robotics. Some of the algorithms based on the above approach include:
1.	Ant Colony Optimization
2.	Particle Swarm Optimization
3.	Stochastic Diffusion Search
Swarm algorithms fall in the category of Distributed Algorithms, since a large number of agents cooperate to achieve a global aim without requiring any central control system.
Distributed algorithms for multi-robot systems rely on network communications to share information. However, the motion of the robots changes the network topology, which affects the information presented to the algorithm. For an algorithm to produce accurate output, robots need to communicate rapidly enough to keep the network topology correlated to their physical configuration. Infrequent communications will cause most multi-robot distributed algorithms to produce less accurate results, and cause some algorithms to stop working altogether.
We wish to analyze some of these algorithms and implement them on a robot swarm. The primary objective is to demonstrate swarm intelligence through a team of robots.
Our work will include the following major components :
1.	Driving mechanism for the robots
2.	Sensors for knowing the position of neighboring robots as well as for collision avoidance
3.	A communication schema for the robots (which may include an IR based approach, or a zigbee approach, or some RF implementation)
We intend to infest  AI (swarm intelligence) into a microcontroller that would act as the central brain of each swarm agent and would coordinate the movement of the robot based on sensor inputs and mutual communication.

Though the actual implementation of swarm robotics is still in its infancy, some of its’ applications include :
•	Aggregation :
Searching for survivors in a collapsed building after an earthquake. Humans are either too big to search inside the debris, or too weak to lift the rubble to effect a rescue. But a multi-robot system comprised of a swarm of tiny life-detecting and rubble-lifting robots could be ideal.
( Demo Video : http://devicedaily.com/robots/swarms-of-ant-sized-robots-to-explore-and-build-homes-on-mars.html @ time 5:36 minutes from start )
•	Dispersion :
Searching a building for an item of interest. A multi-robot system could start from a single location and disperse into the building, searching in all directions simultaneously to locate the object
(  Demo Video :  http://in.youtube.com/watch?v=rYIkgG1nX4E )
•	The U.S. military is investigating swarm techniques for controlling unmanned vehicles and for creating self-assembling robots thereby emulating natural evolution.
•	The European Space Agency is thinking about an orbital swarm for self assembly and interferometry.
•	NASA is investigating the use of swarm technology for planetary mapping.
•	A 1992 paper by M. Anthony Lewis and George A. Bekey discusses the possibility of using swarm intelligence to control nanobots within the body for the purpose of killing carcinogenic tumors.
•	Swarm Intelligence can be used in simulating crowds and studying why and how stampedes occur.
•	Swarm Intelligence can be used in efficient road-network design s.t. bottlenecks and faulty traffic light placements are avoided.
•	The use of Swarm Intelligence in Telecommunication Networks has also been researched, in the form of Ant Based Routing. Basically this uses a probabilistic routing table rewarding/reinforcing the route successfully traversed by each "ant" (a small control packet) which flood the network. Reinforcement of the route in the forwards, reverse direction and both simultaneously have been researched: backwards reinforcement requires a symmetric network and couples the two directions together; forwards reinforcement rewards a route before the outcome is known .