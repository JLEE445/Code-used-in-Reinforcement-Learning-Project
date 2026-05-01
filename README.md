# Code-used-in-Reinforcement-Learning-Project
PLEASE NOTE: This contains the selected code that was used in this project. Another link is provided for all the code, however, this contains major debugging issues https://github.com/JLEE445/Third-Year-Project-RL-for-Path-Planning-and-Task-Assignment.git <- not all of this code was used in the project.

Title of project: Reinforcement Learning for Path Planning and Task Assignment in a Warehouse Environment

Introduction:
There are three main programmes used in this report. The first is a customisable tabular Q-learning algorithm, which was used to test the effects of different hyperparameters, reward structures, and environment sizes on the policy convergence. The second main algorithm is a deep Q-learning algorithm, used to also test different hyperparameters, reward structures and environment sizes, as well as different exploration strategies. The third is a batch simulation of the multi-agent environment, over different task assignment strategies and robot/target configurations.
There is also a fourth program that is not used directly in the project experiments, but develops an animation to simulate the movement of agents in a warehouse in real-time.

Contextual Overview, short explanation:
They are used as a means of conducting individual experiments of separate algorithms; there is no overall connection between programmes. Warehouses.py is used in algorithms to provide warehouse layouts.

Installation instructions:
Requires VSCode and Python version 3.12, as later versions are incompatible with the pygame library.
Libraries that are needed include:
NumPy, for array logic
Pygame, for animations
PyTorch, for neural network implementation
Pandas, for CSV file logic
Matplotlib, for plotting results

How to run software:
In VSCode, load the repository, download a 3.12 version of Python, ensure the above libraries are included, and run.
Please run 2.Customisable_Basic_Q_Learning.py for the tabular Q-learning experiment.
Please run 3.DQN.py for the DQL experiment.
Please run 3.2.DQN_with_epochs.py for epoch experiment.
Please run 7.Final_MA.py for an animation of agents moving.
Please run 9.batch_simulations.py for batch simulations of multi-agent configurations.

Technical Details:
Key technical details are highlighted in the project report, including the structure of the algorithms and equations.

Known Issues for future development:
Animations are slow and of poor quality; this needs to be amended.
In multi-agent simulations, too much information is output in the terminal; this needs to be fixed.
Deep Q-learning is slow - potentially due to unknown bugs; this needs to be looked into.

It should also be noted that Microsoft's extension, called Makefile Tool, was installed in VSCode to help write code faster. It suggested lines of code, and these were carefully read through to ensure they were what the programmer intended. Many of them were incorrect, but occasionally they helped speed up code writing.

Please note that if the code does not run, please consider downloading the full code repository linked at the start and running the same code from there. Due to GitHub problems, I had to keep a manual record of previous code attempts for debugging purposes. The code repository is not as organised as it could be. This is a known issue. Thank you.

