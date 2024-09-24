# Image Classification with CNN and TensorFlow

## Project Overview
This project implements a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset. The goal is to categorize images into 10 predefined classes, including airplanes, cars, birds, cats, and more.

## Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes, with 6,000 images per class. The dataset can be easily loaded using TensorFlow.

## Key Features
- **Data Preprocessing**: Normalized image inputs to enhance model performance.
- **Model Architecture**: Designed a CNN with:
  - Convolutional layers for feature extraction
  - Pooling layers for dimensionality reduction
  - Fully connected layers for classification
- **Training**: Utilized the Adam optimizer and sparse categorical crossentropy loss function over 10 epochs.
- **Performance Evaluation**: Achieved a test accuracy of approximately **68.82%** on unseen data.
- **Visualization**: Plotted training and validation accuracy and loss to analyze model performance.

## Installation
To run this project, make sure you have Python installed along with the following libraries:

```bash
pip install tensorflow matplotlib
