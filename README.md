# 🧠 Handwritten Digit Recognizer (MNIST) using CNN

This project is a simple Convolutional Neural Network (CNN) model built using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset.

## 📂 About

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9). This project demonstrates the use of CNNs to accurately classify these digits.

## 🚀 Features

- Built with TensorFlow 2.x and Keras
- Achieves high accuracy (>98%) on validation data
- Includes preprocessing, training, and evaluation
- Visualizes training history using matplotlib

## 📊 Model Architecture

- Conv2D
- MaxPooling2D
- Flatten
- Dense (Fully Connected Layer)
- Output Layer (10 classes with softmax)

## 🧪 Results

The model was trained for 5 epochs and achieved high accuracy on the test set.

## 🖼 Sample Output

![MNIST sample](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## 📁 Files

- `mnist_digit_recognizer.ipynb`: Main Jupyter notebook
- `README.md`: Project description and usage

## ✅ How to Run

1. Clone the repository
2. Open the notebook using Jupyter Lab or Notebook
3. Run all cells to train and test the model

```bash
pip install tensorflow matplotlib
