# ML-model-to-predict-CO2-emission-and-CO2-rating

# 📌 Project Overview
This project explores vehicle fuel consumption and emissions using Machine Learning.
It applies multiple algorithms to build and compare models for predicting CO₂ emissions and CO₂ ratings.

# It includes:
📊 Data Analysis (EDA)
⚠️ Data Leakage Demonstration
🔢 Regression Models (CO₂ Emission Prediction)
🧠 Classification Models (CO₂ Rating Prediction)

# 🎯 Objectives

- Understand impact of vehicle features on emissions
- Compare multiple ML models
- Demonstrate dangers of data leakage
- Build a complete ML workflow

# Data leakage experiment in Linear Regression Model

I explored how improper feature selection can lead to misleading model performance.
Example:
- Including highly correlated features like fuel consumption led to an inflated R² (~0.99)
- Removing leakage resulted in a more realistic performance (~0.79)

This helped me understand the importance of:
✔ Proper feature selection  
✔ Avoiding target leakage  
✔ Building reliable ML models

| Model Type      | R² Score |
| --------------- | -------- |
| With Leakage    | ~0.99    |
| Without Leakage | ~0.79    |

# 🔢 Regression Task
Target: CO₂ Emissions

Models:
- Linear Regression
- more will be added...

# 🧠 Classification Task

Target: CO₂ Rating  

Model Used:
- Logistic Regression

# 📊 Regression Results
In Linear Model: 
- MSE: 849.0471690144913
- MAE: 22.642148528453063
- R2 SCORE: 0.7941718542845437
- RMSE: 29.138413975618015
- 
# 📊 Classification Results (Logistic Regression)
- Accuracy: 0.88

- Confusion Matrix:
                    [[50  8]
                    [ 7 65]]

- Classification Report:
         - Precision: ~0.88 - 0.89  
         - Recall: ~0.86 - 0.90  
         - F1-score: ~0.87 - 0.90  

- Log Loss: 0.2554
- 
# 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
 
# 👨‍💻 Author
Emon Sen
CSE Student | Future Data Scientist

