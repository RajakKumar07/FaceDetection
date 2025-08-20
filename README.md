👤 Face Detection & Recognition System

This project is a complete Face Detection and Recognition pipeline built with Python, OpenCV, and Deep Learning (Keras/TensorFlow). It provides everything needed to capture face images, preprocess them, train a Convolutional Neural Network (CNN), and recognize faces in real-time.
📌 Features
Capture and save face samples from webcam/IP camera (collect_data.py).
Preprocess images (resize, grayscale, equalize histogram) and prepare labeled datasets (consolidated_data.py).
Train a LeNet-inspired CNN model for multi-person recognition (face_detection.py).
Save trained model as final_model.h5 for later use.
Detect and recognize faces in real-time using Haar Cascade + trained CNN (recognize.py).
Extendable: Add more people by collecting new data and retraining.
Possible use cases: Attendance system, Security verification, Personal recognition tools.
