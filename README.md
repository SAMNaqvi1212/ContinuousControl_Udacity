# ContinuousControl_Udacity
This repository contains the code and other relevant materials for Udacity Nano-degree on Deep Reinforcement Learning project: "Continuous-Control"

![]( https://github.com/SAMNaqvi1212/ContinuousControl_Udacity/blob/main/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif)      

# Introduction

This Project is a part of Udacity-Nanodegree program on Deep Reinforcement Learning. This project is the second of three projects as part of this nano-degree. This project is based on Reacher Environment. 
In this environment a double-jointed arm is to be moved to target-locations. A reward of +0.1 is provided for each step that the agent's hand is in the target location. The ultimate goal is to make the agent
maintain its position for as many steps as possible. The observation spaces comprises of 33 variables that represents position, rotation, velocity and angular velocity.The action space consists of a vector 
with four numbers corresponding to torque with applicable joints. Every entry in the action vector is between -1 and +1. 

The environment is considered to be closed if the agent gains +100 rewards in 33 consecutive steps. 

The corresponding method that is utilized in this is an Actor-Critic Method which is a deep deterministic gradient policy algorithm.


# Solving the Environment
 1) First option includes an episodic task and in order to solve the environment your agent must score +30 over 100 episodes.

 2) (i) The barrier for solving the seconf version is slightly different. We take into account each and every score by the agent. This yields potentially 20 different scores
    and we then get an average of these 20 scores.
    (ii) This yields an average score for each episode (when the average is overall 20 agents).

  The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.

# Getting Started

1) To set-up the Python environment which is provided in the notebook
   
2) To download the environment, follow the provided links below:
   
   1) [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
   
   2)[OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
   
   3) [Windows32-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
   
   4) [Windows64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

   This is for one-agent.

This is for twenty agents:

1) [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)

2)[OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)

3)[Windows32-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)

4)[Windows64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
   
    



