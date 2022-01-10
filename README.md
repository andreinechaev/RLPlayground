# Reinforcment Learning Playground

The repository serves as a sandbox for basic algorithms, their improvements and new ideas

## [DQN Example](DQN.ipynb)

A simple example of DQN implementation using a Neural Net to solve OpenAI gym environments

### Solution

Solution uses Linear Neural Network 128x512xOUTPUT along with Smooth L1 loss and Adam optimizer

![Video](files/balancing.mp4)

## [Policy Gradient Example](PG.ipynb)

A simple example of Policy Gradient without GAE

## [DDPG Example](DDPG.ipynb)

An implementation of DDPG algorithm used for continuous action space. The notebook contains two types of Replay Buffers:

- Equiprobable Replay Buffer - samples drawn randomly
- Prioritized Replay Buffer (PER) - sample drawn based on priority derived from error rate of experiences

Two experiments were run:

### Standard Replay Buffer

![DDPG Replay Buffer Plot](files/rb_ddpg.jpg)

### PER - Prioritized Experience Replay

![DDPG PER Plot](files/per_ddpg.jpg)
