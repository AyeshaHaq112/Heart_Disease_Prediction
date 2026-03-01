# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Objective

The goal of this project is to build a machine learning model that predicts whether a person is at risk of heart disease based on their medical and demographic data.

This is a binary classification problem, where:

- **0 → No heart disease**
- **1 → Heart disease present**

---

## 📊 Dataset

**Dataset:** Heart Disease UCI Dataset (Kaggle)

The dataset contains clinical features such as:

- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Cholesterol level  
- Fasting blood sugar  
- ECG results  
- Maximum heart rate  
- Exercise-induced angina  
- ST depression  
- Number of major vessels  
- Thalassemia type  

The target variable indicates the presence or absence of heart disease.

---

## 🧹 Data Preprocessing

The following steps were performed:

- Missing values handled  
  - Numeric features → filled with median  
  - Categorical features → filled with most frequent value  

- Categorical variables converted to numeric using one-hot encoding  

- Dataset split into training and testing sets  

- Feature scaling applied using StandardScaler  

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted to understand patterns in the data:

- Distribution of heart disease cases  
- Correlation between features and the target  
- Identification of features strongly associated with heart disease risk  

---

## 🤖 Model Used

### Logistic Regression

Chosen because:

- Suitable for binary classification  
- Easy to interpret  
- Widely used in medical prediction tasks  

---

## 📈 Model Evaluation

The model was evaluated using:

### ✅ Accuracy
Measures overall correctness of predictions.

### ✅ Confusion Matrix
Shows:

- True Positives  
- True Negatives  
- False Positives  
- False Negatives  

### ✅ ROC Curve
Shows the trade-off between sensitivity and specificity.

### ✅ ROC-AUC Score
Measures the model’s ability to distinguish between classes.

---

## ⭐ Feature Importance

Feature importance was determined using Logistic Regression coefficients.

Features with higher absolute coefficient values have greater influence on prediction.

Important predictors typically include:

- Chest pain type  
- ST depression (oldpeak)  
- Exercise-induced angina  
- Maximum heart rate achieved  
- Number of vessels observed  

---

## 🏁 Results

- The model successfully predicts heart disease risk with good accuracy.  
- ROC-AUC indicates strong class discrimination ability.  
- Several clinical features show strong influence on prediction.  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  
