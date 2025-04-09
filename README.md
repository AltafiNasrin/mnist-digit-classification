# MNIST Digit Classification with Convolutional Neural Networks (CNNs)

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. It includes data preprocessing, model training, evaluation, and prediction generation for competition-style submission.

## 📌 Project Overview

- **Task**: Image classification (digits 0–9)
- **Dataset**: [MNIST](http://yann.lecun.com/exdb/mnist/) — grayscale 28×28 pixel images
- **Model**: CNN built using TensorFlow/Keras

## 🛠️ Tools & Libraries

- Python
- numpy, pandas
- TensorFlow, Keras
- matplotlib

## 📈 Workflow

1. Loaded and reshaped image data
2. Normalized pixel values
3. Built and trained a CNN model for 100 epochs
4. Monitored training performance with accuracy/loss plots
5. Generated predictions on test data

## 🔍 Results

- Achieved **over 98% validation accuracy**
- Produced accurate digit predictions for use in evaluation or competition

## 📁 Files

- `MNIST.ipynb`: Main notebook containing all code, model architecture, training logic, and prediction steps

## 🧠 Key Takeaway

This project demonstrates how to effectively apply convolutional neural networks to a classic image classification problem, showcasing deep learning workflow from preprocessing to result generation.
