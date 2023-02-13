# Deep-Reinforcement-for-Spacecraft-Guidance
Deep Reinforcement Learning for Robust Spacecraft Rendezvous Guidance


This project was submitted as the part of the course Applied Artificial Intelligence at Carleton University, Canada. This project uses reinforcement learning to train a
deep neural network to act as the guidance strategy for spacecraft proximity operations. Specifically, the neural network takes the state error of the spacecraft as input and outputs velocity commands. An actor-critic training scheme is implemented, similar to the reference paper that first proposed this problem, where the actor network is responsible for mapping state errors to velocity commands, and the critic network is responsible for assessing the value of state-action pairs and outputs the
probability of its reward falling within a specified range. The scenario under consideration is the pose tracking and docking of a chaser spacecraft to a stationary target spacecraft. After several hours of training, the policy network learns to reduce the chaser spacecraft error from the desired positions. The episodic
rewards, losses, and training trajectories of the trained network are compared to those of the reference paper.

Reference paper: https://arc.aiaa.org/doi/full/10.2514/1.A34838

## Note: This repository contains only Program 2 of the project
