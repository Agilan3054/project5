# Video People Counter

## Overview

This Python script utilizes OpenCV for computer vision tasks to count the number of people in a video stream. It employs background subtraction for motion detection and draws bounding boxes around regions with sufficient motion to identify people.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)
- IPython (`IPython.display`)
- Pillow (`PIL.Image`)

## Configuration
Adjust the following parameters in the script to suit your needs:

- video_path: Path to the video file.
- min_contour_area: Minimum contour area to consider for detecting a person
