# T.A.R.G.E.T. (Tracking And Remote Guided Engagement Tank)
T.A.R.G.E.T. is a remote-controlled tank with autonomous targeting. It uses an ESP32 for face detection and camera control, servos for aiming, and an Arduino with an L293D motor controller and Bluetooth module for movement. Built on a metal chassis, it combines computer vision and robotics for dynamic interactions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Software Components](#software-components)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
T.A.R.G.E.T. is an auto-aiming remote-controlled tank designed to track and engage targets using computer vision and AI technologies. This project leverages the AI Thinker ESP32 CAM, servos for pan and tilt control, and an Arduino with an L293D motor controller for movement. The entire system is built on a robust metal chassis and can be controlled via Bluetooth.

## Features
- Automatic target detection and tracking
- Remote control via Bluetooth
- Real-time video streaming
- Pan and tilt control for the camera
- Durable metal chassis

## Hardware Components
- AI Thinker ESP32 CAM
- Servos for pan and tilt
- Arduino Uno
- L293D motor controller
- Bluetooth module
- Metal chassis
- Motors and wheels

## Software Components
- Arduino IDE
- OpenCV
- YOLOv5
- Python

## Setup and Installation

### Hardware Setup
1. Assemble the metal chassis and attach the motors and wheels.
2. Connect the servos to the pan and tilt mechanism and attach the camera module.
3. Wire the AI Thinker ESP32 CAM, Arduino, L293D motor controller, and Bluetooth module according to the provided schematic.

### Software Installation
1. Install the Arduino IDE from [Arduino's official website](https://www.arduino.cc/en/software).
2. Install the required Python libraries:
    ```sh
    pip install opencv-python
    pip install yolov5
    ```
3. Flash the Arduino code onto the Arduino Uno.

### Detailed Instructions
For detailed setup and installation instructions, refer to the `docs/setup.md` file.

## Usage
1. Power on the tank and connect to it via Bluetooth using your preferred remote control application.
2. Start the video stream and computer vision processing.
3. Use the remote control to navigate the tank and engage targets.

## Contributing
We welcome contributions! Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgements
- [YOLOv5](https://github.com/ultralytics/yolov5)
- [OpenCV](https://opencv.org/)
- [Arduino](https://www.arduino.cc/)

Thank you for your contributions!
