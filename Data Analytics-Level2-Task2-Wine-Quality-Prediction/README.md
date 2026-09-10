# Wine Quality Prediction using Machine Learning

## Project Overview

In this project, machine learning classification models were developed to predict wine quality categories based on the chemical properties of wine.

The wine quality was classified into three categories:

- Low
- Medium
- High

Three classification models were trained and evaluated:

- Random Forest
- SGD Classifier
- Support Vector Classifier (SVC)

The performance of the models was compared using accuracy and F1-score to identify the most suitable model.

---

## Objective

The main objectives of this project are:

- Analyze wine quality data.
- Prepare the dataset for machine learning.
- Predict wine quality categories.
- Train multiple classification models.
- Compare model performance.
- Identify the best-performing model.
- Understand the important chemical features affecting wine quality.
- Provide business recommendations based on the results.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Models

The following classification models were trained:

### 1. Random Forest

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to make predictions.

### 2. SGD Classifier

SGD Classifier is a linear classification algorithm that uses Stochastic Gradient Descent for model training.

### 3. Support Vector Classifier (SVC)

SVC is a supervised machine learning algorithm used for classification by finding an optimal decision boundary between classes.

---

## Model Performance

| Model | Accuracy | Weighted F1-Score |
|---|---:|---:|
| Random Forest | 86.0% | 0.841 |
| SVC | 84.3% | 0.803 |
| SGD Classifier | 82.1% | - |

Random Forest achieved the best overall performance among the three tested models.

---

## Best Model

**Random Forest** was selected as the best-performing model.

It achieved:

- **Accuracy:** 86.0%
- **Weighted F1-Score:** 0.841

Random Forest also provides feature importance values, which can help understand which chemical properties contribute most to wine quality prediction.

Therefore, Random Forest is the most suitable model among the tested models for this dataset.

---

## Class Imbalance

The dataset contains class imbalance, with fewer Low and High quality wines compared with Medium quality wines.

This imbalance may affect the model's ability to predict the underrepresented categories accurately.

Possible improvements include:

- Applying class balancing techniques.
- Collecting more samples for underrepresented categories.
- Using appropriate sampling techniques.
- Monitoring model performance across individual classes.

---

## Business Recommendations

### 1. Use Random Forest

Use Random Forest as the preferred model for predicting wine quality categories because it achieved the highest overall performance.

### 2. Focus on Important Chemical Features

Analyze the chemical features identified as important by the Random Forest model to better understand the factors that contribute to wine quality.

### 3. Collect More Data

Collect additional samples for Low and High quality wine categories to improve the representation of underrepresented classes.

### 4. Monitor Model Performance

Regularly evaluate the model when new wine-quality data becomes available to ensure that prediction performance remains reliable.

---

## Conclusion

This project demonstrates the use of machine learning classification techniques for wine quality prediction.

Among the three tested models, **Random Forest achieved the highest accuracy of 86.0% and a weighted F1-score of 0.841**.

Therefore, Random Forest is the preferred model for this dataset. However, the class imbalance should be considered before production deployment.

Additional data collection and class-balancing techniques could further improve the model's ability to predict underrepresented wine quality categories.

---

## Project Files

- `README.md` – Project documentation
- `Wine_Quality_Prediction.ipynb` – Complete Jupyter Notebook containing the analysis, preprocessing, model training, and evaluation.
- Charts/visualizations – Generated model evaluation and analysis outputs.

### Dataset Note

The dataset used for this project is not included in the repository if its file size exceeds GitHub's upload limit. The analysis was performed using the original dataset locally.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Classification
- Random Forest
- SGD Classifier
- Support Vector Classifier
- Model Evaluation
- Feature Importance Analysis
- Data Visualization
- Business Recommendations


**Author: Sadha A**
