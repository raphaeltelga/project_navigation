# Project: Navigation



![banana](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif)



## Details

> The "Navigation" project of the Udacity's Deep Reinforcement learning Nanodegree consist of using the Deep Q Network algorithm in order to train an agent to collect specific objects (yellow bananas) spread out in a large square environment, while avoiding some other objects (blues bananas).
>
> The agent is given a reward of +1 for each yellow banana collected and -1 if it makes a mistake getting a blue banana. The goal of the agent is to get as much yellow bananas as possible while avoiding blue bananas
>
> The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Regarding the actions available, the agent is given four possible options : 
>
> - `0` for moving forward.
>
> - `1` for moving backward.
>
> - `2` for turning left.
>
> - `3` for turning right.
>
> In order for the agent to solve the environment, it have to receive an average score greater than 13.00 over 100 consecutive episodes (the number of steps per episode is freely set by the user).



## Getting Started

> 1. Clone the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning) and follow the instructions in `README.md` to set up your Python environment.
>
> 2. Download the Unity Environment from one of the links below, depending on your operating system:
>
> - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
>
> - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
>
> - Windows (32-bits): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
>
> - Windows (64-bits): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
>
> 3. Unzip (or decompress) the file.



## Instructions

​       Open `Navigation.ipynb` to train the agent.
