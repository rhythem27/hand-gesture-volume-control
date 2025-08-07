# hand-gesture-volume-control
Project Title: Hand Gesture-Based Volume Control System Using Computer Vision

This project implements a real-time hand gesture-based volume controller using a webcam and Python. It leverages the following key technologies and libraries:

OpenCV: For capturing and processing live video frames from the webcam.

MediaPipe: For accurate and efficient hand landmark detection and tracking.

Pycaw (Python Core Audio Windows Library): To control the system's audio volume by interfacing with Windows audio services.

NumPy & Math: For geometric calculations, such as computing the Euclidean distance between fingers.

How it works:
The system detects the positions of the thumb tip and index finger tip using MediaPipe. The distance between these two points is calculated in real time, and this distance is mapped to the system's volume range. The closer the fingers, the lower the volume — and vice versa. The system provides a live video feed with visual cues like lines and circles to assist the user.
