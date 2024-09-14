# Fashion MNIST CNN Classifier

This project uses a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset.

## Requirements

- TensorFlow
- NumPy
- Matplotlib

## How to Run

1. Install the required dependencies:
2. Run the Python script
3. The script will train the CNN and output predictions for two test images.

## Model Overview

The CNN consists of six layers:
1. 3 Convolutional layers with ReLU activation
2. MaxPooling layers to reduce spatial dimensions
3. A Flatten layer to convert 2D feature maps to 1D vectors
4. A Dense layer with 64 units and ReLU activation
5. An output layer with softmax activation for classification
