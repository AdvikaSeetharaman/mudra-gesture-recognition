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

## ▶️ How to Run
1. Install dependencies:
