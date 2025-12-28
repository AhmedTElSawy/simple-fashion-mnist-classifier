# Simple Fashion MNIST Neural Network

A beginner-friendly TensorFlow/Keras model for classifying images from the Fashion MNIST dataset (e.g., shirts, shoes, bags).

## Overview
- Dataset: Fashion MNIST (60,000 training + 10,000 test images, 10 classes).
- Model: 3-layer feedforward neural network (Flatten + Dense(128, ReLU) + Dense(10, Softmax)).
- Training: 10 epochs, Adam optimizer, sparse categorical cross-entropy loss.
- Results: ~91% training accuracy, ~88% test accuracy (may vary slightly).

## How to Run
1. Clone the repo: `git clone https://github.com/AhmedTElSawy/simple-fashion-mnist-classifier.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run the notebook: `jupyter notebook fashion-mnist-classifier.ipynb`

## Dependencies
- TensorFlow/Keras
- Matplotlib (for visualizations)
