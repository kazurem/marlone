# Reinforcement Learning
An agent tries in an environment tries to achieve a goal optimally by
learning from it's own experience. This is done by maximizing the 
reward signal.
Agent must learn from it's own experiences. Sensation, Action and Goal

## Different from Supervised
Unlike supervised learning, reinforcement learning does have labeled data
The agent must learn from it's own experience by interacting with the
environment.
## Different from Unsupervised
The goal of unsupervised to find hidden structure in data while reinforcement
learning tries to maximize a reward signal. Uncovering structure in an agent’s experience can certainly be useful in reinforcement learning, but by itself does not address the reinforcement learning agent’s problem of maximizing a reward signal.

## Exploration vs Exploitation
**Exploit:** Take actions that it already knows are good
**Explore:** Take actions that it hasn't taken before
**Thoughts:** Regarding Exploration, maybe there is a way to infer or rank possible good actions
instead of randomly choosing one?

## Elements of Reinforcement Learning
Agent
Environment

### Policy
Learning agent's way of behaving at any given time. It is a mapping from perceived states of the
environment to the actions to be taken when in those states (Stimulus-Response Rules).
It can be a simple lookup table or a complicated search process
Policies maybe stochastic as well

### Reward Signal
A immediate signal which is sent by the environment to the agent.
It defines the goal of the agent. It's goal is to maximize this reward signal.
the signal defines what is good or bad for the agent.
signal depends on current state of environment and agent
The signal is immediate
It is the primary basis of changing the policy
Policy can change depending on what reward signal agent recieves
This tells the agent how good (how near it is to the goal) it is doing by being in a current state

This is analogous to pain/pleasure signals we feel.
### Value Signal
Reward signal defines what is good in the immediate sense
Value signal defines what is good in the long term
Total amount of rewards the agent can expect to accumulate in the future
Reward => Short term immediate desirability
Value => Long term desirability
states can be low reward but high value

Values is what we are most concerned about when making decisions
The single most important component in reinforcment learning are methods
to efficiently and accurately estimate values
they are much harder to calculate since they requires estimation and prediction

### Model
something which mimics the environment. It is what the agent think how the environment behaves
to actions. The better the model, the better it's predictions/estimations. This component is 
necessary for planning. 
Model-Free => Explicitly Trial and Error Agents (Opposite of planning)
Model-Based => Use models rather than pure trial and error

### Limitations and Scope
Evolutionary Algorithms
Policy Gradient Algorithms (Try to change numerical paramters 
in the direction of better policy)
