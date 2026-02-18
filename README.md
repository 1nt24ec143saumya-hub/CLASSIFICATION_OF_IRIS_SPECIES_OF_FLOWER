# 🌸 Iris Species Prediction using Machine Learning

![Iris Dataset Banner](https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification-1024x367.png)

<sub>Image Source: https://www.embedded-robotics.com/wp-content/uploads/2022/01/Iris-Dataset-Classification-1024x367.png</sub>

---

## 📌 Overview

This project focuses on developing a supervised machine learning model capable of identifying iris flower species based on their physical measurements.

The classification task involves three species:

- **Setosa**
- **Versicolor**
- **Virginica**

Each species can be distinguished using four measurable attributes:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

---

## 🎯 Project Objective

The primary goal of this project is to build and evaluate classification models that accurately predict the species of an iris flower using numerical feature inputs.

By applying machine learning techniques, this project demonstrates how structured biological data can be used to generate reliable predictive models.

---

## 📊 Dataset Description

The dataset contains labeled samples of iris flowers. Each record consists of:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  
- Species (Target Variable)

The four numerical features serve as predictors, while the species label represents the output class.

---

## 🛠 Methodology

The following steps were performed:

### 1. Exploratory Data Analysis (EDA)
- Examined feature distributions  
- Studied relationships between variables  
- Analyzed class separability  

### 2. Data Preparation
- Checked for missing values  
- Ensured data consistency  
- Prepared the dataset for model training  

### 3. Model Development
The following classification algorithms were implemented:

- Decision Tree  
- Random Forest  
- Naive Bayes  

### 4. Model Evaluation
- **Recall** was selected as the primary evaluation metric.  
- Overfitted models (with 100% training performance) were excluded from final comparison to ensure realistic evaluation.

---

## 📈 Model Performance

| S.No | Model                   | Recall (Train %) | Recall (Test %) |
|------|-------------------------|------------------|-----------------|
| 1    | Decision Tree (Tuned)   | 95.24            | 95.56           |
| 2    | Random Forest (Tuned)   | 97.14            | 97.78           |
| 3    | Naive Bayes             | 94.28            | 97.78           |
| 4    | Naive Bayes (Tuned)     | 94.28            | 97.78           |

---

## 🏆 Final Model Selection

The **Tuned Random Forest** classifier was selected as the final model because it demonstrated:

- Strong generalization performance  
- High recall on unseen data  
- Stable results across training and testing datasets  

---

## 🔍 Key Observations

- The Setosa species is distinctly separable from the other two species.
- Petal-related features play a significant role in classification.
- Ensemble methods provide robust and consistent results.

---

## 🚀 Future Scope

Possible enhancements include:

- Advanced hyperparameter optimization  
- Testing additional ensemble algorithms  
- Detailed feature importance visualization  
- Deployment as a web-based application  

---

## 🌱 Applications

This classification model can support:

- Botanical research  
- Environmental monitoring  
- Agricultural analysis  
- Educational demonstrations of supervised learning  

---

## 👩‍💻 Author

**Saumya Srivastava**

---

## 📚 Reference

- Oasis Infobyte
