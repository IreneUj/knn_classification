# knn_classification
Breast cancer diagnosis using the K-Nearest Neighbors (KNN) algorithm with feature scaling, cross-validation, and model evaluation.
# Project Overview

This project builds a **K-Nearest Neighbors (KNN)** classification model to predict whether a breast tumor is **benign** or **malignant** using the Breast Cancer Wisconsin Diagnostic dataset from scikit-learn. The project demonstrates a complete machine learning workflow, including data exploration, preprocessing, model training, hyperparameter tuning, and performance evaluation.

# Dataset
The dataset used in this project is the **Breast Cancer Wisconsin Diagnostic Dataset**, which is available through the `scikit-learn` library.

# Dataset Characteristics

- Number of samples: **569**
- Number of features: **30** 
- Target classes:
  - **0:** Malignant
  - **1:** Benign

The features describe characteristics breast mass cell nuclei, such as:

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Symmetry
- Fractal Dimension
  
# Project Objectives

- Explore and understand the dataset.
- Visualize feature distributions.
- Split the dataset into training and testing sets.
- Standardize numerical features using StandardScaler.
- Train a K-Nearest Neighbors classifier.
- Tune the optimal value of **k** using cross-validation.
- Evaluate model performance using multiple classification metrics.
- Predict the diagnosis of new patient samples.


## Project Workflow

# Exploratory Data Analysis (EDA)
- Examine dataset dimensions.
- Check feature names and data types.
- Check for missing values.
- Visualize feature distributions.

# Data Preprocessing
- Split the dataset into training and testing sets (80/20).
- Standardize numerical features using StandardScaler.

# Model Development
Train a K-Nearest Neighbors classifier using multiple values of **k**:
- k = 1
- k = 3
- k = 5
- k = 7
- k = 9
- k = 11

Use **5-fold cross-validation** to determine the optimal number of neighbors.

# Model Evaluation
Evaluate the final model using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

# Prediction
Use the trained model to classify new patient data.
