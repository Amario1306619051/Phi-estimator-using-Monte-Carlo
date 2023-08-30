## Monte Carlo Pi Estimation using Pygame

This repository provides a Python script that demonstrates the estimation of the mathematical constant π (pi) using the Monte Carlo simulation method. The script uses the Pygame library to visualize the simulation process by plotting random points within a quarter circle and determining the ratio of points inside the circle to the total number of points generated.

### How it works

The script performs the following steps:

1. Initializes the Pygame library and sets up the screen dimensions.
2. Defines the colors used for visualization (blue for points inside the circle, red for points outside).
3. Creates a Pygame screen to visualize the simulation.
4. Implements the `estimate_pi` function to estimate π using the Monte Carlo simulation method.
5. Defines the number of points for estimation and calculates the estimated value of π.
6. Initiates the Pygame visualization loop, where points are plotted and colored according to their position relative to the quarter circle.
7. Controls the frame rate of the visualization and automatically exits the loop when all points are plotted.
8. Quits the Pygame library after the simulation is complete.

### Running the Simulation

To run the simulation and estimate the value of π, simply execute the provided Python script. The visualization shows the accumulation of points within the quarter circle, allowing you to observe the estimation process in action.


Feel free to explore and modify the script for educational purposes or to gain insights into the Monte Carlo method and its application in approximating mathematical constants.

**Note:** This repository requires the Pygame library to be installed. You can install it using the following command:
```
pip install pygame
```