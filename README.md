# final_year_project
social distance monitoring ml model system implemented as a desktop app

Social Distancing Monitoring System

Description
This Python script implements a real-time social distancing monitoring system using the YOLO (You Only Look Once) object detection algorithm. The system detects people in a given video stream or file and assesses their compliance with social distancing guidelines. It draws bounding boxes around individuals, colors them based on their compliance level, and provides violation statistics.

Features
Real-time social distancing monitoring.
Display of bounding boxes and centroids for detected individuals.
Differentiates between serious and abnormal violations.
Sends email alerts when serious violations exceed a predefined threshold.

Requirements
Python 3
OpenCV
NumPy
imutils
scipy
YOLOv3 weights and configuration file
Other custom modules: mylib.config, mylib.thread, mylib.mailer, mylib.detection
