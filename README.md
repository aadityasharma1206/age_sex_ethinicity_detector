# Age, Sex, and Ethnicity Prediction using Deep Learning

This project is a deep learning-based system that predicts the age, sex, and ethnicity of a person from live webcam input. It utilizes TensorFlow and Keras for the neural network architecture and OpenCV for integrating webcam feeds.

# Project Overview

This project implements a convolutional neural network (CNN) to predict three attributes (age, sex, and ethnicity) based on a person's facial features captured through a webcam. The system is trained on the UTKFace dataset, achieving an accuracy of 85.6% on the test set.


# Features
Real-time predictions of age, sex, and ethnicity using webcam input.
Neural network designed using TensorFlow and Keras.
Webcam integration through OpenCV for real-time facial detection and analysis.
Preprocessing pipeline for face detection and image augmentation.
Easy setup and usage through Python scripts.
Model Architecture
The neural network architecture is a custom-designed convolutional neural network (CNN) built using TensorFlow and Keras:

Input: Webcam feed captured using OpenCV.
Output: Predicted age, sex, and ethnicity.
The model uses several convolutional and fully connected layers, optimized using Adam optimizer and trained over the UTKFace dataset. Model uses a fine tuned VGG16 architecture for the purpose.


# Dataset
The model is trained on the publicly available UTKFace dataset, which consists of over 20,000 labeled images of human faces across a variety of ages, genders, and ethnicities.

Image Augmentation: Augmented images using standard techniques like flipping, zooming, and rotating to improve model robustness.
