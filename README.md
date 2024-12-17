# Lane Detection

## Overview

This repository contains a Python script for lane detection in a video using OpenCV. The script processes a video file, detects lane lines, and displays the result in real-time. Key computer vision techniques like Region of Interest (ROI) selection, dilation, grayscale conversion, thresholding, Canny edge detection, and Hough Transform are used.

## Features

1.Select and crop a Region of Interest (ROI) for lane detection.

2.Detect white lane lines based on pixel intensity.

3.Apply Canny edge detection and Hough Transform to identify lane lines.

4.Display the detected lane lines over the original video.

## Requirements

To run this script, ensure you have the following installed:

1.Python 3.x

2.OpenCV (cv2)

3.NumPy

You can install the required libraries using:

pip install opencv-python-headless numpy

## How to Use

1.Clone the Repository:

git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

2.Place the Input Video:
Ensure the input video is placed in the Videos directory or update the video_path variable in the script to the correct path.

3.Run the Script:

python lane_detection.py

4.Select ROI:

After running the script, a window will appear to select the ROI.

Use your mouse to draw a bounding box over the area where lanes are expected.

Press Enter to confirm the selection.

5.View Results:

The video will be displayed with the detected lane lines drawn in green.

Press 1 to exit the video playback.
