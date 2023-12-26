# Breast-Cancer-Diagnosis-Prediction
Breast Cancer Diagnosis Prediction: Sklearn Dataset Exploration and Logistic Regression Modeling
# Breast Cancer Diagnosis Prediction

## Project Overview:
This project utilizes the Sklearn Breast Cancer Wisconsin dataset to build and evaluate a logistic regression model for breast cancer diagnosis. The model's performance is assessed using accuracy and precision metrics. Additionally, predictions are made on new, unseen data.

## Project Steps:
1. **Data Loading and Splitting:**
   - Loaded the Breast Cancer Wisconsin dataset from Sklearn.
   - Split the dataset into features (X) and target variable (y).
   - Performed a train-test split (80-20 split).

2. **Logistic Regression Model Training:**
   - Instantiated and trained a logistic regression model on the training set.
   - Handled convergence warnings by considering the provided recommendations.

3. **Model Performance Evaluation:**
   - Evaluated the model's accuracy and precision on the test set.
   - Accuracy: 93%
   - Precision: 96%

4. **Prediction on New Data:**
   - Made predictions on new, unseen data to showcase the model's application.
   - The model predicted the diagnosis as benign (class 0) for the provided new data.

## Results:
The logistic regression model demonstrates high accuracy (93%) and precision (96%) in diagnosing breast cancer. The predictions on new data further highlight the model's effectiveness in practical applications.

*Note: The convergence warning suggests potential improvements in model convergence, which can be addressed by adjusting the number of iterations or scaling the data.*

This project provides insights into breast cancer diagnosis prediction, emphasizing the model's performance and practical utility.
