
# Autonomous Drone Navigation System

## Overview

This project implements an autonomous navigation system using robotics, computer vision, and path planning algorithms.

## Features

- **Environment Mapping:** Uses SLAM (Simultaneous Localization and Mapping) techniques for mapping the environment.
- **Object Detection:** Utilizes YOLOv4 model for real-time object detection to avoid obstacles.
- **Path Planning:** Implements A* algorithm for path planning based on mapped environment and detected obstacles.
- **Control System:** Integrates PID (Proportional-Integral-Derivative) controller for steering and speed control.
- **User Interface:** Provides a simple GUI for visualization and control.

## Requirements

- Python 3.x
- OpenCV (version X.X)
- NumPy (version X.X)
- YOLOv4 model weights (`yolov4.weights`) and configuration file (`yolov4.cfg`)
- COCO dataset classes file (`coco.names`)
- Robotics platforms or simulators (e.g., ROS, Gazebo, etc.)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your/repository.git
   cd repository
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download YOLOv4 model files and COCO dataset classes file.

## Usage

1. Configure the environment and robot/platform setup.
2. Run the application:

   ```bash
   python main.py
   ```

3. Follow on-screen instructions or GUI prompts to start the autonomous navigation system.

## Configuration

- Adjust parameters in `config.py` for camera settings, model paths, path planning parameters, and control system parameters.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- YOLOv4 model implementation based on [Darknet](https://github.com/AlexeyAB/darknet).
- Path planning algorithms inspired by [Robot Operating System (ROS)](https://www.ros.org/).


