# Vehicle Counter using OpenCV

## Overview
Vehicle detection and counting are crucial for various applications such as traffic monitoring, toll collection, and military purposes. This project implements a basic model to detect and count vehicles from a video input using OpenCV. The program processes the video frames, detects vehicles, and counts them in real-time by applying background subtraction techniques and identifying the best algorithms for the task.

## Features
- Vehicle detection in real-time from video input
- Vehicle counting
- Background subtraction with shadow removal
- Comparison of different background subtraction algorithms based on accuracy, speed, and resource usage
- Easy-to-extend framework for further improvements

## Algorithms Used
Several algorithms for background subtraction are tested and compared:
- **MOG2 (Mixture of Gaussians)**: Efficient and accurate background subtraction method.
- **KNN (K-Nearest Neighbors)**: Another background subtraction algorithm, useful in certain scenarios.
- **BackgroundSubtractorGMG**: A probabilistic foreground/background segmentation algorithm.
  
The results are compared based on:
- Speed of execution
- Accuracy of vehicle detection
- Resource usage (CPU/memory)

## Dependencies
Make sure you have the following installed:
- Python 3.x
- OpenCV
- NumPy


