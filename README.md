# Speed Detection System

## Overview
This repository contains a **Speed Detection System** built using OpenCV. The system calculates the speed of moving objects in video feeds by analyzing frame differences and applying contour detection techniques. It was developed as part of an **Applied Computer Vision** course project to showcase real-world applications of computer vision.

## Features
- **Object Tracking:** Detect and track moving objects in video feeds.
- **Speed Calculation:** Measure object speeds based on frame rate and displacement.
- **Contour Detection:** Accurately identify objects in motion.

## Technologies
- **Python**
- **OpenCV**
- **NumPy**

## How It Works
1. **Frame Differencing:** The system captures two consecutive frames to detect motion.
2. **Contour Detection:** Motion is analyzed using contour detection to identify moving objects.
3. **Speed Calculation:** The displacement of tracked objects across frames is measured, and speed is calculated using the frame rate.

## Dependencies
- Python 3.x
- OpenCV 4.x
- NumPy

## Installation
To install the required dependencies, use:

```bash
pip install opencv-python numpy
```

## License
This project utilizes open-source libraries (**OpenCV** and **NumPy**) and is distributed under the **MIT License**. Feel free to use or modify the code for educational and non-commercial purposes.

## Acknowledgments
- **OpenCV:** Open-source computer vision library for motion tracking and image processing.
- **NumPy:** Fundamental package for scientific computing in Python.

---

Feel free to contribute to this project or raise any issues if you encounter problems. Happy coding!
