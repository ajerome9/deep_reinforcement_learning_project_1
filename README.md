# Deep Reinforcement Learning Nanodegree - Project 1: Navigation

## Project details
The task here is to develop a Reinforcement Learning Agent that can navigate through UnityML's banana collector environment.

#### The environment
The environment consists of bananas - yellow and blue. Collecting a yellow banana results in a reward of +1, whereas a blue banana results in a reward of -1.

#### State space
The state space is continuous, and is 37 dimensional. The state indicates aspects about where the agent is currently within the environment (eg: sensory input / ray-based perception indicating what objects are around it), and also where the agent is headed to (eg: its velocity).

#### Action space
The agent can take 4 actions to navigate through the environment.

| action | description |
| ------ | ----------- |
| 0 | move forward |
| 1 | move backward |
| 2 | turn left |
| 3 | turn right |

#### Episode
The task is episodic, and the environment is considered solved when the agent gets an average score of 13 over 100 consecutive episodes.

# Getting Started
#### Package dependencies
The project requires library dependencies such as PyTorch, Numpy and these can installed by following the platform-specific instructions at the below link.
https://github.com/udacity/deep-reinforcement-learning#dependencies

#### ML-Agents toolkit
The project uses an environment provided by Unity ML Agents, and this can be installed by 
1. Downloading the below zip file (corresponding to your platform)
  * [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
  * [MacOS](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
  * [Windows 64](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
  * [Windows 32](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
2. Place it in the p1_navigation/ folder in the DRLND GitHub repository, and unzipping it.


# Training the agent
To run the code in this repository,
1. Open the Navigation.ipynb notebook
2. Start the environment by following the first few cells
3. Sections 2,3 explore the environment, and also look at how a random agent would perform
4. Section 4 contains trains an agent that uses a Deep Q Network (DQN) to learn a function that approximates the value function for this environment. This is DQN is based on the LunarLander DQN in the same nanodegree program.

For a description of the DQN, please see Report.pdf
