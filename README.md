# Iris Flower Classification


![Uploading Iris-Dataset-Classification-1024x367.png…]()

This project builds a machine learning model to classify iris flowers into three species: Setosa, Versicolor, and Virginica.

The classification is based on four features:
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

## Objective

To train and evaluate classification models that can accurately predict the species of an iris flower using these measurements.

## Approach

- Performed basic exploratory data analysis.
- Cleaned and prepared the dataset.
- Trained multiple models including Decision Tree, Random Forest, and Naive Bayes.
- Used **recall** as the primary evaluation metric.
- Excluded overfitted models with perfect training scores.

## Results

| Model                  | Recall (Train %) | Recall (Test %) |
|------------------------|------------------|-----------------|
| Decision Tree (Tuned)  | 95.24            | 95.56           |
| Random Forest (Tuned)  | 97.14            | 97.78           |
| Naive Bayes            | 94.28            | 97.78           |
| Naive Bayes (Tuned)    | 94.28            | 97.78           |

## Conclusion

The tuned Random Forest model was selected as the final model due to its strong and consistent performance on both training and test data.

## Author

Saumya Srivastava
