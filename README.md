# Frozen Lake Q-Learning Project

## Overview

This project implements a Q-Learning algorithm to solve the **FrozenLake-v1** environment from the OpenAI Gymnasium. The environment is an 8x8 grid where the agent must navigate from the start to the goal while avoiding holes. The agent learns by interacting with the environment and updating Q-values based on its experiences and the rewards received.

The goal of the project is to train the agent to maximize the cumulative reward, ensuring it can safely reach the goal.

## Project Structure

- `main.py`: The main script containing the Q-learning algorithm, environment setup, and rendering options.
- `frozen_lake8x8.pkl`: Saved Q-values after training, allowing the agent to play the game without re-training.
- `frozen_lake8x8.png`: Visualization of the agent's reward progress over episodes.

## Installation

1. Clone this repository to your local machine.
2. Install the required Python libraries:

```bash
pip install gymnasium numpy matplotlib pickle5
