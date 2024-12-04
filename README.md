# CAS-Project
# Mobile Robot Kinematic Model Simulation

## Overview:
This project simulates the motion of a mobile robot using a differential-drive kinematic model. The robot's movement is computed based on its velocities, and the trajectory is visualized in 2D. The simulation demonstrates how the robot's position (`x`, `y`) and orientation (`theta`) evolve over time in response to control inputs, with the simulation results plotted to show the robot's motion.

The kinematic model used in this project is simple yet powerful, allowing the user to experiment with different initial conditions and control inputs. This simulation is intended for understanding the basic principles of kinematic motion and for exploring how a mobile robot moves in a controlled environment.

## Files Included:
1. **mobile_robot_kinematic_model.m** - MATLAB script that implements the kinematic model of the mobile robot and runs the simulation. This file contains the code for initializing the robot's state, computing its trajectory over time, and generating plots.
2. **README.md** - Documentation file you are currently reading, explaining the details of the project and how to use the simulation code.

## Requirements:
- MATLAB (R2018b or later)
- No additional toolboxes required. The code uses basic MATLAB functions.

## Running the Simulation:
1. Download the `mobile_robot_kinematic_model.m` file.
2. Open MATLAB and navigate to the folder where the file is saved.
3. Run the script by typing the following command in the MATLAB Command Window:
   ```matlab
   mobile_robot_kinematic_model
