# P2 Continuous Control
![Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/images/reacher.png)

## Project Details
This project uses [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment. In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step so that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

## Getting Started
To get started, it is recommended to follow the Udacity DRL ND dependencies [instructions here](https://github.com/udacity/deep-reinforcement-learning#dependencies) and install the dependencies. This project utilises [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md), [NumPy](http://www.numpy.org/) and [PyTorch](https://pytorch.org/) extensively.  A prebuilt simulator is required in be installed. You need only select the environment that matches your operating system:

### Version 1: One (1) Agent
Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

The file needs to placed in the root directory of the repository and unzipped. Next, before starting the environment utilising the corresponding prebuilt app from Udacity  **Before running the code cell in the notebook**, change the `file_name` parameter to match the location of the Unity environment that you downloaded.

## Instructions
(1) Run the requirements.txt for relevant libraries
(2) Download and set the path for the environment Reacher environment.
(3) Run the `DDPG_Continuous_Control.ipynb` notebook using the drlnd kernel to train the DDPG agent.
(4) Once trained the model weights will be saved in the same directory in the files `actor.pth` and `critic.pth`. The model weights are used by the `Trained Agent.ipynb` notebook against the simulator. 

