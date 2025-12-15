# Face Detection and Recognition System
# Objective
Develop a face detection and recognition system using machine learning to identify individuals from images/video, suitable for use in an automated attendance-style application.
# Tools & Technologies
PythonOpenCV (for face detection and image processing)scikit-learn / face recognition library (as used in your project)
# Key Steps
Collected and organized face images for multiple individuals and created labelled training data.
Detected faces in images/video frames using OpenCV and extracted face regions for training.
Trained a face recognition model on encoded face features and evaluated recognition accuracy.
Implemented a simple script to capture frames from webcam, detect faces and display predicted names in real time.
# Results
Successfully detected faces and recognized known individuals with good accuracy on test images.
Demonstrated how ML-based face recognition can support applications such as automated attendance or access control.
# How to Run
Clone this repository.
Install dependencies from requirements.txt.
Prepare or download sample training images in the data/images/ folder.
Run python src/face_detection_recognition.py to perform detection and recognition
