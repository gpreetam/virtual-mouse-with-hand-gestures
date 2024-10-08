VIRTUAL MOUSE USING HAND GESTURES
This project implements a virtual mouse that allows users to control their computer cursor through hand gestures. The project leverages computer vision techniques to recognize and track hand gestures and translates them into mouse movements and clicks, providing an intuitive and contactless way to interact with a computer.

FEATURES
Cursor Control: Move the cursor on the screen using hand movement.
Left Click Gesture: Perform a left click with a specific hand gesture.
Right Click Gesture: Perform a right click with another gesture.
Screenshot: Close all five fingers to take a screenshot.
Double Click Gesture: Perform a double click with close two fingers. 

HOW IT WORKS
Computer Vision:
            Utilizes a webcam to capture real-time video frames.
            Hand detection and gesture recognition are performed using OpenCV and MediaPipe.

Hand Gesture Recognition:
            Specific gestures are mapped to mouse functions such as movement, clicks, and scrolling.
            The project can be extended to support more gestures and commands.

Mouse Event Simulation:
            The recognized hand gestures are mapped to actual mouse events (movement, click, scroll) using libraries like PyAutoGUI or Pynput to control the system cursor.

REQUIREMENTS
To run this project, ensure you have the following installed:
Python 3.x
OpenCV (pip install opencv-python)
MediaPipe (pip install mediapipe)
PyAutoGUI (pip install pyautogui)
Pynput (pip install pynput)
