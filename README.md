# Hand Gesture Controlled Robot

An intelligent robot that uses hand gesture recognition to control movement in real time.

## Overview
This project combines computer vision, machine learning, and robotics to create a robot that responds to hand gestures captured through a live camera feed.

The system detects hand landmarks, classifies gestures, and sends movement commands to the robot via Arduino.

## Features
- Real-time hand gesture recognition
- Robot movement control
- Obstacle avoidance using ultrasonic sensor
- Human-Robot Interaction (HRI)

## Gesture Commands
- 5 Fingers → Forward
- 1 Finger → Right
- 2 Fingers → Left
- 3 Fingers → Backward
- 0 Fingers → Stop

## Machine Learning
- Model: Random Forest Classifier
- Accuracy: ~98%
- Dataset: 152 test samples

## Hardware
- Arduino Uno
- L293D Motor Driver
- DC Motors
- Ultrasonic Sensor
- Robot Chassis

## Software & Tools
- Python
- OpenCV
- MediaPipe
- Scikit-learn
- Arduino IDE

## Challenges
- Difficulty integrating ESP32-CAM wirelessly
- Gesture confusion in similar hand poses
- Limited obstacle detection from front sensor only

## Future Improvements
- Wireless control
- LiDAR integration
- Better gesture classification

## Team Members
- Shumukh Eid Altoom
- Shatha Ibrahim Ghabban
- Layal Mohammed Alhazmi
- Hatoon Mohammed Ghabban

## Course
AI371 — Cognitive Robotics  
Taibah University
