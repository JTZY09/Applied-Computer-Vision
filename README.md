Speed Detection System
Overview
This project implements a speed detection system using OpenCV. It calculates the speed of moving objects by analyzing frame differences and applying contour detection techniques. The system was developed as part of an Applied Computer Vision course project to demonstrate practical applications of computer vision.

Features
Object Tracking: Detects and tracks moving objects in video feeds.
Speed Calculation: Calculates object speeds based on frame rate and object displacement.
Contour Detection: Identifies objects in motion for accurate measurements.
Technologies
Python
OpenCV
How It Works
Frame Differencing: Captures two consecutive frames to detect motion.
Contour Detection: Identifies and tracks objects in motion.
Speed Calculation: Measures the displacement of objects across frames and computes speed based on the frame rate.
Dependencies
Python 3.x
OpenCV 4.x
NumPy
Install Dependencies
Use the following command to install required packages:

bash
Copy
Edit
pip install opencv-python numpy  

License
This project uses open-source tools and follows standard licensing norms.
