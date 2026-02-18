# Iris Classification using KNN

![Iris Dataset](https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification-1024x367.png)

This project demonstrates a basic machine learning workflow using the Iris dataset from scikit-learn.

## Overview

The dataset contains measurements of iris flowers based on four features:

- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

Each sample belongs to one of three classes:
- Setosa  
- Versicolor  
- Virginica  

## Steps Performed

- Checked Python and library versions (NumPy, pandas, matplotlib, SciPy, scikit-learn, etc.)
- Loaded the Iris dataset using `load_iris()`
- Explored dataset structure (features, target names, shape, sample data)
- Split the dataset into training (75%) and testing (25%) sets
- Visualized training data using a scatter matrix
- Trained a **K-Nearest Neighbors (KNN)** classifier with `n_neighbors=1`
- Predicted the class of a new sample: `[5, 2.9, 1, 0.2]`
- Evaluated model accuracy on the test set

## Model

KNeighborsClassifier (k = 1)

## Result

The model achieved a high accuracy score on the test dataset using the KNN algorithm.

## Author

Saumya Srivastava
