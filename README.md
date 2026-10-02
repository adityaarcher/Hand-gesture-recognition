# Hand Gesture Mouse Control

A real-time Python application that uses computer vision and hand tracking to control your system's mouse cursor using hand gestures via a webcam.

## Features

* **Real-Time Tracking**: Fast and efficient hand landmark detection powered by MediaPipe.
* **Cursor Control**: Move the system mouse pointer naturally across the screen using your fingers.
* **Gesture Actions**: Support for clicking, dragging, scrolling, and cursor freezing based on finger positioning and distance metrics.

## Tech Stack

* **Python 3.10+**
* **OpenCV (`cv2`)**: For webcam feed acquisition and frame processing.
* **MediaPipe**: For hand landmark detection and tracking.
* **PyAutoGUI**: For controlling the operating system's mouse and screen size detection.

## Project Structure

```text
Hand-gesture-recognition/
│
├── pro/
│   ├── main.py        # Main execution script for gesture detection & mouse control
│   ├── util.py        # Math utilities (angle and distance calculation functions)
│   └── require.txt    # Project dependencies
│
├── .gitignore         # Ignores virtual environments and cache
└── README.md          # Project documentation
