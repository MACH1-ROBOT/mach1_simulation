# Mach1_Description ROS Package

## Overview

The `mach1_description` ROS package provides a 3D model and configuration files for the Mach1 robot. It enables visualization and simulation of the Mach1 robot in a ROS environment.

## Package Contents

- `urdf/`: Unified Robot Description Format (URDF) files defining the robot's 3D model.
- `meshes/`: Mesh files (.stl or .dae format) defining detailed geometry of the robot's components.
- `config/`: Configuration files for robot simulation and visualization.
- `launch/`: Launch files for integrating with other ROS nodes and packages.
- `rviz/`: RViz configuration files for visualizing the Mach1 robot.

## Installation

To use Mach1 Navigation, you will need to have `ROS Noetic` installed on your system. You can install ROS by following the instructions on the official ROS website: http://wiki.ros.org/ROS/Installation.

1. Install `ROS Noetic`.
2. Create or use an existing ROS workspace.
3. Clone the `mach1_description` package into the `src/` directory of your workspace.
4. Build the workspace with `catkin_make` or `catkin_build`.
5. Launch the robot model using provided launch files, e.g., `roslaunch mach1_description display.launch`.
6. Customize and extend the package to suit your requirements.

## License

The `mach1_description` package is licensed under the [MIT License](https://mit-license.org/).

## Author

The `mach1_description` package is developed and maintained by [Julian Rendon](https://github.com/jrendon102).
