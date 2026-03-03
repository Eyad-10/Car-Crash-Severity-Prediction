# 🚗 Car Crash Severity Prediction

## 📌 Project Overview
This project aims to predict car crash severity levels using Machine Learning techniques.  
The model classifies accidents into 4 severity categories based on crash-related features.

This project demonstrates skills in:
- Data preprocessing
- Handling imbalanced datasets
- Model training & evaluation
- Performance comparison across multiple algorithms

---

## 📊 Dataset Description
The dataset contains accident-related features such as:
- Weather conditions
- Road conditions
- Location information
- Traffic-related variables

Target variable:
- Severity Level (1–4)

Since the dataset was imbalanced, special preprocessing techniques were applied.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Power BI (for dashboard visualization)

---

## 🔄 Data Preprocessing
- Handled missing values
- Encoded categorical variables using One-Hot Encoding
- Applied feature scaling
- Used SMOTE to handle class imbalance

---

## 🤖 Models Implemented
The following models were trained and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Naive Bayes
- Gradient Boosting
- XGBoost

---

## 📈 Model Evaluation
Models were evaluated using:

- Accuracy Score
- Macro F1-Score
- Classification Report
- Confusion Matrix

### 🏆 Best Model Performance
- Macro F1-Score: **0.648**
- Accuracy: **0.836**

The model showed balanced performance across all 4 severity classes.

---

## 📌 Key Challenges
- Imbalanced dataset
- Multi-class classification complexity
- Feature selection

---

## 🚀 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Feature importance analysis
- Deploy model using Flask / Streamlit
- Cross-validation for better generalization

---
