# Navigation_RL_Agent
Training an RL agent to solve unity's Banana navigation environment.  

## Project Details:
The README describes the the project environment details (i.e., the state and action spaces, and when the environment is considered solved).
**Overview:** Goal is to train an agent to successfully navigate Unity's large square world environment of yellow and blue bananas. 

**Goal & Rewards:** 
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

**State:** 
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. 

**Action:**
Four discrete actions are available, corresponding to:

- `0` - move forward.
- `1` - move backward.
- `2` - turn left.
- `3` - turn right.

**Solving condition:**
The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started:
The README has instructions for installing dependencies or downloading needed files.


## Instructions:
The README describes how to run the code in the repository, to train the agent. For additional resources on creating READMEs or using Markdown, see here and here.


Dependcies 
  Pytorch
  Unity Environment 
How to Install the dependencies and setup the system 

Once setup is done - how to train and run the Agent to solve the environment 

## TODO: you should describe the environment that you solved, along with how to install the requirements before running the code in your ![repository]()
