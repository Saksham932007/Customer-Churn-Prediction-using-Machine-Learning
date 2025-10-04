# Customer Churn Prediction using Machine Learning

This project predicts customer churn for a telecommunications company using machine learning.

-----

## 📋 Dataset

The project uses the "Telco Customer Churn" dataset, which contains information about 7,043 customers and 21 features. The dataset includes customer demographics, account information, and services they've signed up for. The "Churn" column is the target variable, indicating whether a customer has left the company.

-----

## 🤖 Methodology

The project follows these steps:

1.  **Data Preprocessing and EDA:** The data is cleaned and prepared for modeling. This includes handling missing values, encoding categorical features, and performing exploratory data analysis (EDA) to understand the relationships between different features and customer churn.

2.  **Feature Engineering:** New features are created from existing ones to improve model performance.

3.  **Model Building:** Several machine learning models are trained on the preprocessed data, including:

      * Decision Tree Classifier
      * Random Forest Classifier
      * XGBoost Classifier

4.  **Model Evaluation:** The performance of each model is evaluated using various metrics, such as accuracy, confusion matrix, and classification report.

-----

## 🏆 Results

The models achieved the following accuracies:

  * **Decision Tree:** 72%
  * **Random Forest:** 78%
  * **XGBoost Classifier:** 78%

The Random Forest and XGBoost models performed the best, with an accuracy of 78%.

-----

## 🚀 How to Run

To run this project, you'll need the following libraries:

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn
  * Imbalanced-learn
  * XGBoost
  * Pickle

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost pickle-mixin
```

Then, you can run the Jupyter Notebook `Customer_Churn_Prediction_using_ML.ipynb` to see the code and results.
