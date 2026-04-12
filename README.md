# ML-model-to-predict-CO2-emission-and-CO2-rating

# 📌 Project Overview
This project explores vehicle fuel consumption and emissions using Machine Learning.
It applies multiple algorithms to build and compare models for predicting CO₂ emissions and CO₂ ratings.

# It includes:
- 📊 Data Analysis (EDA)
- ⚠️ Data Leakage Demonstration
- 🔢 Regression Models (CO₂ Emission Prediction)
- 🧠 Classification Models (CO₂ Rating Prediction)

# 🎯 Objectives

- Understand impact of vehicle features on emissions
- Compare multiple ML models
- Demonstrate dangers of data leakage
- Build a complete ML workflow

# 🔢 Regression Task
Target: CO₂ Emissions

Models:
- Linear Regression
- more will be added...

# Data leakage experiment in Linear Regression Model

I explored how improper feature selection can lead to misleading model performance.
Example:
- Including highly correlated features like fuel consumption led to an inflated R² (~0.99)
- Removing leakage resulted in a more realistic performance (~0.79)

This helped me understand the importance of:
✔ Proper feature selection  
✔ Avoiding target leakage  
✔ Building reliable ML models

# 📊 Regression Results
Metric   | With Data Leakage |	Without Data Leakage
---------|-------------------|------------------------
R² Score | 0.9947	           |  0.7942
MSE	     | 21.82	           |  849.05
MAE	     | 1.57	             |  22.64
RMSE	   | 4.67	             |  29.14

# 🧠 Classification Task

Target: CO₂ Rating  

Model Used:
- Logistic Regression
- KNeighbors Classifier
- Decision Tree Classifier
- SVM


# 📊 Classification Results

Model	              | Accuracy | Precision (Class 1) | Recall (Class 1) | F1-Score (Class 1)
--------------------|----------|---------------------|------------------|----------------------
Logistic Regression	|  88.4%	 |       0.89          | 	   0.90	        |    0.90
Decision Tree       |	 86.2%	 |       0.92          | 	   0.82	        |    0.87
SVM (RBF Kernel)	  |  84.6%	 |       0.92          | 	   0.79	        |    0.85
KNN (k=5)	          |  83.8%	 |       0.81	         |     0.93	        |    0.86
Naive Bayes	        |  67.7%   |       0.97	         |     0.43         |    0.60


📌 Insight:
-
-
📊 Comparison Insight

-
-


# 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
 
# 👨‍💻 Author
Emon Sen
CSE Student | Future Data Scientist

