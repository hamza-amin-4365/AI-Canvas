# Virtual AI Canvas with OpenCV and MediaPipe

## Table of Content
- [Overview](#overview)
- [Demo](#demo)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
- [Installation And Run](#installation-and-run)
- [Directory Tree](#directory-tree)
- [To Do](#to-do)
- [Bug / Feature Request](#bug---feature-request)
- [Technologies Used](#technologies-used)
- [Credits](#credits)
  
## Overview
This project is a hand tracking application built using OpenCV and MediaPipe. The application can detect hands in real-time from a webcam feed, track the position of hand landmarks, and provide functionality for drawing and erasing on the screen using hand gestures.

## Demo
Here's a brief demonstration of the hand tracking application in action:

## Motivation
The motivation behind this project was to explore the capabilities of computer vision and hand tracking technologies, and to create an interactive application that demonstrates these capabilities in a fun and engaging way.

## Technical Aspect
The application uses the following technologies and libraries:

- **Opencv**: An open-source computer vision and machine learning software library.
- **MediaPipe**: A cross-platform framework developed by Google for building multimodal applied machine learning pipelines.
- **Numpy**: A library for the Python programming language, adding support for large, multi-dimensional arrays and matrices.

The application follows these steps:

1. Capture video from a webcam.
2. Use MediaPipe to detect and track hand landmarks in the video frames.
3. Implement different modes for drawing and erasing on the screen based on hand gestures.
4. Overlay the drawing on the video feed and display it to the user.

## Installation And Run
1. Clone the repository or download the source code.
2. Install the required packages by running the following command:

```bash
pip install -r requirements.txt
```
3. Run the application with the following command:
```bash
python VirtualPainter.py
```
Directory Tree
```
│   app.py
│   HandTrackingModule.py
│   README.md
│   requirements.txt
└───Header
        # Images for header will be stored here
```
## To Do

* Improve hand tracking accuracy and responsiveness.
* Add support for more gestures and interactions.
* Optimize performance for lower-end hardware.

## Bug / Feature Request
If you find a bug or have a feature request, please open an issue [here](https://github.com/hamza-amin-4365/AI-Canvas/issues/new).

## Technologies Used
<img target="_blank" src="https://opencv.org/wp-content/uploads/2020/07/OpenCV_logo_black.png" width=200>
<img target="_blank" src="https://mediapipe.dev/images/logo_horizontal_color.png" width=200>
<img target="_blank" src="https://numpy.org/images/logo.svg" width=200>

## Credits
* MediaPipe
* OpenCV
* NumPy