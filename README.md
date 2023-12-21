# Resume Classifier

## Overview
This project implements a resume classifier using a deep learning model based on the ResNet50 architecture. The model is trained to classify images into two categories: resumes and non-resumes. The project includes data preprocessing, model training, and evaluation.

## Table of Contents
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Usage](#usage)
- [Requirements](#requirements)

## Dataset
The dataset used for training and testing contains diverse images of resumes and non-resumes. Images have been resized to (224, 224) for consistency.

## Model Architecture
The ResNet50 architecture, combined with custom layers, is employed for effective image classification. The model includes global average pooling, dense layers, and dropout for robust learning.

## Training
The model is trained using data augmentation techniques for enhanced robustness. Early stopping is implemented to prevent overfitting. The training process is detailed in the code.

## Evaluation Metrics
Evaluation metrics include a confusion matrix and classification report. The model's strengths and limitations are discussed based on these metrics.

## Results
The trained model achieves high accuracy and balanced precision-recall. Strengths include accurate identification of resumes, while limitations are noted for consideration, especially with a small dataset.

## Usage
1. Clone the repository.
2. Ensure the required libraries are installed (see [Requirements](#requirements)).
3. Run the provided Jupyter Notebook or Python script for training and evaluation.
4. Use the saved model for making predictions on new images.

## Requirements
- Python 
- TensorFlow
- OpenCV
- Matplotlib
- sklearn
