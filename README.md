# Reinforcement Learning

This repository is a comprehensive introduction to Reinforcement Learning, designed to help users understand one of the foundational algorithms in machine learning through practical examples and real-world applications.

**Reinforcement Learning (RL)** is a branch of machine learning where an autonomous **agent** learns to make decisions by performing actions within an **environment** to maximize a cumulative **reward**.

Unlike supervised learning, where a model is given the "correct" answers (labeled data), an RL agent learns through **trial and error**. It receives feedback in the form of rewards (for good moves) or penalties (for mistakes), similar to how a human might learn to play a video game or how a dog is trained with treats.

## Projects Overview

This repository contains 2 different reinforcement learning projects:

#### 1. Deep-Q Learning
- **Data**: Uses `CartPole-v1` environment 
- **Notebook**: `Deep-Q Learning/Deep_Q_Learning.ipynb`
- **Content**: Deep Q-Learning extends classical Q-Learning by using Deep Neural Networks to approximate the Q-function, which predicts the "quality" or expected cumulative reward of taking a particular action in a given state. Traditional Q-Learning uses tables to store Q-values for each state-action pair, which becomes infeasible for environments with large or continuous state spaces.
- **Objective**: This implementation demonstrates DQN on classic control tasks from the Gymnasium library (formerly OpenAI Gym). The agent learns to solve tasks such as CartPole (balancing a pole on a cart) by discovering optimal control policies through reward maximization.
- **Status**: Ready for analysis, note that this code uses Hardware Auto-detection to run on CPU, GPU (NVIDIA) and TPU (Google Collab T4)

#### 2. Snake Game
- **Data**:  Not Applicable
- **Notebook**: `Snake Game/Snake_Game.ipynb`
- **Content**: This project successfully demonstrates the application of Deep Q-Learning (DQN) to train an autonomous agent to play the classic Snake game.
- **Objective**:  By implementing a neural network-based reinforcement learning approach with experience replay and epsilon-greedy exploration, the agent learns to navigate the game environment, avoid collisions, and maximize its score through trial and error.
- **Status**: Ready for analysis


## Getting Started

1. Clone this repository
2. Install required Python packages for linear regression,  note that each Notebook contains cell to install the dependencies, if required:   
3. Choose a project folder and open the corresponding Jupyter notebook or in Google Collab
4. Follow the analysis and experiment with different regression techniques

## Project Structure

```
Reinforcement-Learning/
├── README.md
├── Deep-Q Learning/
│   ├── Deep_Q_Learning.ipynb
├── Snake Game/
│   ├── Snake_Game.ipynb
    └── requirements.txt
```
