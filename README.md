# Navigation_RL_Agent
Training an RL agent to solve unity's Banana navigation environment.  

## Project Details:
**Overview:** 
Broad goal is to train an agent to successfully navigate Unity's large square world environment of yellow and blue bananas. 

**Goal & Rewards:** 
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

**State Space:** 
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. 

**Action Space:**
Four discrete actions are available, corresponding to:

- `0` - move forward.
- `1` - move backward.
- `2` - turn left.
- `3` - turn right.

**Solving condition:**
The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started:
The README has instructions for installing dependencies or downloading needed files.

### Setting up the python environment 
 1. Create (and activate) a new environment with Python 3.6.

   - Linux or Mac:
 
      `conda create --name navigation python=3.6`
      `source activate navigation`
      
   - Windows:
   
     `conda create --name navigation python=3.6`  
     
     `activate navigation`
  
 2. Clone the repository, and navigate to the python/ folder. Then, install several dependencies.
     `git clone https://github.com/ramanshrivastava/navigantion_rl.git`
     `pip install torch`
     `pip install numpy` 
     `pip install matplotlib`
     
 3. Create an IPython kernel for the `navigation` environment.
    `python -m ipykernel install --user --name navigation --display-name "navigation"`

 4. Before running code in a notebook, change the kernel to match the `navigation` environment by using the drop-down Kernel menu.

### Download the Unity Environment 
1. Download the environment from one of the links below. You need only select the environment that matches your operating system:

  - Linux: click here
  - Mac OSX: click here
  - Windows (32-bit): click here
  - Windows (64-bit): click here

(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the environment.

2. Place the file in the `navigation_rl` GitHub repository, in the root folder, and unzip (or decompress) the file.


## Instructions:
The README describes how to run the code in the repository, to train the agent. For additional resources on creating READMEs or using Markdown, see here and here.


Dependcies 
  Pytorch
  Unity Environment 
How to Install the dependencies and setup the system 

Once setup is done - how to train and run the Agent to solve the environment 

## TODO: you should describe the environment that you solved, along with how to install the requirements before running the code in your ![repository]()
