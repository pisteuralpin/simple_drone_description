# Simple Drone - Description package
[![ROS2](https://img.shields.io/badge/ROS2-Jazzy-green)](https://docs.ros.org/en/jazzy/index.html)
[![Gazebo](https://img.shields.io/badge/Gazebo-Harmonic-orange)](http://gazebosim.org/)
[![License](https://img.shields.io/badge/License-GNU--3..0-blue)](#license)

Simple Drone are ROS2 packages designed for simulating drones in a Gazebo environment. This package provides models and physics properties for drones.

Models from [Gazebo Fuel](https://app.gazebosim.org/OpenRobotics/fuel/models/X3%20UAV).

## Associated packages
- [simple_drone_description](https://github.com/pisteuralpin/simple_drone_description) (this package)
- [simple_drone_gazebo](https://github.com/pisteuralpin/simple_drone_gazebo)

## Features
- [x] Drone models with realistic physics properties.

## Tested configuration
- ROS2 Jazzy
- Gazebo Harmonic

# Usage
- Visualize the drone model in RViz2:
  ```bash
  ros2 launch simple_drone_description display.launch.py
  ```