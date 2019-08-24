# dqn_pytorch
The file `model.py` contains a vanilla neural network that maps states to actions and rewards
Agent has been defined in the file `dqn_agent.py`. 
The notebook walks you through the training process. 
The learning algorithm used is vanilla DQN as described in original paper. A deep neural network is used to process the input, which is an image. The deep neural network has following layers:

    Fully connected layer - input: 37 (state size) output: 64
    Fully connected layer - input: 64 output 64
    Fully connected layer - input: 64 output: (action size)

Parameters used in DQN algorithm:

    Maximum steps per episode: 1000
    Starting epsilion: 1.0
    Ending epsilion: 0.01
    Epsilion decay rate: 0.995

## Dependencies
To be able to run this code, you will need an environment with Python 3.6 and 
the dependencies are listed in the `requirements.txt`
```
pip install requirements.txt
``` 

Furthermore, you need to download the environment from one of the links below. You need only to select
the environment that matches your operating system:
- Linux : [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- MAC OSX : [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows : [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

## Running
Run the cells in the notebook `Navigation.ipynb` to train an agent 
