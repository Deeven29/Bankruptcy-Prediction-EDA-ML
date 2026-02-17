# Bankruptcy-Prediction-EDA-ML
---

## 🔎 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to better understand the dataset and identify patterns before model building.

### 📊 Key EDA Steps:

- Checked dataset shape and data types.
- Verified missing values (dataset contained no significant missing values).
- Analyzed class distribution and identified strong class imbalance.
- Visualized target variable distribution.
- Examined correlation between financial features.
- Identified highly correlated features and removed redundancy.
- Detected potential outliers in financial ratios.
- Reduced features from 96 to 74 for better model performance.

### 📈 Key Observations:

- The dataset was highly imbalanced (very few bankrupt companies).
- Several financial indicators showed strong correlation.
- Tree-based models performed better due to nonlinear financial relationships.
- Feature reduction helped reduce noise and improve generalization.

EDA helped in understanding the structure of financial data and guided preprocessing decisions such as feature selection and handling class imbalance.

# 📊 Bankruptcy Prediction using Machine Learning

## 📌 Project Overview
This project predicts whether a company is likely to go bankrupt using financial indicators and machine learning classification models.

---

## 🎯 Problem Statement
Build a predictive model to classify companies as bankrupt or non-bankrupt using financial ratio data.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## ⚙️ Data Processing
- Removed irrelevant and redundant features
- Reduced features from 96 to 74
- Applied SMOTE to handle class imbalance
- Used StandardScaler for normalization
- Stratified train-test split

---

## 🤖 Models Trained
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting
- Neural Network (MLP)

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special focus was placed on **Recall for the bankrupt class**, as missing a bankrupt company can result in financial risk.

---

## 🏆 Best Performing Model

**Random Forest**
- Accuracy: 96%
- Balanced precision and recall
- Best F1-score for minority class

---

## 💡 Key Insights
- Accuracy alone is misleading for imbalanced datasets.
- Recall is critical in financial risk prediction.
- Tree-based models handled financial ratio data effectively.
- SMOTE significantly improved minority class detection.

---

## 🚀 Conclusion
Random Forest was selected as the final model due to its strong performance and balanced evaluation metrics, making it suitable for practical financial risk prediction scenarios.
