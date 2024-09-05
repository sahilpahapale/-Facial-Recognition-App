# -Facial-Recognition-App

# Overview
This project implements a face detection and identification pipeline using OpenCV and TensorFlow/Keras. It is designed to capture, process, and classify facial images into positive, negative, and anchor sets, which are used for training a model on facial similarity tasks. The application is structured around the concepts of facial verification, aiming to verify if two faces belong to the same person.

# Features
Face Detection: Detects faces from webcam images using OpenCV.

Dataset Creation: Generates positive, negative, and anchor datasets for training.

Model Training: A CNN model is trained using TensorFlow/Keras for face recognition tasks.

# Directory Structure

The project organizes images into three main directories:

data/positive: Contains images for the positive class (anchor faces).

data/negative: Contains images for the negative class (non-anchor faces).

data/anchor: Contains images for face verification tasks.
