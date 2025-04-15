# Machine-Learning-Application-in-Oil-Gas

This project applies machine learning to analyze and predict reservoir characteristics using a combination of geological, geophysical, and production data. The aim is to assist decision-making in the upstream oil and gas sector by building accurate regression models to estimate reservoir properties such as porosity and permeability.

## 📂 Project Overview

- **Domain:** Oil & Gas (Reservoir Characterization)
- **Goal:** Predict porosity using well log features
- **Approach:** Supervised learning (Regression)
- **Dataset:** Synthetic reservoir dataset with well log measurements
- **Modeling Techniques:** 
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor

## 🔍 Key Features

- Exploratory Data Analysis (EDA) to understand feature relationships and detect outliers
- Feature engineering including correlation filtering and one-hot encoding
- Data normalization using MinMaxScaler
- Train-test split for performance evaluation
- Multiple regression models with performance comparison
- Model evaluation metrics: MAE, MSE, RMSE, R²

## 🧪 Machine Learning Models

| Model               | MAE     | RMSE    | R² Score |
|--------------------|---------|---------|----------|
| Linear Regression  | ~0.050  | ~0.066  | ~0.84    |
| Random Forest      | ~0.037  | ~0.050  | ~0.91    |
| XGBoost            | ~0.035  | ~0.049  | ~0.92    |

> 📌 **XGBoost Regressor** delivered the best performance and was chosen as the final model.

## 📈 Visualizations

- Heatmaps for correlation analysis
- Feature importance plots for model interpretability
- Actual vs. Predicted scatter plots

## 🛠️ Technologies Used

- Python 3
- pandas, NumPy
- scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## 🚀 Getting Started

### Prerequisites

Make sure the following libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
