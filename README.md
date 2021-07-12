# Continuous Control Project
## Udacity Deep Reinforcement Learning - Nanodegree Program

In this Repo you will find my solution to 2nd Project of Deep Reinforcement Learning, Udacity Nanodegree called "Continuous Control".

I will be training the First Version that consist of a SINGLE agent.

## Project Details

In this environment, a double-jointed arm can move to target locations. 
A reward of +0.1 is provided for each step that the agent's hand is in the goal location. 
Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. 
Each action is a vector with four numbers, corresponding to torque applicable to two joints. 
Every entry in the action vector should be a number between -1 and 1.

### Option 1: Solve the First Version
The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.

## Getting Started

To install and use the environment you have to follow these steps:

 1 Install Anaconda Suite and create (and activate) a new python environment
   ```python
   conda create --name drlnd python=3.6
   ```
 2 Install OpenAi gym
   ```python
   pip install gym
   ```
   
 3 Install the Unity Environment App (not Unity SDK!)
 
   Just copy your required os unity environment file on your working directory and decompress.
   
   * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
   * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
   * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
   * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
 
 4 Clone this repository and install other dependencies:
   ```python
   pip install ./python
   ```
 5 Run [Continuous_Control_ok.ipynb](https://github.com/jbagnato/deep-rl-continuous/blob/main/Continuous_Control_ok.ipynb) (Jupyter Notebook) with the working code and watch how it trains a new model and later use it to play alone.
   
## Instructions

To train a new agent, open [Continuous_Control_ok.ipynb](https://github.com/jbagnato/deep-rl-continuous/blob/main/Continuous_Control_ok.ipynb) Jupyter Notebook file.

Follow the steps described on each cell. 

You will find a DDPG function that will train until ```np.mean(scores_deque)>=30.0```This means that the average score of the agent is greater than 30.

Then it will use saved agent in both files 'checkpoint_actor2.pth' and 'checkpoint_critic2.pth' to run a continuous episode that you can enjoy in realtime :-)
