# Digit Classifier

A handwritten digit classification project based on the MNIST dataset using Logistic Regression to classify digits from 0 to 9.

## Overview

The project processes 28×28 pixel grayscale images and applies preprocessing and feature scaling before training the Logistic Regression model.

## Dataset

- **Dataset:** MNIST
- **Total Samples:** 70,000
- **Training Samples:** 60,000
- **Test Samples:** 10,000
- **Image Size:** 28×28 pixels
- **Classes:** 10 (digits 0–9)
- **Pixel Range:** 0–255, normalized to 0–1

## Machine Learning Pipeline

MNIST Dataset → Normalization → Train/Test Split → Feature Scaling → Logistic Regression → Prediction → Evaluation

## Model

**Logistic Regression**

- Solver: LBFGS
- C: 1.0
- Maximum Iterations: 200
- Feature Scaling: StandardScaler

## Results

The model achieved **98.07% classification accuracy** on the 10,000 test samples.

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Features

- Handwritten digit classification from 0–9
- MNIST dataset processing
- Pixel normalization and feature scaling
- Logistic Regression classification
- Performance evaluation
- Confusion matrix analysis
- Precision, recall, and F1-score analysis
- Interactive digit drawing and prediction interface

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Logistic Regression
- StandardScaler
- MNIST
- Machine Learning
- Data Visualization

## Project Preview

The project includes an interactive interface where users can draw a handwritten digit and obtain the model's predicted digit along with its probability distribution.

## Author

**Eswar Prasad**

GitHub: [EswarPrasad369](https://github.com/EswarPrasad369)
