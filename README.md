# 🏏 Bowling Action Angle Analysis

A computer vision project that analyzes a cricket bowling action by detecting body landmarks and calculating the **elbow angle** throughout the bowling motion.

## Features

* Detects body landmarks using **MediaPipe Pose**
* Tracks the shoulder, elbow, and wrist
* Calculates the elbow angle frame by frame
* Stores elbow-angle data for bowling-action analysis
* Uses **OpenCV** for video processing

## Technologies

* Python
* OpenCV
* MediaPipe
* NumPy

## How It Works

```text
Bowling Video
     ↓
MediaPipe Pose Detection
     ↓
Shoulder + Elbow + Wrist
     ↓
Elbow Angle Calculation
     ↓
Bowling Action Analysis
```

## Installation

```bash
pip install opencv-python mediapipe numpy
```


## Project Structure

```text
Bowling-Action-Angle-Analysis/
├── cricket_test.py
├── videos/
└── README.md
```

## Disclaimer

This project is intended for educational and experimental purposes. The calculated elbow angle is a computer-vision estimate and should not be considered an official assessment of a bowling action.

## Author

**Abin K Vijayan**
