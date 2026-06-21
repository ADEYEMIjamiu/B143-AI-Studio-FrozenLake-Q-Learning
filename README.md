# B143 AI Studio – FrozenLake Q-Learning

## Project Overview

This project demonstrates the implementation of a Reinforcement Learning (RL) agent using the Q-Learning algorithm to solve the FrozenLake-v1 environment from the Gymnasium library.

The objective of the agent is to learn the optimal path from the start position to the goal while avoiding holes in the frozen lake.

The project was developed as part of the B143 AI Studio module at GISMA University of Applied Sciences.

---

## Technologies Used

- Python
- Gymnasium
- NumPy
- Matplotlib
- Google Colab

---

## Environment Configuration

```python
env = gym.make(
    "FrozenLake-v1",
    is_slippery=False
)
