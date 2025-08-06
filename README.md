# Digit Recognition System

A simple machine learning project that classifies handwritten digits (0–9) using the **K-Nearest Neighbors (KNN)** algorithm and the **Scikit-learn** library. It utilizes the popular **digits dataset** available in `sklearn.datasets`.

## Features

- Load and visualize handwritten digit data
- Train a classification model (KNN by default)
- Predict the class of new digit images
- Evaluate model accuracy with a confusion matrix and classification report

## Dataset

The project uses the **Digits Dataset** from Scikit-learn, consisting of:
- 1797 grayscale images of size 8x8
- 10 classes (digits from 0 to 9)
- Each image is flattened into a 64-length feature vector
