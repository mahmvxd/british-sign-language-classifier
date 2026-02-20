# BSL Alphabet Real-Time Classifier

## Overview
A CNN-based image classification project for recognising British Sign Language (BSL) alphabet gestures (A–Z). The model supports both offline image classification and real-time webcam inference using OpenCV.

## What’s Included
- `notebooks/` — training + real-time inference notebook
- `models/` — trained Keras model (`.keras`)
- `results/` — evaluation screenshot(s)
- `label_map.json` — class index ↔ label mapping

## Dataset
Dataset used: Kaggle (not included in this repository due to size ~8.8GB).  
Add the Kaggle link here:
https://www.kaggle.com/datasets/erentatepe/bsl-numbers-and-alphabet-hand-position-for-mediapipe?select=1_HAND_DATASET  
https://www.kaggle.com/datasets/erentatepe/bsl-numbers-and-alphabet-hand-position-for-mediapipe?select=2_HAND_DATASET

## Technologies
Python • TensorFlow/Keras • OpenCV • NumPy • scikit-learn

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
