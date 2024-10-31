# Neuroscience of Learning, Memory, and Cognition

This repository contains project work for a course on the neuroscience of learning, memory, and cognition. The project is structured into two main components:
1. **Assignments**: Three assignments focused on neural signal processing and visual perception.
2. **Reinforcement Learning (RL) Project**: An agent learning to navigate a grid world environment to maximize its score.

Repository Link: [GitHub Repository](https://github.com/alrezmlk/neuroscience-of-learning-memory-cognition)

---

## Table of Contents
- [Project Overview](#project-overview)
- [Assignments](#assignments)
  - [Assignment 1 & 2: Neural Signal Processing](#assignment-1--2-neural-signal-processing)
  - [Assignment 3: CNN Layers and Visual Perception](#assignment-3-cnn-layers-and-visual-perception)
- [Reinforcement Learning Project](#reinforcement-learning-project)
- [Installation](#installation)

---

## Project Overview

This course project explores key concepts in neural signal processing, visual perception, and reinforcement learning. It includes:
- Assignments on processing neural signals and analyzing relationships between deep learning model layers and brain responses in the visual pathway.
- An RL-based grid world task in which an agent learns to maximize its score within a turn limit.

Each component is implemented as a Jupyter notebook to support easy experimentation and visualization.

---

## Assignments

### Assignment 1 & 2: Neural Signal Processing
The first two assignments focus on processing neural signals. These assignments cover foundational techniques in analyzing neural data, filtering signals, and extracting meaningful information for understanding brain activity.

### Assignment 3: CNN Layers and Visual Perception
This assignment investigates the relationship between the layers of a convolutional neural network (CNN) and the brain's visual processing pathway. We use a pre-trained AlexNet, fine-tune it for our task, and compare the activations of different layers to EEG data projections across areas in the visual cortex (e.g., V1, V2, V4).

Key steps include:
- **Fine-tuning AlexNet**: Adjusting the model to enhance its feature representations for visual perception tasks.
- **Layer Comparisons**: Comparing CNN layers with projections of EEG data on different visual processing areas, providing insights into model alignment with biological processes.

---

## Reinforcement Learning Project

This project involves training an RL agent in a grid world environment. The agent’s objective is to learn a strategy that maximizes its score by optimally navigating the grid within a limited number of moves.

- **Environment**: A grid-based game where each cell may provide rewards or penalties.
- **Goal**: Maximize the cumulative reward by strategically choosing actions, improving performance over time.

---

## Installation

To run the notebooks, follow these steps:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/alrezmlk/neuroscience-of-learning-memory-cognition.git
   cd neuroscience-of-learning-memory-cognition
