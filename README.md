# Heart Disease Prediction Using Machine Learning

Predicting heart disease early is crucial for prevention and treatment. This project develops a **machine learning pipeline** to predict the **probability of heart disease** in patients based on their health and lifestyle data. The system uses multiple ML models and handles class imbalance using **SMOTE** for improved prediction accuracy.

---

## 🚀 Project Highlights

- **Objective:** Predict the possibility of heart disease from patient data.
- **Data Source:** Patient dataset with medical and lifestyle features.
- **Target Variable:** `Heart Disease Status` (Yes/No)
- **Challenges Addressed:**
  - Imbalanced classes (Yes = 20%, No = 80%)
  - Mixed data types (numeric + categorical)
  - Missing values handling
  - Feature scaling & encoding

---

## 📊 Features Used

| Feature | Type |
|---------|------|
| Age | Numeric |
| Blood Pressure | Numeric |
| Cholesterol Level | Numeric |
| BMI | Numeric |
| Sleep Hours | Numeric |
| Triglyceride Level | Numeric |
| Fasting Blood Sugar | Numeric |
| CRP Level | Numeric |
| Homocysteine Level | Numeric |
| Gender | Categorical |
| Exercise Habits | Categorical |
| Smoking | Categorical |
| Family Heart Disease | Categorical |
| Diabetes | Categorical |
| High Blood Pressure | Categorical |
| Low HDL Cholesterol | Categorical |
| High LDL Cholesterol | Categorical |
| Alcohol Consumption | Categorical |
| Stress Level | Categorical |
| Sugar Consumption | Categorical |

---

## 🛠️ Models Used

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Support Vector Machine (SVM)**
4. **XGBoost Classifier** (Best performing model)

> SMOTE was used to balance the dataset before training.

---

