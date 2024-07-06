# Car Detection and Counting using YOLOv5

This project utilizes YOLOv5, a state-of-the-art object detection model, to detect and count cars in a video. The system processes each frame of the video, detects cars, and counts the number of cars crossing a specified line.

## Table of Contents

- Introduction
- Installation
- Usage
- Output
- Contributing
- License

## Introduction

The goal of this project is to detect and count cars in a video file. Each frame of the video is processed using a pre-trained YOLOv5 model. The system detects cars in each frame, and if a car crosses a predefined line, it is counted. The frame number and count are saved to a CSV file, and the frames with detections are saved as images.

## Installation

To get started, clone this repository and install the necessary dependencies.

```bash
git clone https://github.com/yourusername/car-detection-yolov5.git
cd car-detection-yolov5
pip install -r requirements.txt
## Dependencies
torch
opencv-python
pandas
## Usage
Download the YOLOv5 weights: Place your pre-trained YOLOv5 model (car_best.pt) in the project directory.

Run the script: Execute the script to start processing the video and detecting cars.
## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

You can use this content to create a README file (`README.md`) for your project on GitHub.
