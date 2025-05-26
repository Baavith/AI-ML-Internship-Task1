# AI-ML-Internship-Task1
Data Cleaning &amp; Preprocessing Task for AI/ML Internship
# Heart Disease Prediction Project

![Heart Disease Prediction](assets/correlation_matrix.png)

## Overview
This project aims to predict the presence of heart disease in patients using the UCI Heart Disease dataset. The project includes exploratory data analysis, data preprocessing, model building with Random Forest, hyperparameter tuning, and evaluation.

## Dataset
The dataset used is the Heart Disease UCI dataset containing 920 instances with 14 attributes including:
- Demographic: age, sex
- Medical: chest pain type, resting blood pressure, cholesterol levels, etc.
- Target: presence of heart disease (0 = no, 1 = yes)

## Project Structure
heart-disease-prediction/
│
├── notebooks/ # Jupyter notebooks
├── data/ # Dataset storage
├── assets/ # Visualizations and images
├── README.md # Project documentation
└── requirements.txt # Python dependencies
## Updated requirements.txt
numpy==1.21.5
pandas==1.3.5
scikit-learn==1.0.2
matplotlib==3.5.1
seaborn==0.11.2
jupyter==1.0.0


## Key Improvements for the Given Dataset

1. **Data Preprocessing**:
   - Dropped unnecessary columns ('id', 'dataset')
   - Converted the target variable 'num' to binary (0/1)
   - Handled missing values with forward and backward filling
   - Encoded categorical variables using LabelEncoder

2. **Feature Engineering**:
   - Kept all relevant medical features
   - Standardized numerical features

3. **Model Deployment Preparation**:
   - Saved the scaler and label encoders for consistent preprocessing
   - Saved column names for reference during inference

4. **Documentation**:
   - Updated README to reflect the specific dataset characteristics
   - Included instructions for reproducing results

This solution provides a complete end-to-end workflow for heart disease prediction using the provided dataset, with all necessary components for GitHub deployment and reproducibility.
