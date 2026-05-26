# Car Selling Price Prediction

A machine learning project focused on predicting used car selling prices using regression models and real-world vehicle market data.

## Project Overview

This project demonstrates an end-to-end machine learning workflow for car price prediction, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding
- Feature scaling
- Regression modeling
- Model evaluation
- Explainable AI (XAI)

The project compares multiple regression algorithms and evaluates their performance using the R² metric.

---

## Dataset Features

The dataset includes information such as:

- Car name
- Manufacturing year
- Present price
- Kilometers driven
- Fuel type
- Seller type
- Transmission type
- Ownership history

Target variable:

- `Selling_Price`

---

## Workflow

### 1. Data Exploration
- Inspected dataset structure and feature distributions
- Checked for missing values
- Analyzed categorical feature distributions

### 2. Data Preprocessing
- Encoded categorical variables using One-Hot Encoding
- Removed unnecessary features
- Split the dataset into training and testing sets
- Applied feature scaling using StandardScaler

### 3. Model Training
Implemented and compared:
- Linear Regression
- Lasso Regression (L1 Regularization)

### 4. Model Evaluation
Evaluated models using the R² score.

#### Results
| Model | R² Score |
|---|---|
| Linear Regression | 0.83 |
| Lasso Regression | 0.90 |

### 5. Explainable AI (XAI)
Used SHAP (SHapley Additive exPlanations) to:
- Interpret model predictions
- Analyze feature importance
- Improve model transparency

---

## Visualizations

The project includes:
- Prediction vs Actual value plots
- SHAP feature importance visualization
- Exploratory data analysis visualizations

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP
- Jupyter Notebook

---

## Key Skills Demonstrated

- Machine Learning Pipelines
- Regression Modeling
- Feature Engineering
- Data Preprocessing
- One-Hot Encoding
- Feature Scaling
- Model Evaluation
- Explainable AI (XAI)
- Data Visualization

---

## Future Improvements

Possible future enhancements include:
- Hyperparameter tuning
- Cross-validation
- Trying advanced ensemble models
- Deploying the model with FastAPI or Streamlit
