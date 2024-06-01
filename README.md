# Football Analysis Project

## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. Also the model is trained to improve its performance. Additionally, assignment of players to teams is based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match. Also optical flow will be used to measure camera movement between frames, enabling accurate measurement of a player's movement. Furthermore, perspective transformation will be implemented to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered.

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Requirements
To run this project, the following libraries were used
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
