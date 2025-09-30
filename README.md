# IRIS - Classification | by using K-Nearest Neighbors (KNN) Classifier

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm for classification tasks using the popular Iris dataset. The notebook walks through the end-to-end process of classification, including data loading, preprocessing, model training, prediction, and evaluation.

## Overview

K-Nearest Neighbors (KNN) is a simple, supervised machine learning algorithm that can be used for both classification and regression tasks. In classification, it predicts the class of a sample based on the majority class among its k-nearest neighbors in the feature space.

## How it Works

1. **Data Loading**: The Iris dataset is loaded from `sklearn.datasets`.
2. **Data Splitting**: The dataset is split into training and testing sets.
3. **Model Training**: A KNN classifier is trained on the training data.
4. **Prediction**: The trained model predicts the classes for the test data.
5. **Evaluation**: The model's performance is evaluated using accuracy score, confusion matrix, and classification report.

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Results

- **Accuracy**: Achieves high accuracy (~98%) on the Iris test dataset.
- **Confusion Matrix**: Shows the correct and incorrect predictions for each class.
- **Classification Report**: Provides precision, recall, and f1-score for each class.
