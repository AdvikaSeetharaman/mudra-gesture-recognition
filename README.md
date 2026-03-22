# Hierarchical Mudra Recognition System

This project implements a real-time Bharatanatyam mudra recognition system using MediaPipe and Bidirectional LSTM (BiLSTM).

## Features
- Real-time webcam-based gesture detection
- MediaPipe Holistic landmark extraction
- Hierarchical classification:
  - Mudra recognition
  - Meaning interpretation

## Model
- BiLSTM architecture
- Dual-output classification (mudra + meaning)
- Sequence-based learning (30 frames)

## Dataset
- 20 mudra-meaning classes
- 120 sequences per class
- Stored as NumPy keypoint arrays

## Technologies Used
- TensorFlow / Keras
- MediaPipe
- OpenCV
- NumPy
- scikit-learn

## How to Run
1. Install dependencies: pip install tensorflow mediapipe opencv-python numpy scikit-learn matplotlib
2. Run the notebook: mudra_recognition_model.ipynb


## Output
- Real-time gesture recognition
- Hierarchical prediction (mudra + meaning)
- Probability visualization

## Research Context
This repository supports the paper:
"Hierarchical Real-Time Gesture Interpretation of Bharatanatyam Mudras Using Bidirectional LSTM Networks"

## Supplementary Note
Dataset and additional implementation details can be provided upon request.

