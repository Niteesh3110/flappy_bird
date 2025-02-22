# Flappy Bird AI

## Overview

This project is a recreation of the classic Flappy Bird game, enhanced with AI that learns to play the game using a neural network. The AI is trained using reinforcement learning techniques, allowing it to improve its performance over time.

## Features

- Classic Flappy Bird gameplay
- AI-controlled bird that learns through reinforcement learning
- Visualization of AI learning progress
- Interactive manual play mode

## Technologies Used

- Python
- Pygame (for game rendering)
- NEAT (NeuroEvolution of Augmenting Topologies) for AI training
- Matplotlib and Graphviz for visualization

## Installation

### Prerequisites

Ensure you have Python installed on your system. You will also need to install the dependencies listed in `requirements.txt`:

```sh
pip install -r requirements.txt
```

### Clone the Repository

```sh
git clone https://github.com/Niteesh3110/flappy-bird-AI.git
cd flappy-bird-AI
```

## Running the Game

To play the game manually, run:

```sh
python flappy_bird.py
```

To run the AI-controlled bird, execute:

```sh
python AI.py
```

## Files in the Repository

- **flappy_bird.py**: Contains the core game logic, including physics, rendering, and user interactions.
- **AI.py**: Implements the AI using the NEAT algorithm to train and evolve bird agents.
- **visualize.py**: Contains functions for visualizing AI training statistics, species evolution, and neural networks.
- **requirements.txt**: Lists the required dependencies to run the project.

## How the AI Works

1. **Neuroevolution:** The AI uses the NEAT algorithm, which evolves a neural network to optimize its performance over generations.
2. **Fitness Evaluation:** The AI's fitness is determined based on how far it progresses without hitting obstacles.
3. **Evolution Process:** The best-performing neural networks are selected and evolved over multiple iterations.
4. **Visualization:** The training process and neural networks can be visualized using Graphviz and Matplotlib.
