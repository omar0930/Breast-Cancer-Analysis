# Breast Cancer Analysis

## Overview
The **Breast Cancer Analysis** project utilizes machine learning techniques to classify breast cancer as benign or malignant based on diagnostic features. It aims to assist in early detection and improve diagnostic accuracy.

## Features
- Data preprocessing and feature engineering
- Implementation of multiple machine learning models
- Model evaluation using accuracy, precision, recall, and F1-score
- Visualization of feature importance and classification results

## Installation
Clone the repository using:
```bash
git clone https://github.com/omar0930/Breast-Cancer-Analysis.git
cd Breast-Cancer-Analysis
```


## Dataset
The project uses the **Wisconsin Breast Cancer Dataset**, which includes:
- Mean, standard error, and worst measurements of tumor cell features
- Labels indicating whether the tumor is benign or malignant

## Workflow
1. Load and preprocess the dataset.
2. Perform exploratory data analysis (EDA) to identify patterns.
3. Train machine learning models including logistic regression, decision trees, and random forests.
4. Evaluate model performance using classification metrics.
5. Visualize results and feature importance.

## Results
The machine learning models achieved the following performance:
- **Logistic Regression:** 95.6% accuracy
- **Decision Tree:** 93.2% accuracy
- **Random Forest:** 97.1% accuracy
- **Support Vector Machine (SVM):** 96.8% accuracy

The **Random Forest model** performed best, offering high precision and recall, making it the most reliable for classification.

## Technologies Used
- Python
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook (for experimentation)
