# deep_learning3
It contains code,report,optimal weights

# Project Details

Environment:
multi agent version environment


Observation space
The eight racquets are heightened by variables such as position and velocity.

Action space
Two consecutive actions.

Reward
When the agent hits the ball: +0.1
When the agent hits the ball out of range, etc.: -0.01

Environment completion conditions
The problem is solved when the score average is 0.5 or higher for 100+ episodes.

# introduction
All my work was done on a GPU environment given by Udacity. 

1.Install enviroment
To set up your python environment to run the code in this repository, follow the instructions below.

  1. Createa new environment in python.

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

  2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
    - Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
    - Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).

  3. Clone the repository, and install several dependencies.
  ```bash
  git clone https://github.com/udacity/deep-reinforcement-learning.git
  cd deep-reinforcement-learning/python
  pip install .
  ```

  4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
  ```bash
  python -m ipykernel install --user --name drlnd --display-name "drlnd"
  ```

2.Download Unity enviroment
  visit below web site and download.
  for Linux：[here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)

  for Mac OSX：[here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)

  for Windows10 x32:[here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)

  for Windows10 x64:[here](https://s3-us-west-1.amazonaws.com/udacitydrlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

# instruction

1.Open the jupyter notebook Tennis_prohect.ipynb and Select the "Kernel" section in the top menu and change the kernel to "drland" which is the environment you just created.

2. Click the Run button on the cell where the code is written.

3.You will see the result.
