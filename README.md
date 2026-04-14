# Nutrition Monitoring System

## Description
Real-time food detection using MobileNet SSD and OpenCV on Raspberry Pi.

## Requirements
- Python 3.x
- opencv-python
- imutils
- numpy

## Installation
pip install opencv-python imutils numpy

## Usage
python real_time_object_detection.py --prototxt deploy.prototxt --model mobilenet_iter_73000.caffemodel

## How it works
- Webcam captures food item placed on load cell
- MobileNet SSD detects and classifies the food
- Output is displayed on monitor with bounding boxes

## Note
Download the caffemodel from:
https://github.com/chuanqi305/MobileNet-SSD
