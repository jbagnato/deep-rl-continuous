# Project 2 Report: Continuous Control

### Introduction

For this project, you will work with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained RL Agent](https://github.com/jbagnato/deep-rl-continuous/blob/main/p2_navigation.gif)

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

### Learning Algorithm

I used DDPG Algorithm. I take a previous version from "pendulum Excercise" and modified it to make it work on this new environment.



### Plot of Rewards

Rewards plot image:
![Rewards Plot](https://github.com/jbagnato/deep-rl-continuous/blob/main/rewards_plot.png)


#### Ideas for future Work

On future work It would be great to use other RL models like:
