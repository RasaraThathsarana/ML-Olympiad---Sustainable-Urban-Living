# Loan Default Prediction Using Feature Engineering

## Overview
Finding a suitable place to live is a crucial decision, significantly impacting your well-being. While online listings provide information, it can be challenging to assess a property's true "habitability" based solely on descriptions. This is where AI can lend a helping hand!

This project is part of the **ML Olympiad - Sustainable Urban Living** competition, where participants leverage Machine Learning techniques to develop a model that predicts the habitability score of a property based on available details. The model aims to contribute to a user-friendly system that empowers individuals to make informed decisions about their living spaces.

### Goal
Develop a machine learning model that predicts the Sustainable Habitability Score of a property based on the provided data.

### Timeline
- **Start**: February 26, 2024
- **Close**: March 31, 2024

### Dataset
The dataset contains various properties from across the United States. Your challenge is to predict the "habitability score" for each property, considering multiple factors that contribute to a comfortable and enjoyable living experience.

### Explainability
Explainability is crucial! Strive to build models that not only predict accurately but also provide understandable insights into the factors influencing habitability scores. This will help users interpret the results and make informed decisions.

### Evaluation
The model's performance is evaluated based on its ability to accurately predict habitability scores. The primary metric for evaluation is the **Root Mean Squared Error (RMSE)**.

## Project Report

### Index
- **Index**: 210170G
- **Name**: W.A.R.T. Fonseka
- **Lab**: 02 – Regression

### Introduction
In this report, I explore various machine learning approaches to find the best prediction model for habitability scores. The report discusses evaluation metrics for regression scenarios and explores optimization techniques for ML models.

### Evaluation Matrices
The following machine learning models were used to evaluate and select the best-performing model:
1. **XGB Regressor**
2. **Random Forest Regressor**
3. **SVR**
4. **Linear Regression**
5. **MLP Regressor**
6. **K Neighbors Regressor**

#### Evaluation Metrics
1. **Root Mean Squared Error (RMSE)**
2. **Mean Absolute Error (MAE)**
3. **Mean Squared Error (MSE)**
4. **R² Score (R2S)**

### Results
- **Best Performing Models**: XGB Regressor and Random Forest Regressor.
- **Final Model**: Averaging Ensemble method, which outperformed single models with an RMSE of 5.85 on the test data.

### Final Thoughts
The report concludes that the Averaging Ensemble model provides the best prediction results for habitability scores. The final model was trained on all available data and demonstrated improved performance compared to other methods.

## Citation
Ashwin Raj, BeyondML. (2024). ML Olympiad - Sustainable Urban Living. Kaggle. [https://kaggle.com/competitions/ml-olympiad-sustainable-urban-living](https://kaggle.com/competitions/ml-olympiad-sustainable-urban-living)

## Additional Resources
- [Google Drive Data Folder](https://drive.google.com/drive/folders/your-folder-id)
- [Feature Engineering Techniques](https://www.example.com/feature-engineering)
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/latest/)
