# Mach1 Simulation ROS Package

## Overview

The `mach1_simulation` ROS package provides a comprehensive simulation environment for the Mach1 robot. It includes a 3D model of the robot and configuration files that allow for visualization and simulation within the ROS (Robot Operating System) framework.

## Package Contents

- `urdf/`: Unified Robot Description Format (URDF) files defining the robot's 3D model.
- `meshes/`: Mesh files (.stl or .dae format) defining detailed geometry of the robot's components.
- `config/`: Configuration files for robot simulation and visualization.
- `launch/`: Launch files for integrating with other ROS nodes and packages.
- `rviz/`: RViz configuration files for visualizing the Mach1 robot.

## Installation

To use the Mach1 Simulation package, you will need to have ROS Noetic installed on your system. If you haven't installed ROS Noetic yet, you can follow the installation instructions on the official ROS website: http://wiki.ros.org/ROS/Installation.

1. Install ROS Noetic.
2. Create a new ROS workspace or use an existing one.
3. Clone the `mach1_simulation` package into the `src/` directory of your workspace.
4. Build the workspace using either `catkin_make` or `catkin_build` command.
5. Launch the robot model using the provided launch files. For example, you can use the following command: `roslaunch mach1_simulation display.launch`.
6. Customize and extend the package as per your requirements to further enhance the Mach1 simulation.

## License

The `mach1_simulation` package is licensed under the [MIT License](https://mit-license.org/).

## Author

The `mach1_simulation` package is developed and maintained by [Julian Rendon](https://github.com/jrendon102).
