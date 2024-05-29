# Caladrius

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Introduction

Caladrius is a cutting-edge fall detection system designed to act as a guardian for individuals under health supervision, such as those in elderly care homes or hospital wards. By leveraging the power of YOLOv8 for real-time people detection and advanced mathematical calculations for fall detection, Caladrius ensures prompt alerts in the event of a fall, potentially saving lives and improving response times.

## Features

- **Real-time People Detection**: Utilizes the YOLOv8 model for accurate and efficient detection of people in the video stream.
- **Fall Detection Algorithm**: Employs a robust mathematical model to determine if a fall has occurred based on the positions and movements of detected people.
- **Alarm System**: Immediately raises an alarm when a fall is detected, alerting caregivers and medical staff.
- **Video Stream Input**: Processes live video feeds from CCTV cameras using the OpenCV (cv2) library.
- **Scalable and Configurable**: Easily adaptable to different environments and customizable to meet specific needs.

## System Architecture

1. **Video Input**: Captures video streams from CCTV cameras using the OpenCV (cv2) library.
2. **People Detection**: Uses the YOLOv8 model to identify and track individuals in the video feed.
3. **Fall Detection**: Analyzes the detected individuals' movements and positions to determine if a fall has occurred using a predefined threshold and mathematical calculations.
4. **Alarm Trigger**: Raises an alarm to notify caregivers or medical staff when a fall is detected.

## Installation

To get started with Caladrius, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/arhammxo/Caladrius.git
   cd Caladrius

2. **Install the required dependencies:**:
   ```bash
   pip install -r requirements.txt

## Usage

To run the Caladrius fall detection system, execute the following command:

   ```bash
   python main.py
   ```
## Contact

If you have any questions or need further assistance, please contact:

- **Email**: [arhammxo@gmail.com](mailto:arhammxo@gmail.com)
- **GitHub**: [arhammxo](https://github.com/arhammxo)

Thank you for using Caladrius! Together, we can make a difference in the lives of those who need it most.