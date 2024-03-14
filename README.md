# final_year_project
## Reinforcement Learning
### Library Dependencies present in requirements.txt. 

 `train.py`: Use for training your Reinforcement Learning agent. \
 `eval.py`: For simulating your trained RL agent.  \
  `envs`: folder contains the environment with obstacles. 

### Steps to run the code
1. Make a python environment using `python -m venv /path/to/new/virtual/environment` and activate the environment. 
2. Install `requirements.txt` from this repository. Note: If you get an OS error for Windows Long Path, ignore it. The code will work. 
3. Install the dependencies using `pip install -r requirements.txt`
4. Download the submitted code.
5. Go to the `Reinforcement Learning` folder.
6. To train the model, run `python train.py`. Note: while training, you may get warnings regarding no inertial data for link. This warning can be ignored. 
7. To simulate the model, run `python eval.py`.
8. To generate graphs from the simulation, run `python graph.py`.
9. All the environments are present in the `envs` folder. 

## PID Control
Implemented in Matlab. 

## Hardware
Implemented the Agilicious hardware from scratch, doing the mechanical, electronic and software assembly. \
Due to safety considerations such as limited space and lack of safety hardware, we could not test the RL on Agilcious used for the racing drone. 
Instead, the RL was deployed on CrazyFlie, a much lighter, safer, but less robust drone platform. 

