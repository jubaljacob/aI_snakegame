# Snake Game AI

![Snake Game AI](images/snake_ai_demo.gif)

This project aims to teach an AI to play the classic snake game by utilizing reinforcement learning techniques. The objective is to create an agent that can control a snake in the game, learn to navigate the game board, and recognize the rewards associated with eating fruits.

## Overview

The project covers the following key aspects:

- Understanding the basics of Reinforcement Learning and Deep Q Learning.
- Setting up the game environment and implementing the snake game.
- Developing an agent to control the snake's movements in the game.
- Creating and training a neural network to enable the agent to play the game.

## Linear Q-net Module

The Linear Q-net module forms a crucial part of this project. Q-learning is a model-free reinforcement learning algorithm that helps determine the value of an action in a particular state. It does not require a model of the environment and can handle problems with stochastic transitions and rewards without requiring adaptations.

Q-learning finds an optimal policy by maximizing the expected value of the total reward over successive steps, starting from the current state. The "Q" in Q-learning refers to the function that the algorithm computes—the expected rewards for taking an action in each state.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/snake-game-ai.git
```

2. Change into the project directory:

```bash
cd snake-game-ai
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run Using the script:

```bash
python agent.py
```

2. Enjoy watching the AI-controlled snake play the game!


## Acknowledgments

This project was inspired by the fascinating field of reinforcement learning and the classic snake game. Special thanks to the open-source community and researchers who have made significant contributions to the field of AI and reinforcement learning.
## Demo

![](https://github.com/jubaljacob/aI_snakegame/blob/main/snake.gif)

## Screenshots

## Snake game
![image](https://drive.google.com/uc?export=view&id=1iRmQ4nNlYzgGsucH8EOgnOl1Tv9vEZJ0)

## Current game stastitics.
![train](https://github.com/jubaljacob/aI_snakegame/assets/71512643/d181188a-23da-407c-af16-53c65c4a62f2)


