# 🏠 Ames Housing Price Prediction

A Machine Learning project for predicting house prices using the Ames Housing dataset.

## 📌 Project Overview

This project aims to build a Machine Learning model that predicts house prices based on different housing features such as:

- Overall Quality
- Living Area
- Garage Area
- Number of Rooms
- Year Built
- Total Basement Area
- And other house features



## 🎯steps

- Clean and preprocess the dataset
- Handle missing values
- Perform exploratory data analysis (EDA)
- Select and engineer useful features
- Train regression models
- Evaluate model performance
- Save the final trained model
- Deploy the model on streamlit

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Machine Learning Workflow

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Feature Selection
7. Data Preprocessing
8. Model Training
9. Model Evaluation
10. Model Saving

## 🤖 Models Used

The project uses regression models such as:

- Linear Regression
- Polynomial Regression
- Lasso Regression

## 📊 Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- finally result i get :
      ==================================================
      ======================Train========================
      Mean Squared Error (MSE): 357567880.6465379
      Root Mean Squared Error (RMSE): 18909.465371779763
      Mean Absolute Error (MAE): 12131.619691226915
      R-squared (R2): 0.9400511592861596
      ==================================================
      ======================Test========================
      Mean Squared Error (MSE): 797194338.1158139
      Root Mean Squared Error (RMSE): 28234.630121816965
      Mean Absolute Error (MAE): 17032.055352762654
      R-squared (R2): 0.8960677399392949

## 📁 Project Structure

```text
Predict-Price-Ames-Housing/
│
├── data/
│   └── train.csv
│
├── notebooks/
│   └── Ames_Housing_Prediction.ipynb
│
├── model/
│   └── model.joblib
│
├── README.md
└── requirements.txt
