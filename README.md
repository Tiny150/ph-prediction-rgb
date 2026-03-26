# ph-prediction-rgb
Prediction of pH using RGB data and machine learning models
# 📊 Prediction of pH using RGB Data

## 🌍 Context
Monitoring water quality is essential for environmental sustainability. However, traditional laboratory measurements of pH can be costly and time-consuming.

This project explores a low-cost alternative: predicting pH values directly from RGB color data.

---

## 🎯 Objective
The goal is to develop machine learning models capable of estimating pH values using RGB inputs.

---

## 📂 Dataset
The dataset (`ph-data.csv`) contains:
- Red (R)
- Green (G)
- Blue (B)
- pH (target variable)

---

## 🔍 Data Analysis
- Checking missing values
- Detecting duplicates
- Statistical summary
- Visualization:
  - Scatter plots:
    - R vs pH
    - G vs pH
    - B vs pH

---

## ⚙️ Methodology

### 1. Preprocessing
- Renaming columns
- Feature selection (R, G, B → pH)

### 2. Train/Test Split
- 80% training
- 20% testing

### 3. Models Used
- Linear Regression
- Random Forest Regressor

---

## 📈 Model Evaluation

Models are evaluated using:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 🤖 Prediction Function

A custom function allows prediction from new RGB values:

```python
predict_ph((R, G, B))
