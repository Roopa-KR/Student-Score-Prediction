# 📊 Logistic Regression Model for Pass Prediction

## 📌 Project Overview

This project implements a **Logistic Regression model** to predict whether a student will **pass or fail** based on:

* Hours Studied 📚
* Attendance 📅

The project demonstrates a complete **Machine Learning pipeline**, including preprocessing, model training, hyperparameter tuning, and evaluation.

---

## 🎯 Objective

To build a classification model that predicts:

* **0 → Fail**
* **1 → Pass**

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Joblib

---

## 📂 Dataset Description

| Feature       | Description                 |
| ------------- | --------------------------- |
| Hours_Studied | Number of hours studied     |
| Attendance    | Attendance percentage       |
| Pass          | Target (0 = Fail, 1 = Pass) |

---

## ⚙️ Workflow

1. **Data Creation**

   * A small dataset is manually created.

2. **Data Splitting**

   * Split into training and testing sets.

3. **Feature Scaling**

   * Applied StandardScaler to normalize feature values.

4. **Model Training**

   * Logistic Regression model is used.

5. **Hyperparameter Tuning**

   * GridSearchCV is used to find the best parameters.

6. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

7. **Model Saving**

   * Model and scaler saved using Joblib.

8. **Prediction**

   * New data prediction supported.

---

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas numpy scikit-learn joblib

# Run the Python script / notebook
```

---

## 📊 Example Prediction

Input:

```
Hours Studied = 6  
Attendance = 72
```

Output:

```
Prediction → 1 (Pass)
```

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score

---

## ⚠️ Important Notes

* Scaling is applied **after train-test split** to avoid data leakage.
* GridSearchCV ensures optimal model performance.
* Dataset is small, so results may show high accuracy.

---

## 🔥 Key Learnings

* Importance of preprocessing and scaling
* Avoiding data leakage
* Hyperparameter tuning using GridSearchCV
* Model evaluation techniques

---

## 📌 Future Improvements

* Use a larger real-world dataset
* Add visualization (decision boundary)
* Deploy using Flask or Streamlit
* Handle imbalanced datasets

---


