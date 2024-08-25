Driver Drowsiness Detection System :

This is a Python-based Driver Drowsiness Detection System designed to enhance road safety and prevent unnecesary accidents  by monitoring and detecting drowsiness in drivers. 
The system utilizes computer vision and machine learning techniques to analyze eye blinks and other facial features to classify the driver's state as awake, drowsy, or asleep.

Features:

Real-Time Detection: The system processes video frames in real-time to assess the driver's level of alertness.

Eye Blink Analysis: Uses eye aspect ratio (EAR) to detect eye blinks and identify signs of drowsiness.

Alert System: Generates alerts (visual/audio) when drowsiness is detected to prevent accidents.

Technologies Used:

Python: The core programming language used for developing the system.

OpenCV: For real-time video capture and image processing.

Dlib: For facial landmark detection, particularly for locating the eyes.

Scipy: Utilized for scientific and mathematical computations, including signal processing.

Pygame: To create an interactive interface and generate alerts.

Workking:

Video Capture: The system captures real-time video using a webcam.

Facial Landmark Detection: Dlib's pre-trained models are used to detect and extract facial landmarks, focusing on the eyes.

Eye Blink Detection: The Eye Aspect Ratio (EAR) is computed to monitor blinking patterns. A consistent low EAR indicates drowsiness.

Alert Mechanism: If drowsiness is detected based on blink patterns, the system triggers an alert to wake the driver.
