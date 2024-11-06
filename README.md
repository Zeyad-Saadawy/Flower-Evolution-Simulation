# Flower Evolution Simulation

This project simulates the evolution of a population of flowers using a genetic algorithm, implemented in Python with a graphical user interface created with Tkinter.

## Overview

The purpose of this project is to visualize evolutionary principles, such as selection, crossover, and mutation, by simulating flower evolution. Each flower has a set of genes that define its characteristics, and over generations, flowers evolve to display traits that align with higher fitness as determined by user interactions.

## Features

- **Genetic Representation**: Each flower has a DNA sequence with genes representing:
  - Size of the flower's center
  - Color of the center (RGB)
  - Color of the petals (RGB)
  - Number of petals

- **Genetic Algorithm Components**:
  - **Selection**: Chooses flowers for reproduction based on their fitness.
  - **Crossover**: Combines genetic information from two parent flowers to create a new flower.
  - **Mutation**: Introduces genetic diversity by randomly altering some genes.

- **User Interaction for Fitness**: The user "hovers" over flowers to assign fitness scores. The longer a flower is hovered over, the higher its fitness score, influencing which flowers contribute their genes to the next generation.

- **Evolution Over Generations**: The flower population evolves over successive generations, resulting in flowers that progressively exhibit characteristics associated with higher fitness.

## Getting Started

### Prerequisites

- Python 3.x
- Tkinter (usually included with Python installations)

### Instructions

1. Hover over flowers in the GUI to increase their fitness.
2. Click "Evolve" to proceed to the next generation.
3. Observe how the flower characteristics evolve over time.

## File Structure

- **flower_evolution.py**: Main script for running the simulation.
- **flower.py**: Defines the `Flower` class, including genetic properties and methods for selection, crossover, and mutation.
- **population.py**: Manages the population of flowers, including initialization and evolution functions.
- **gui.py**: Handles the Tkinter GUI for displaying flowers and capturing user interactions.

## Future Improvements

- Add more complex fitness functions.
- Allow users to adjust mutation and crossover rates.
- Introduce more visual customization options for flower characteristics.

## License

This project is licensed under the MIT License.
