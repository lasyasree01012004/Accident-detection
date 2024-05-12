# Accident Severity Prediction

This project aims to predict the severity of accidents in the United States based on various features such as location, weather conditions, road conditions, and more. The dataset used is the "US Accidents Dec21 updated" dataset from Kaggle.

## Dependencies

The following Python libraries are required:

- pandas
- numpy
- matplotlib
- seaborn
- missingno
- scikit-learn
- imbalanced-learn

## Usage

1. Download the dataset from Kaggle using the provided command.
2. Install the required dependencies.
3. Run the Python script to preprocess the data, train the machine learning models, and evaluate their performance.

## Models

The following machine learning models are implemented and evaluated:

- Random Forest
- Logistic Regression
- K-Nearest Neighbors
- Gradient Boosting
- Decision Tree
- Multi-Layer Perceptron

## Dimensionality Reduction

Linear Discriminant Analysis (LDA) is used for dimensionality reduction, and the models are trained and evaluated on the reduced feature space.

## Location-based Analysis

The location feature is analyzed, and the dataset is split based on the location to investigate location-specific patterns.
