# MNIST Handwritten Digit Classifier 🖥️🖌️

A simple Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

## 📚 Overview

This project uses a Convolutional Neural Network to recognize handwritten digits (0-9) from grayscale images.  
The dataset used is MNIST, which consists of 70,000 images of handwritten numbers.

## 🛠️ Technologies
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

## 🚀 How to Run

1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Run the notebook `mnist_classifier.ipynb` on [Google Colab](https://colab.research.google.com/) or locally.

3. Train the model and test predictions on sample images.

## 📊 Model Summary

- 2 Convolutional layers
- MaxPooling
- Dense fully connected layer
- Softmax output for classification

## 📈 Results

Achieved around **99% accuracy on the training set** and over **98% on the test set** after 5 epochs.

## 📎 Example Output

Prediction on a test image:
