# Project 2 Report: Continuous Control

### Introduction

For this project, you will work with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained RL Agent](https://github.com/jbagnato/deep-rl-continuous/blob/main/p2_navigation.gif)

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

### Learning Algorithm

I used DDPG Algorithm to solve the practice excercise. 
I took a previous code from "pendulum Excercise" directory and modified it to make it work on this new environment.



### Plot of Rewards

```xml
Episode 100	Average Score: 0.78
Episode 200	Average Score: 2.19
Episode 300	Average Score: 7.01
Episode 400	Average Score: 16.94
Episode 500	Average Score: 24.64
Episode 563	Average Score: 30.06
Environment solved in 563 episodes!	Average Score: 30.06
```

Rewards plot image:

![Rewards Plot](https://github.com/jbagnato/deep-rl-continuous/blob/main/rewards_plot.png)


#### Ideas for future Work

On future work It would be great to use other RL models like:
