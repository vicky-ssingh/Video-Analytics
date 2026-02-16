# Video Analytics System (Retail, Airport, Factory, Sports)

## Overview

This project implements a Video Analytics pipeline using Computer Vision
and YOLO. It detects people, tracks movement, generates alerts, and
produces a processed output video.

## Features

-   Person detection using YOLOv8
-   Movement tracking
-   Loitering detection
-   Danger zone safety alerts
-   Heatmap-ready architecture
-   Output processed video file

## Use Cases

### Retail

-   Track customer paths
-   Heatmaps of popular aisles

### Airport / Station

-   Crowd monitoring
-   Suspicious behavior detection

### Factory Floor

-   Worker safety monitoring
-   Danger zone alerts

### Sports

-   Player tracking
-   Ball tracking
-   Broadcast analytics

## Tech Stack

-   Python
-   OpenCV
-   YOLOv8 (Ultralytics)
-   NumPy
-   Matplotlib

## Installation

Run:

pip install ultralytics opencv-python matplotlib numpy

## How to Run

1.  Open notebook: video_analytics_jupyter_path_output.ipynb

2.  Set video path: video_path = "path/to/input/video.mp4"

3.  Run all cells

4.  Output saved: output_processed_video.mp4

## Future Improvements

-   Multi-object tracking (DeepSORT)
-   Real-time dashboard
-   Cloud deployment

## Author

Vicky Singh
