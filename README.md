# Breast Cancer Classification Project

## Overview

This project aims to classify breast cancer tumors as malignant or benign using machine learning techniques on the Breast Cancer Wisconsin dataset from sklearn. The dataset includes various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin dataset, which consists of:

- **Number of samples**: 569
- **Number of features**: 30
- **Target variable**: Class labels (0 for benign, 1 for malignant)

### Features

The features include various measurements of the cell nuclei present in the FNA, such as radius, texture, perimeter, area, smoothness, and compactness.

## Preprocessing Steps

1. **Data Import**: Load the dataset using `sklearn.datasets`.
2. **Data Exploration**: Understand the dataset's structure, missing values, and class distribution.
3. **Data Splitting**: Split the dataset into training and testing sets (70% training, 30% testing).
4. **Data Scaling**: Standardize the features using `StandardScaler` to ensure they have a mean of 0 and a standard deviation of 1.
5. **Outlier Detection**: Identify and handle outliers using methods such as Z-score or IQR if necessary.

## Model Training

The project utilizes various machine learning models to classify the tumors:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

Each model is evaluated based on accuracy, precision, recall, and F1 score.

## Results

The results of the classification will be presented in terms of confusion matrices, classification reports, and accuracy scores for each model.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
