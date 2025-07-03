# ML_project_Energy-Efficiency
# 🏡 Project: Energy Efficiency Prediction using Machine Learning

This project focuses on predicting the **Heating Load (HL)** and **Cooling Load (CL)** of buildings using various machine learning models. The dataset comes from the [UCI Energy Efficiency Dataset](https://archive.ics.uci.edu/ml/datasets/Energy+efficiency).

## 🔍 Problem Statement

Given 8 architectural features of buildings (e.g., surface area, glazing area, orientation), the goal is to predict:
- **Heating Load (HL)**
- **Cooling Load (CL)**

## 🧰 Workflow

### 1. Exploratory Data Analysis (EDA)
- Visualized feature distributions and relationships
- Checked correlations and outliers

### 2. Preprocessing
- Standardized features using `StandardScaler`
- Created regression and classification-ready datasets

### 3. Regression Models
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

**Evaluation Metrics:**
- Mean Squared Error (MSE)
- R² Score

### 4. Classification Models
Converted load values to binary labels (High/Low) for classification.

- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  

**Evaluation Metrics:**
- Accuracy
- Confusion Matrix
- Classification Report

### 5. Feature Importance
- Analyzed and selected the top 12 important features
- Improved model performance using selected features

## 🧠 Key Takeaways
- Tree-based models performed best
- Classification simplifies decision-making for energy efficiency ratings
- Feature selection enhances both performance and interpretability

## 📁 Files Included
- `Project On Energy Efficiency.ipynb`: Full implementation
- `README.md`: Project summary and documentation
