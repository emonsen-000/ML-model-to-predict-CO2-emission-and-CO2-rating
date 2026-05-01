# 🚗 CO2 Emission & CO2 Rating Prediction using Machine Learning

This project focuses on predicting **vehicle CO2 emissions** using regression models and **CO2 ratings** using classification models.  
The project was built as a learning-based machine learning practice project to understand model behavior, compare algorithm performance, and apply proper evaluation techniques.

---

## 📌 Project Objectives

- Predict **CO2 Emission** of vehicles using regression algorithms
- Predict **CO2 Rating** using classification algorithms
- Compare multiple ML models
- Perform **hyperparameter tuning** using GridSearchCV
- Understand model evaluation metrics
- Detect and fix **data leakage issues**

---

## 📂 Project Files

- `CO2_Emission_Prediction.ipynb` → Regression models for CO2 emission prediction
- `CO2_Rating_Prediction.ipynb` → Classification models for CO2 rating prediction

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Regression Models (CO2 Emission Prediction)

Regression models were evaluated using:
- **MSE (Mean Squared Error)**
- **MAE (Mean Absolute Error)**
- **R² Score**

| Model | MSE | MAE | R² Score |
|------|-----|-----|----------|
| Linear Regression (with data leakage) | 21.82 | 1.54 | 0.99 |
| Linear Regression (without data leakage) | 783.81 | 22.12 | 0.81 |
| KNN Regressor | 923.66 | 21.53 | 0.77 |
| Decision Tree Regressor | 804.37 | 19.02 | 0.80 |
| Random Forest Regressor | 574.39 | 17.92 | 0.86 |

### Key Insights
- Initially, Linear Regression achieved unrealistically high performance due to **data leakage**.
- After removing leakage, performance dropped significantly, showing realistic results.
- **Random Forest Regressor** performed best with:
  - **MSE:** 574.39
  - **MAE:** 17.92
  - **R² Score:** 0.86
- Tree-based models performed better, indicating non-linear relationships in the dataset.

---

## 🤖 Classification Models (CO2 Rating Prediction)

Classification models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

| Model | Accuracy |
|------|----------|
| Logistic Regression | ~88% |
| KNN | 82.3% |
| Decision Tree | **89.2%** |
| Naive Bayes | 65.2% |
| Random Forest | 85.4% |
| SVM | 86.1% |

### Best Model: Decision Tree Classifier
- **Accuracy:** 89.2%
- Balanced precision across both classes (~89%)
- F1-score:
  - Class 0: 0.88
  - Class 1: 0.90

### Key Insights
- **Decision Tree** gave the best overall classification performance.
- **Logistic Regression** provided stable and interpretable results.
- **SVM** showed class imbalance behavior, tending to predict class 0 more often.
- **Naive Bayes** underperformed due to feature independence assumptions.

---

## 🔍 Learning Outcomes

Through this project, I learned:

- Data preprocessing and feature selection
- Train-test splitting
- Regression and classification workflows
- Hyperparameter tuning with **GridSearchCV**
- Model comparison and evaluation
- Detecting and resolving **data leakage**
- Interpreting confusion matrices and performance metrics


---

## 👨‍💻 Author

**Emon Sen**  
CSE Undergraduate | Aspiring Data Scientist  
