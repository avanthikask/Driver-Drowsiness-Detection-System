The Driver Drowsiness Detection System is an AI-based safety and sustainability project designed to monitor a driver’s alertness in real time.Using computer vision and machine learning, the system detects signs of fatigue such as eye closure, yawning, or head tilting, and issues an instant alert to prevent potential accidents.This project supports green mobility goals by promoting safer and more energy-efficient driving, reducing accident-related fuel wastage, and lowering the environmental footprint of road mishaps.

Key Features:
1)Real-Time Eye & Face Detection: Tracks eye blinking and head position using OpenCV and Dlib.
2)Drowsiness Detection using CNN Model: Identifies fatigue patterns based on live camera input.
3)Instant Audio/Visual Alert: Warns the driver to take a break before safety is compromised.
4)Green Mobility Integration: Contributes to sustainable transport by reducing accidents, fuel wastage, and emissions.
5)Lightweight Edge Deployment: Can run on low-power devices (like Raspberry Pi), promoting green computing.

Libraries:
1)OpenCV:	Used for image and video processing — captures frames from the webcam, detects faces, eyes, and mouth regions in real time.
2)Dlib:	Provides facial landmark detection (68-point model) — used to locate eyes, mouth, and head orientation for drowsiness analysis.
3)TensorFlow: For building and training a Convolutional Neural Network (CNN) model that classifies whether the driver is “alert” or “drowsy”.
4)NumPy:	Performs matrix and array operations for image data handling.
5)imutils:	Simplifies common OpenCV tasks like resizing, rotation, and displaying frames.
6)playsound / pygame:	Used to play an audio alert or alarm when drowsiness is detected.
7)Matplotlib: To visualize accuracy, loss, and EAR threshold trends during testing.

Algorithms:
1)Eye Aspect Ratio (EAR) Algorithm: Geometric-based method used to measure the openness of the eyes using specific facial landmarks.
2)Convolutional Neural Network (CNN): Used to classify whether the driver is “alert” or “drowsy” based on eye region images or full-face images.
