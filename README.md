# GestureWave: Hand Gesture Volume Control

## Overview
**GestureWave** is a Python-based project that allows users to control the computer's volume using hand gestures. Utilizing OpenCV, MediaPipe, and PyAutoGUI libraries, this project captures hand movements via a webcam, identifies key hand landmarks, and calculates the distance between specific points to adjust the system's volume accordingly.

## Features
- **Real-Time Hand Gesture Recognition:** Uses a webcam to detect and track hand gestures.
- **Volume Control:** Adjusts the system volume by measuring the distance between the thumb and forefinger.
- **Visual Feedback:** Displays video with hand landmarks and lines drawn between key points.

## Tech Stack
- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **Hand Tracking:** MediaPipe
- **System Control:** PyAutoGUI
- **Development Environment:** PyCharm

## How It Works
- **Capture Webcam Video:**
The project starts by capturing video from the webcam using OpenCV's VideoCapture.

- **Hand Landmark Detection:**
MediaPipe is used to detect hand landmarks in the video feed, which are then displayed on the screen.

- **Calculate Distance:**
The project identifies the landmarks of the thumb and forefinger. It calculates the distance between these two points, which is used to determine the desired volume level.

- **Adjust Volume:**
Using PyAutoGUI, the system's volume is adjusted based on the distance calculated between the thumb and forefinger.

- **Exit the Application:**
Press the ESC key to stop the camera and exit the application.

## Future Improvements
- **Gesture Customization:** Allow users to customize which gestures control the volume.
- **Multi-Gesture Support:** Add more gestures for additional controls (e.g., mute, play/pause).
- **Cross-Platform Support:** Ensure compatibility across different operating systems.

