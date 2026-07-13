# marlone
Training a Drone Swarm for various purposes such as:
1. Searching for a target
2. Tracking a target
3. Acting as a communication relay  

## Current Scope
For now, only the searching part will be implemented. This will be done using Multi-Agent Reinforcement Learning.
The Drone Swarm will also be only 2D for now but I plan on extending this project for 3D as well.

## Notebooks
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kazurem/marlone/blob/environment/BasicVMASEnv.ipynb) **Basic Custom Scenario in VMAS**. Here is a notebook which implements a custom scenario using [VMAS's](https://github.com/proroklab/vectorizedmultiagentsimulator) `BaseScenario` class. It includes multiple agents (in blue) and obstacles (in red). There is also a 2D vector field which is supposed to represent wind. The actions the agents take are random for now.
![WindNavScenario](assets/WindNavScenario.gif)
  
## What is Multi-Agent Reinforcement Learning
From [Wikipedia: Multi-Agent reinforcement learning](https://en.wikipedia.org/wiki/Multi-agent_reinforcement_learning):
> Study of behavior of multiple learning agents that coexist in a shared environment.
Each agent is motivated by its own rewards, and does actions to advance its own interests; 
in some environments these interests are opposed to the interests of other agents
Can be modeled by a Markov Decision Process

# Resources
Please see the [Github Wiki Page](https://github.com/kazurem/marlone/wiki/Resources)
