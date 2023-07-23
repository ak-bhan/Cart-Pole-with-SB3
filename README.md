# RL-with-RNN-for-CartPole

**Description**:
This repository showcases Reinforcement Learning (RL) using Recurrent Neural Networks (RNN) for the CartPole environment. The goal is to train an agent to balance the pole on a moving cart using RL algorithms, specifically the Proximal Policy Optimization (PPO) algorithm. Additionally, the repository explores the integration of RNNs into the agent's policy and value networks to capture sequential dependencies in the observations.

**Key Features**:

1. RL Training with PPO: Demonstrates how to train an RL agent using the PPO algorithm provided by Stable Baselines 3.
2. RNN Integration: Illustrates the usage of RNN architectures (GRU and LSTM) in the policy and value networks of the agent.
3. Custom Network Architecture: Includes a custom neural network class designed to support RNNs in the policy and value networks.

**Installation**:
1. Clone the repository to your local machine.
2. Ensure you have the required dependencies installed, such as Python 3.x, Stable Baselines 3, PyTorch, NumPy, and Gym.
3. Optionally, create a conda environment to manage dependencies.

**Usage**:
1. Run the provided code to train the RL agent without RNN integration using the default MlpPolicy.
2. Observe the agent's performance and training progress in TensorBoard.
3. Experiment with different RNN architectures (GRU and LSTM) by training the agent with CustomActorCriticPolicy.
4. Compare the performance of the agent with and without RNN integration.

**Repository Contents**:
- `cartpole_rnn.ipynb`: Jupyter notebook containing step-by-step implementation of RL with RNN for CartPole.
- `custom_network class`: Custom neural network class implementing RNN-based policy and value networks.
- `tensorboard/`: Directory to store TensorBoard logs for visualization.

**Benefits of using RL and RNN**:

1. **Reinforcement Learning (RL)**:
   - RL is well-suited for problems with sequential decision-making, such as games, robotics, and finance.
   - It enables agents to learn from interaction with the environment without explicit supervision.
   - RL agents can handle environments with delayed rewards and sparse feedback, making them versatile for real-world scenarios.

2. **Recurrent Neural Networks (RNN)**:
   - RNNs are designed to capture sequential dependencies in data, making them effective for time-series and sequential tasks.
   - In RL, RNNs can help agents learn from a history of observations, enabling them to make informed decisions based on past experiences.
   - RNNs enable agents to handle partially observable environments, where only past observations are available for decision-making.

**Results**
![Comparison of Training Plots](https://github.com/ak-bhan/Cart-Pole-with-SB3/assets/93557815/38040587-6d32-4e8d-b239-468c584fe818)


**Acknowledgments**:
The code in this repository is built upon Stable Baselines 3 and Gym environments, allowing for an easy and efficient RL experimentation.
