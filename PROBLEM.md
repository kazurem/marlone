# Multi-Agent Reinforcement Learning for Agent Swarm Optimization
## What is Multi-Agent Reinforcement Learning
Study of behavior of multiple learning agents that coexist in a shared environment. Each agent is motivated by its own rewards, and does actions to advance its own interests; in some environments these interests are opposed to the interests of other agents
Can be modeled by a Markov Decision Process

## PEAS
### Performance Measure
- How close to the target the agents reached (Distance from center of mass of swarm?)
- Battery Usage
- Area Coverage
- Time Taken
- ...?
### Environment
2D environment containing:
- Wind
- Walls or Buildings (Obstacles)
- Other agents
- Recharging stations?
### Actuators
- Able to move in any 2D direction (Vector(x, y) where x, y member of Real Numbers)
Each push different from the current moving direction will require more battery usage than
a push in the same direction
### Sensors
Able to sense objects within a circle of a certain radius $r$

## TODO:
1. Make the environment (either using some library or pygame. Research what to use)
2. Learn theory for reinforcement learning and get exposure to MARL
3. Make Github Repository documenting everything (In discussions)

## Resources:
1. [Wikipedia: Multi-Agent reinforcement learning](https://en.wikipedia.org/wiki/Multi-agent_reinforcement_learning)
2. Reinforcement Learning: An Introduction By Richard S. Sutton and Andrew G. Barto
3. [Wikipedia: Markov Decision Process](https://en.wikipedia.org/wiki/Markov_decision_process)
4. [Library for MARL: PettingZoo](https://pettingzoo.farama.org/)
5. [arXiv: Multi-agent Reinforcement Learning: A Comprehensive Survey](https://arxiv.org/pdf/2312.10256)
6. [Wikipedia: Game Theory](https://en.wikipedia.org/wiki/Game_theory)
7. [arXiv: Deep Reinforcement Learning for Swarm Systems](https://arxiv.org/pdf/1807.06613)
8. [Github: MARL Papers](https://github.com/LantaoYu/MARL-Papers)



