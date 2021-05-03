OHaire Final Project

-------------------------------------------------------------------------------

Code was modified from two different repositories, OffWorld-Gym and StableBaselines3.

DQN and PPO trials were completed in the Modified_stable-baselines3 repository while
all trials run in DDQN were run in the Modified_offworld-gym environment.
Because of environment compatibility issues, I had to keep the repositories seperate from one another.
For the same reasons, it will be difficult to run all scripts, so I included log files that
validate the results I wrote about in my paper.


***************DDQN Scripts*************************
-Please install all requirements found in requirements.txt follow instructions
for installation provided by OffWorld at this website: https://gym.offworld.ai/docs/installation.html
- Start the Keras Environment as outlined here: https://gym.offworld.ai/docs/examples.html

DDQN Scripts can be found in Modified_offworld_gym/examples/

Run scripts from examples folder using python3.6

IF YOU WOULD LIKE TO SKIP TRAINING STEP, I HAVE INCLUDED THE LOG FILES IN THE
LOGS FOLDER. TO TEST LOG FILES, RUN "tensorboard --logdir=logs" IN HOME DIRECTORY OF
Modified_offworld_gym.

***************DQN and PPO*************************
-Please install all requirements found in requirements.txt follow instructions
for installation provided by: https://stable-baselines3.readthedocs.io/en/master/guide/install.html

Train_DQN and Train_PPO can be run using python3.6

Output charts are included.
