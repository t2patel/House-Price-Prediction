# 🏠 House Price Prediction

House Price Prediction is a Machine Learning regression project that predicts house prices based on different housing and area-related features.

## 📌 Project Overview

The goal of this project is to build a Machine Learning model that can predict the price of a house using features such as:

- Average Area Income
- Average Area House Age
- Average Area Number of Rooms
- Average Area Number of Bedrooms
- Area Population

The project includes data preprocessing, exploratory data analysis, model training, and model evaluation.

## 🎯 Objective

The main objective of this project is to:

- Understand and preprocess housing data
- Perform Exploratory Data Analysis (EDA)
- Identify relationships between features and house prices
- Train Machine Learning regression models
- Compare model performance
- Select the best-performing model for house price prediction

## 📊 Dataset

The dataset used in this project is `USA_Housing.csv`.

### Features

| Feature | Description |
|---|---|
| Avg. Area Income | Average income of the area |
| Avg. Area House Age | Average house age in the area |
| Avg. Area Number of Rooms | Average number of rooms |
| Avg. Area Number of Bedrooms | Average number of bedrooms |
| Area Population | Population of the area |
| Price | Target variable representing house price |

The `Address` column was removed because it is a text-based feature and is not directly used in the basic numerical prediction model.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Best Model Selection
   ↓
House Price Prediction
