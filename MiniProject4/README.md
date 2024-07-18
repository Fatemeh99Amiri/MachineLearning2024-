## Introduction to Reinforcement Learning and Its Algorithms

This mini-project is part of the Machine Learning 2024 course by Dr. Mehdi Aliyari at Khajeh Nasir Toosi University of Technology (KNTU). The project explores and implements two fundamental reinforcement learning algorithms: Q-learning and Deep Q-Networks (DQN). The objective is to solve the Wumpus World problem and apply Deep Q-Learning to the Lunar Lander environment, demonstrating the practical applications of these algorithms.

## Solving the Wumpus World

The Wumpus World is a grid-based environment where an agent must navigate to find gold while avoiding deadly pits and a dangerous Wumpus. This classic AI challenge provides a rich context for testing reinforcement learning algorithms due to its combination of rewards and risks. The objectives for the agent include navigating the grid, avoiding hazards, collecting gold, and killing the Wumpus. We implemented Q-learning, a model-free reinforcement learning algorithm that uses a Q-table to store and update the value of state-action pairs, and Deep Q-Networks (DQN), which extends Q-learning by using neural networks to approximate Q-values, handling larger state spaces with experience replay and a target network for stabilized training.

### Performance Evaluation and Key Findings in Wumpus World

Performance was evaluated using metrics such as total rewards, cumulative rewards, and mean rewards per episode. Key findings include visualizing the agent's policy performance through learning curves, the impact of different epsilon values (exploration rate) on the learning process, and a comparison of Q-learning and DQN in terms of speed and efficiency in learning the optimal policy.

## Deep Q-Learning for Lunar Lander

In this section, we design and train an agent using Deep Q-Learning to solve the Lunar Lander environment. The Lunar Lander is a simulated environment where an agent must safely land a spacecraft on a lunar surface. The objectives include designing an agent that uses Deep Q-Learning to learn the optimal policy for landing and training the agent with various hyperparameters to evaluate performance. The environment provides a continuous state space describing the lander's position, velocity, angle, and angular velocity, and an action space where the agent can take actions such as firing the main engine or the side engines, with rewards based on the lander's proximity to the landing pad and penalties for crashing.

### Performance Evaluation and Key Findings in Lunar Lander

We evaluated performance using different batch sizes (32, 64, 128) and episodes (50, 100, 150, 200, 250), and analyzed learning curves to understand the agent's learning process. The project compared the performance of DQN and DDQN (Double DQN) models. Key findings include determining the best-performing model and hyperparameters based on reward convergence, and conducting a regret analysis to understand the agent's decision-making over time. This comprehensive analysis demonstrated the effectiveness of reinforcement learning algorithms in complex environments.
