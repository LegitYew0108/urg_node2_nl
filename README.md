# urg_node2_nl (No Lifecycle) - No Lifecycle management ROS2 driver for Hokuyo URG

# Overview
This package provides a ROS2 driver for the Hokuyo URG series of laser range finders without lifecycle management. It allows for easy integration of the URG sensors into ROS2-based systems.

# Features
- Real-time laser scan data acquisition
- Support for various URG models
- Simple configuration and setup
- No lifecycle management for straightforward operation

# Installation
To install the package, clone the repository into your ROS2 workspace and build it using colcon
```bash
cd ~/ros2_ws/src
git clone --recursive <repository_url>
cd ~/ros2_ws
colcon build --packages-select urg_node2_nl
```