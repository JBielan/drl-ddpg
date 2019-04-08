# Deep Deterministic Policy Gradient - Unity Reacher

The objective of [Unity's Reacher](https://www.youtube.com/watch?v=2N9EoF6pQyE&feature=youtu.be) environment is to move the 20 double-jointed arms to reach and maintain a target location for as long as possible.

![alt text](https://github.com/JBielan/drl-ddpg/blob/master/reacher.gif)

## Getting Started

### Dependencies
- Python 3.6 or higher (https://www.anaconda.com/download) or (https://www.python.org/downloads/) 
- Optional but recommended Create (and activate) a new environment with Python 3.6.
    Create (and activate) a new environment with Python 3.6.
    - __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
- Install requirements:
    ```bash
    clone git https://github.com/adaptationio/DDPG-Continuous-Control.git
    cd DDPG-Continuous-Control
	pip install .
	```

- Download the correct Unity Environment for OS and copy into same directory as results.ipynb
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux_NoVis.zip) NO Visual version


## Instructions

- Run:
    ```bash
	jupyter notebook
	```
    Open **ddpg-reacher.ipynb** and run code cells in order
    
## Environment

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

## Built With

* [Pytorch](https://pytorch.org/) - Used to handle Machine Learning part
* [Unity ML](https://unity3d.com/machine-learning) - Reacher environment comes from Unity

## Author

* [**Jakub Bielan**](https://www.linkedin.com/in/jakub-bielan-7334b7137/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
