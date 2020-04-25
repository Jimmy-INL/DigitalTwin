# DigitalTwin

## Introduction
Digital twin refers to a digital replica of potential and actual physical assets, processes, people, places, systems and devices that can be used for various purposes. The digital representation provides both the elements and the dynamics of how an Internet of Things device operates and lives throughout its life cycle. Definitions of digital twin technology used in prior research emphasize two important characteristics. Firstly, each definition emphasizes the connection between the physical model
and the corresponding virtual model or virtual counterpart. Secondly, this connection is established by generating real time data. The concept of the digital twin can be compared to other concepts such as cross-reality environments or co-spaces and mirror models, which aim to, by and large, synchronize part of the physical world (e.g., an object or place) with its cyber representation (which can be an abstraction of some aspects of the physical world).

## Digital Hotspot Twin
Imagine certain hot spots in a city, such a football game where network surge is expected due to large crowds. How can the network be optimized so that the users does not experience any degradation in throughput or increase in latency. Creating a twin with combination of historical data and simulated data where different configurations of network can be tested to find the right configuration for various hot spot scenarios.

## Current Work
We have a simulator in place which can generate simulated data given any geographical region and initial set of parameters of the network. We can use it as a testbed to train models in the simulator which can then give us the most optimal set of configuration for the entire network that can optimize the network by minimising the latency and maximizing the throughput.

## Assumptions/Constraints
Currently, the simulator is assumed to be fair approximation of the real world and hence we can train our model with fair amount of certainty. However, the simulated data that is generated using the simulator takes a large amount of time to be created and hence we are further simplifying the problem by narrowing down to only one physical location for training our model and then later generalize it any given location. We are also further planning to enhance the current simulator by building a generative model on top of it which can then create simulated data on the fly for any given physical location or given network configuration.






