# Heart Disease Prediction Project

This is my first machine learning project focused on predicting heart disease. In this project, I have developed a machine learning model to predict the likelihood of a person having heart disease based on various medical attributes.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Methods](#methods)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
Heart disease is a critical health issue affecting millions of people worldwide. Early detection and prediction of heart disease can be life-saving. This project aims to leverage machine learning techniques to predict the risk of heart disease based on patient data.

## Data
I used the Heart Disease Dataset. The dataset consists of 1026 samples and 14 features.

## Methods
I employed several machine learning algorithms to build predictive models for heart disease. The following are the steps I followed:

1. **CatBoost**
   - Accuracy: 98.54%
   - MSE: 0.0146
   - RMSE: 0.12097
   - Precision: 100.0%
   - Recall: 97.09%
   - F1 Score: 98.52%
   - Negative Precision: 68.63%
   - Negative Recall: 70.0%
   - Negative F1 Score: 69.31%

2. **Logistic Regression**
   - Accuracy: 81.46%
   - MAE: 0.0146
   - RMSE: 0.12097
   - Precision: 77.31%
   - Recall: 89.32%
   - F1 Score: 82.88%
   - Negative Precision: 73.53%
   - Negative Recall: 87.21%
   - Negative F1 Score: 79.79%

3. **Gaussian Naive Bayes**
   - Accuracy: 78.10%
   - MAE: 0.0146
   - RMSE: 0.12097
   - Precision: 75.41%
   - Recall: 89.32%
   - F1 Score: 81.78%
   - Negative Precision: 68.63%
   - Negative Recall: 70.0%
   - Negative F1 Score: 69.31%

4. **SVM**
   - Accuracy: 95.49%
   - MSE: 0.0146
   - RMSE: 0.12097
   - Negative Precision: 73.53%
   - Negative Recall: 87.21%
   - Negative F1 Score: 79.79%

5. **Decision Trees**
   - Accuracy: 98.05%
   - Precision: 100.0%
   - Recall: 97.09%
   - F1 Score: 98.52%
   - Negative Precision: 68.63%
   - Negative Recall: 70.0%
   - Negative F1 Score: 69.31%

6. **Random Forests**
   - Accuracy: 98.41%
   - Precision: 100.0%
   - Recall: 97.09%
   - F1 Score: 98.52%
   - Negative Precision: 68.63%
   - Negative Recall: 70.0%
   - Negative F1 Score: 69.31%

7. **K-Nearest Neighbors - KNN**
   - Accuracy: 97.07%
   - Precision: 100.0%
   - Recall: 97.09%
   - F1 Score: 98.52%
   - Negative Precision: 68.63%
   - Negative Recall: 70.0%
   - Negative F1 Score: 69.31%

8. **Naive Bayes**
   - Accuracy: 75.73%
   - Precision: 69.52%
   - Recall: 70.87%
   - F1 Score: 70.19%
   - Negative Precision: 68.63%
   - Negative Recall: 70.0%
   - Negative F1 Score: 69.31%

## Results
Out of the models tested, five models achieved satisfactory results with high accuracy, precision, and recall. These models can be considered for further deployment in real-world applications. However, three models did not perform as expected and require further optimization.

## Conclusion
In conclusion, this project demonstrates the potential of machine learning in predicting heart disease based on patient data. While five models provided promising results, further optimization is needed for the three underperforming models. This project serves as a foundation for future improvements and research in the field of heart disease prediction.

