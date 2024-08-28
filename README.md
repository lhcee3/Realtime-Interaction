# Realtime Interaction Program

This is a Python-based face detection program that utilizes the OpenCV, MediaPipe, and PyAutoGUI libraries. The program is designed to detect faces in real-time through your computer's camera and perform specific actions based on the detection results.

## Features

- **Wink to Click:** Supports retina detection of face and helps you click when you wink.
- **Hand Detection:** Utilizes MediaPipe’s advanced hand detection models for precise tracking of hand that also be used to control the cursor.
- **Scroller:** Integrated with PyAutoGUI for automating GUI to scroll through any window with just a nod of head.

## Requirements

Before you can run the program, you need to have the following Python libraries installed:

- `opencv-python`
- `mediapipe`
- `pyautogui`

You can install these libraries using pip:

```bash
pip install opencv-python mediapipe pyautogui
How to Use
Clone the Repository:

First, clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/face-detection.git
cd face-detection
Run the Program:

Execute the Python script to start the face detection:

bash
Copy code
python face_detection.py
The program will automatically start the webcam and begin detecting faces. When a face is detected, the program can perform actions, such as moving the mouse cursor, taking a screenshot, or other automated tasks using PyAutoGUI.

Stopping the Program:

To stop the program, simply close the window displaying the webcam feed or press Ctrl+C in the terminal.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
