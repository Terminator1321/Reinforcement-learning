An AI agent that learns to play the classic Snake game using Deep Q-Learning (DQN).
The environment is built with Pygame, and the neural network is implemented from scratch using PyTorch. The agent improves its gameplay over time by interacting with the environment, receiving rewards, and learning from past experiences.

This project demonstrates how Reinforcement Learning can be applied to a game environment.
The agent observes the current game state (danger zones, movement direction, and food location) and decides the best possible action using a Deep Q-Network. Training is done using experience replay and an ε-greedy exploration strategy.

🗂️ Project Structure
.
├── Agent.py            # Agent logic, state handling, training loop
├── Model.py            # Deep Q-Network and trainer
├── GameEnviroment.py   # Snake game environment (Pygame)
├── helper.py           # Training score visualization
├── model/
│   └── best_model.pth  # Saved best model weights
└── main.py             # Entry point (training loop)

