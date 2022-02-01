# Reinforcement-Learning-for-Robot-in-Maze

<p align="center">
<img src="https://github.com/samuelesm/Reinforcement-Learning-for-Robot-in-Maze/blob/main/maze.png">
</p>

This project is divided into three different parts. 

1) The first part is an implementation of Policy Iteration or Value Iteration with the purpose of finding
the optimal policy (of 4 possible actions: move up, down, left, or right) of 112 states
(14 possible positions * 8 possible flag combinations) with the objective to reach
the goal after collecting all 3 flags.

2) We experiment with Q-learning to visualize and to discover the effects
different learning rates and action policies have on convergence of Q values and
the overall rate of convergence.

3) We select the way we want to parameterize our policy and then
reinforce a model. From that, we apply the Q-learning algorithm to the different
models, experimenting with different learning and hyperparameter values. Last,
we plot the comparisons with different parameter values in performing reinforce
and Q-learning for the different environments we explore from gym.openai.

## The following is the resulting Policy
<p align="center">
<img src="https://github.com/samuelesm/Reinforcement-Learning-for-Robot-in-Maze/blob/main/policy.png" width="800">
</p>

## Here is a graph compaing the RSME between optimal Q* and Qt
<p align="center">
<img src="https://github.com/samuelesm/Reinforcement-Learning-for-Robot-in-Maze/blob/main/RSME.png" width="500">
</p>
