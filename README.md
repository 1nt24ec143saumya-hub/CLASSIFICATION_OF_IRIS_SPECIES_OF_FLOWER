# Iris Flower Classification

![Iris Dataset](https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification-1024x367.png)

This project builds a machine learning model to classify iris flowers into three species: Setosa, Versicolor, and Virginica.

The classification is based on four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Objective
To train and evaluate models that can predict the species of an iris flower using these measurements.

## Method
- Performed basic data analysis and preprocessing  
- Trained Decision Tree, Random Forest, and Naive Bayes models  
- Used recall as the main evaluation metric  
- Removed overfitted models with perfect training scores  

## Results

| Model                 | Recall (Train %) | Recall (Test %) |
|-----------------------|------------------|-----------------|
| Decision Tree (Tuned) | 95.24            | 95.56           |
| Random Forest (Tuned) | 97.14            | 97.78           |
| Naive Bayes           | 94.28            | 97.78           |
| Naive Bayes (Tuned)   | 94.28            | 97.78           |

## Conclusion
The tuned Random Forest model was selected as the final model due to its consistent performance on both training and test data.

## Author
Saumya Srivastava
