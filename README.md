# Churn Prediction for Video Streaming Service

## Overview
This project focuses on predicting customer churn for a video streaming service using a machine learning model. The goal is to identify customers at risk of canceling their subscriptions to reduce churn.

## Dataset
- **Train.csv**: Contains historical data of customer subscriptions and the target variable `Churn`.
- **Test.csv**: Contains similar data without the target variable, used for making predictions.

## Approach
1. **Data Preprocessing**: Categorical features were encoded, and numerical features were normalized.
2. **Model Training**: A Random Forest model was trained to predict churn.
3. **Evaluation**: The model achieved a validation AUC of 0.73.
4. **Prediction**: Predictions were made on the test dataset and saved for submission.

## Results
The model helps prioritize customer retention efforts by predicting the likelihood of churn, potentially reducing churn rates and increasing revenue.

## How to Run
1. Clone the repository: `git clone https://github.com/yourusername/churn-prediction-project.git`
2. Navigate to the project directory.
3. Run the Jupyter notebook or script to reproduce the results.

## Author
[Your Name]
