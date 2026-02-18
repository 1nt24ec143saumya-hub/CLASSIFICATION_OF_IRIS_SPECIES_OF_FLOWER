

🌸 Iris Species Prediction using Machine Learning

<img width="1024" height="367" alt="Iris-Dataset-Classification-1024x367" src="https://github.com/user-attachments/assets/91e26eed-b78f-4388-8ac3-9ddadb4878ba" />

Image Source: https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification-1024x367.png



📌 Overview

This project focuses on building a supervised machine learning model that can identify the species of an iris flower based on its physical dimensions. The iris dataset is one of the most well-known datasets in the field of data science and pattern recognition.

The classification task involves distinguishing between three different iris species:
	•	Setosa
	•	Versicolor
	•	Virginica

Each species differs in measurable attributes such as sepal length, sepal width, petal length, and petal width.

⸻

🎯 Project Goal

The main objective of this project is to design and evaluate classification models that can accurately predict the species of an iris flower using numerical feature inputs.

By leveraging machine learning techniques, this project demonstrates how structured biological data can be transformed into predictive insights.

⸻

📊 Dataset Description

The dataset consists of labeled samples of iris flowers. Each record includes:
	•	Sepal Length
	•	Sepal Width
	•	Petal Length
	•	Petal Width
	•	Species Label

These four numerical features act as predictors, while the species serves as the target variable.

⸻

🛠 Approach

The workflow followed in this project includes:
	1.	Exploratory Data Analysis (EDA)
	•	Studied feature distributions
	•	Examined inter-feature relationships
	•	Observed class separability
	2.	Data Preparation
	•	Checked for inconsistencies and missing values
	•	Prepared the dataset for modeling
	3.	Model Building
Multiple classification algorithms were trained and compared:
	•	Decision Tree
	•	Random Forest
	•	Naive Bayes
	4.	Model Evaluation
Recall was selected as the primary evaluation metric to ensure effective class detection performance.
Models showing perfect training scores (indicative of overfitting) were excluded from final consideration.

⸻

📈 Performance Comparison

Below are the refined model results after eliminating overfitted candidates:

S.No	Model	Recall (Train %)	Recall (Test %)
1	Decision Tree (Tuned)	95.24	95.56
2	Random Forest (Tuned)	97.14	97.78
3	Naive Bayes	94.28	97.78
4	Naive Bayes (Tuned)	94.28	97.78


⸻

🏆 Final Model Selection

After comparing performance metrics, the Tuned Random Forest model was selected as the final predictive model due to:
	•	Strong generalization performance
	•	High recall on unseen data
	•	Stability across training and testing datasets

⸻

🔍 Key Insights
	•	Setosa is clearly distinguishable from the other two species.
	•	Petal-related features contribute significantly to classification.
	•	Ensemble methods (like Random Forest) provide robust performance for this dataset.

⸻

🚀 Future Enhancements

Potential improvements include:
	•	Hyperparameter optimization using advanced search techniques
	•	Testing additional ensemble models
	•	Visualizing feature importance in greater depth
	•	Deploying the model as a web-based application

⸻

🌱 Real-World Relevance

Automated species classification systems can assist in:
	•	Botanical research
	•	Agricultural studies
	•	Environmental monitoring
	•	Educational demonstrations of classification algorithms

⸻

👩‍💻 Author

Saumya Srivastava

⸻

📚 Reference
	•	Oasis Infobyte

⸻
