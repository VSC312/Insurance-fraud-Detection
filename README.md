# Insurance Fraud Detection (Fraud Detection, Machine Learning, Classification, Ensemble)

## Project Overview
This project focuses on detecting fraudulent claims in the insurance industry using various machine learning techniques. By leveraging multiple classifiers and ensemble methods, we aim to improve the detection of fraudulent activities and minimize losses for insurance companies.

## Dataset
The dataset consists of insurance claim data where the target variable indicates whether a claim is fraudulent or not. It includes features such as claim amount, claim type, and customer details.[Link](https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data)

## Technologies Used
- **Python**: Core programming language used for data analysis and machine learning.
- **Pandas & NumPy**: For data manipulation and cleaning.
- **Scikit-learn**: Used for implementing various machine learning models.
- **CatBoost, LightGBM, XGBoost**: Advanced gradient boosting algorithms.
- **Matplotlib & Seaborn**: Visualization tools for data exploration.


## Machine Learning Models
We used a variety of machine learning models to classify fraudulent claims:
- **Support Vector Classifier (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest**
- **AdaBoost**
- **XGBoost**
- **LightGBM**
- **CatBoost**
- **Extra Trees Classifier**
- **Gradient Boosting Classifier**
- **Stochastic Gradient Boosting (SGB)**
- **Voting Classifier** (Ensemble of models)

## Evaluation Metrics
The performance of each model was evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**

## Results
The **Voting Classifier** achieved the highest accuracy of **77%** on the test data, effectively identifying fraudulent claims while minimizing false positives.

## Conclusion
This project successfully demonstrates the application of machine learning in detecting fraud in the insurance industry. By experimenting with multiple models and ensemble techniques, we improved the ability to predict fraudulent claims and support insurance companies in mitigating financial risk.


