# ⚽ Football Player Market Value Prediction

This project focuses on predicting the **market value of professional football players** from Europe’s top five leagues using machine learning algorithms with **PySpark**. The analysis includes data cleaning, feature engineering, exploratory data analysis, and model training using both linear and ensemble-based regression techniques.

## 📊 Dataset

- **Source**: [Kaggle - Predicting the Market Value of Football Players](https://www.kaggle.com/datasets/jonascarette/predicting-the-market-value-of-soccer-players)

## 🧠 Techniques Used

- **Data Cleaning**:
  - Removal of irrelevant or incorrect columns (e.g. wrong league labels).
  - Joining with external dataset to fix league information.
- **EDA**:
  - Identifying missing values
  - League/player distributions
- **Feature Engineering**:
  - String indexing
  - One-hot encoding
  - Vector assembly & standardization
- **Modeling**:
  - `LinearRegression` using Spark MLlib
  - `RandomForestRegressor` using Spark MLlib
- **Evaluation**:
  - Model performance metrics (RMSE, R²)
