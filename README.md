# Speed Detection System

## Overview
This project implements a speed detection system using OpenCV. It calculates the speed of moving objects by analyzing frame differences and applying contour detection techniques. The system was developed as part of an Applied Computer Vision course project to demonstrate practical applications of computer vision.

## Features
- Detects and tracks moving objects in video feeds.
- Calculates object speeds based on the frame rate and object displacement.
- Uses contour detection for object identification.

## Technologies
- **Python**
- **OpenCV**

## How It Works
1. **Frame Differencing:** Captures two consecutive frames to detect motion.
2. **Contour Detection:** Identifies and tracks objects in motion.
3. **Speed Calculation:** Measures the displacement of objects over different frames.

Dependencies
Python 3.x
OpenCV 4.x
NumPy
Install dependencies via pip:
pip install opencv-python numpy
