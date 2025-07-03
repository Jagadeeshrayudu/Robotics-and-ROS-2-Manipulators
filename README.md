# Robotic Manipulator Project

This repository contains code and resources for building and controlling a robotic manipulator using ROS 2. You can use it with a simulated robot or deploy it on a real robotic arm.

## Features

- Simulation in Gazebo
- Robot kinematics and motion planning
- Integration with ROS 2
- Optional control with Arduino

## Getting Started

Follow these steps to set up your development environment and get the robot running.

### Prerequisites

- Ubuntu 22.04
- [ROS 2 Humble](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)
- Gazebo simulator
- Colcon build tool

Optional for real robot:
- Arduino IDE
- VS Code

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/JagadeeshRayudu/Robotics-and-ROS-2-Manipulators.git
    cd your-repo
    ```

2. Build the ROS 2 workspace:
    ```bash
    colcon build
    ```

3. Source the workspace:
    ```bash
    . install/setup.bash
    ```

### Running the Robot

#### Simulated Robot

To launch the simulated robot in Gazebo:
```bash
ros2 launch your_package simulated_robot.launch.py
