# Maze Solver with Deep Learning

This project implements a maze solver using a combination of classical pathfinding algorithms (Dijkstra) and deep learning techniques. The goal is to create a dataset of maze images, solve them with classical algorithms, and train a Convolutional Neural Network (CNN) to predict the solution paths from unsolved mazes.

## Features

1. **Maze Generation:**

   * Randomly generates unique mazes using recursive backtracking.

2. **Classical Pathfinding:**

   * Solves the generated mazes using Dijkstra's algorithm.

3. **Dataset Generation:**

   * Automatically generates a dataset of unsolved and solved mazes for model training.

4. **Convolutional Neural Network (CNN):**

   * A deep learning model is trained to solve mazes based on the generated dataset.

5. **Model Checkpointing:**

   * The model's state is saved during training for future use.



## License

This project is licensed under Apache 2.0
