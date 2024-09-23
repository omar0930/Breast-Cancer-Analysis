# Breast Cancer Analysis

## Overview

This project analyzes a breast cancer dataset using machine learning techniques, particularly a decision tree classifier. The analysis includes various evaluation metrics and visualizations, and the results are displayed in a graphical user interface (GUI) built with the `tkinter` library.

## Problem Statement

The Breast Cancer Analysis project aims to provide insights into the classification of breast cancer tumors. It leverages Python libraries such as `scikit-learn` for machine learning, `matplotlib` for data visualization, and `tkinter` for building the GUI. By using this system, users can classify breast cancer as malignant or benign with high accuracy.

## Features

- **Dataset Loading**: Uses the `load_breast_cancer` function from `scikit-learn` to load the dataset.
- **Data Splitting**: Splits data into training and testing sets.
- **Decision Tree Classifier**: Trains the model using a decision tree classifier.
- **Evaluation Metrics**: Calculates accuracy, confusion matrix, precision, recall, and classification report.
- **Visualization**: Displays feature importance and a graphical representation of the decision tree.
- **GUI Interface**: A user-friendly GUI to display results without requiring coding knowledge.

## System Requirements

### Software Requirements

- Python 3.x
- Libraries: `scikit-learn`, `pandas`, `matplotlib`, `tkinter`
  

## How to Modify the Dataset

The project allows for easy modification of the dataset. By changing the dataset in the code, you can work with any dataset that is compatible with decision trees and feature-based classification tasks.

To modify the dataset:

1. Replace the dataset loading line with the path to your desired dataset.
   For example:
   ```python
   # Replace the existing dataset with your own
   data = pd.read_csv("path_to_your_dataset.csv")
## Results and Discussions

Once the model is trained, the project provides detailed evaluation metrics that help assess its performance:

- **Accuracy**: Measures the overall correctness of the classifier’s predictions.
- **Confusion Matrix**: Gives a detailed breakdown of how the classifier performed on each class (malignant or benign).
- **Precision**: Shows the proportion of positive identifications that were actually correct.
- **Recall**: Shows the proportion of actual positives that were identified correctly.
- **Classification Report**: Summarizes all key metrics, such as precision, recall, and F1 score.

You can visualize these metrics easily through the GUI provided in the project.
