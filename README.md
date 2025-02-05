# Iris ML Model Comparison

This project explores various machine learning models applied to the Iris dataset, focusing on both classification and regression approaches. While regression models are not ideal for this classification problem, they have been included for experimentation and learning purposes. The goal was to try out different models and understand their behavior on this well-known dataset.

## Dataset Overview
The Iris dataset consists of 150 samples of iris flowers, divided into three classes (setosa, versicolor, and virginica). Each sample has four features: sepal length, sepal width, petal length, and petal width.

## Models Implemented
- **KNN Classification**
- **KNN Regression**
- **Logistic Regression**
- **Linear Regression**
- **Decision Tree Classification**
- **Decision Tree Regression**
- **Support Vector Classification (SVC)**
- **Support Vector Regression (SVR)**

## Model Performance
- **Classification Models** (KNN Classification, Decision Tree Classification, SVC):
  - Achieved an **F1 Score of 1.0** on the classification task, indicating perfect classification performance on this dataset.
  
- **Regression Models** (KNN Regression, Linear Regression, Decision Tree Regression, SVR):
  - Although regression models are not suitable for this classification problem, they were implemented for experimentation.
  - All regression models, except KNN Regression, achieved an **R² Score of 1.0**, indicating perfect fit for the given data, though this is expected due to the simple nature of the dataset.

## Why Regression Models?
Although the Iris dataset is a classification problem, I chose to implement regression models (KNN Regression, Linear Regression, Decision Tree Regression, SVR) to experiment with them and gain exposure to a variety of algorithms, even though they are not the appropriate choice for this type of task.
## Performance Summary

Here's a quick overview of the performance of each model:

| Model                             | Accuracy (Classification) | Precision (Classification) | F1 Score (Classification) | MAE (Regression) | MSE (Regression) | R² Score (Regression) | RMSE (Regression) |
|-----------------------------------|---------------------------|----------------------------|---------------------------|------------------|------------------|-----------------------|-------------------|
| KNN Classification                | 1.0                       | 1.0                        | 1.0                       | N/A              | N/A              | N/A                   | N/A               |
| KNN Regression                    | N/A                       | N/A                        | N/A                       | 0.03             | 0.01             | 0.99                  | 0.09              |
| Logistic Regression               | N/A                       | N/A                        | N/A                       | 0.0              | 0.0              | 1.0                   | 0.0               |
| Linear Regression                 | N/A                       | N/A                        | N/A                       | 0.0              | 0.0              | 1.0                   | 0.0               |
| Decision Tree Classification      | 1.0                       | 1.0                        | 1.0                       | N/A              | N/A              | N/A                   | N/A               |
| Decision Tree Regression          | N/A                       | N/A                        | N/A                       | 0.0              | 0.0              | 1.0                   | 0.0               |
| Support Vector Classification (SVC)| 1.0                       | 1.0                        | 1.0                       | N/A              | N/A              | N/A                   | N/A               |
| Support Vector Regression (SVR)   | N/A                       | N/A                        | N/A                       | 0.0              | 0.0              | 1.0                   | 0.0               |

## Conclusion

This project allowed me to compare and experiment with different machine learning models, both classification and regression, on the Iris dataset. The results show that classification models performed perfectly on the classification task, with **accuracy**, **precision**, and **F1 Score** all reaching a perfect value of **1.0**.

For the regression models, despite being not suited for the classification task, they achieved perfect **R² Scores** of **1.0**. However, metrics such as **MAE**, **MSE**, and **RMSE** indicate that these models fitted the data perfectly, which is expected given the simplicity of the dataset.

### Key Takeaways:
- **Classification models** (KNN Classification, Logistic Regression, Decision Trees, SVC) are the appropriate choice for the Iris dataset. They showed perfect performance with **accuracy**, **precision**, and **F1 Score**.
- **Regression models** (KNN Regression, Linear Regression, Decision Tree Regression, SVR) were implemented for learning purposes but are not suitable for classification tasks.
- The project provided valuable hands-on experience with **scikit-learn**, exposing me to a wide range of machine learning models and evaluation metrics.
 appropriate choice for the Iris dataset.
- **Regression models** were implemented for learning and comparison purposes, but they are not suitable for classification problems like the Iris dataset.
- This project provided valuable hands-on experience with **scikit-learn** and a variety of machine learning algorithms.

