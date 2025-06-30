# Gesture-Recognition-using-MediaPipe
A gesture recognition system for construction site hand signals using MediaPipe Holistic and LSTM.
# Gesture Recognition for Construction Hand Signals

This project implements a gesture recognition system tailored for construction environments, where workers often rely on standardized hand signals for communication amidst noise and distance. The system uses **MediaPipe Holistic** to extract real-time pose and hand landmarks from video input, and a **Long Short-Term Memory (LSTM)** neural network to classify dynamic gesture sequences.

The pipeline includes:
- A custom OpenCV-based tool for recording gesture data
- CSV-based storage of landmark sequences (60 frames per sample)
- An LSTM model built with TensorFlow/Keras for training and inference
- Accuracy and confusion matrix visualization for evaluation

The current version supports four construction-related gestures: **Stop**, **Emergency Stop**, **Hoist**, and **Lower Load**. This repository was developed as part of a research project under the URECA programme at NTU.


---

## 🔗 Project Info

This repository was created by Elangovan Harshan as part of a URECA research project at Nanyang Technological University (NTU), Singapore.


