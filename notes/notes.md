# Markov decision proccesses


## RL math

- x: feature representation of the state
- w: model parameters
- ŷ = W^T X expected reward
- y = True reward


State sequences: States can be interconnected or not


## Markov decission processes (MDPs)

### MDPs terms

- return: sum of future rewards
- value: expected sum of future rewards given a state
- Bellman equation


### Gaussian likelihood


$$
p(X|\mu, \tau) = \Pi \sqrt{\frac{\tau}{2\pi}}e^{-\frac{\tau}{2}(x_i - \mu)^2}
$$


### Grid world

- episode
- environment
- agent
- actions
- context
- state
- reward
- policy
- action space

### Representing a policy

Can be probabilistic or deterministic

$$
a = \pi(s) \\
\pi(a|s)
$$


## Policy evaluation

Task 1: What is the value of a given policy?
Task 2: What is the best policy?

