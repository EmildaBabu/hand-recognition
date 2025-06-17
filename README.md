# **Hand Recognition**
The Hand Recognition System utilizes MediaPipe on a Raspberry Pi, an advanced computer vision framework, to perform real-time hand tracking and gesture recognition. By identifying 21 key landmarks on the hand through a webcam feed, it enables gesture-based control for various applications. The system is lightweight, fast, and platform-independent, offering smooth and efficient performance for interactive tasks such as virtual input, robotic control, or educational tools.

## AIM
To design and implement a real-time hand recognition system using MediaPipe on a Raspberry Pi, capable of detecting and interpreting hand gestures for seamless, contactless control and interaction.

## COMPONENTS
1. Raspberry Pi 4 
2. USB Webcam
3. MicroSD Card (with Raspbian OS)
4. Power Supply for Raspberry Pi

## PROCEDURE
Step 1:
Set up the Raspberry Pi with the latest Raspberry Pi OS and ensure Python is installed and up to date.

Step 2:
Connect a USB webcam to the Raspberry Pi and verify it is working by capturing test images or video using Python and OpenCV.

Step 3:
Install the required Python libraries using pip:
pip install opencv-python mediapipe

Step 4:
Write a Python script to access the webcam feed and initialize MediaPipe’s hand detection module to detect and track hand landmarks in real-time.

Step 5:
Run the script and test the system by showing your hand in front of the webcam. Verify that the system detects the hand and displays 21 hand landmarks on the video feed.


## OUTPUT
<img src="https://github.com/EmildaBabu/hand-recognition/blob/c6507deab120e5fbd7715b32557e8690fdd2c71a/images/hand%20reocg.png" alt="Hand-recog" width="300" height="250">
<img src="https://github.com/EmildaBabu/hand-recognition/blob/c6507deab120e5fbd7715b32557e8690fdd2c71a/images/rasperry%20pi.png" alt="rasppi4" width="300" height="250">




