# 📊 Customer Purchase Prediction using Machine Learning

## 🧠 Project Overview
This project predicts whether a customer will make a purchase based on their online browsing behavior using machine learning techniques. It is built using the **Online Shoppers Intention dataset** and helps understand customer intent in e-commerce platforms.

The model analyzes user session data such as page visits, time spent on pages, bounce rates, exit rates, and page value to predict the likelihood of purchase.

---

## 🎯 Objective
To build a classification model that can accurately predict whether a customer will:
- ✔ Purchase (Revenue = 1)
- ❌ Not Purchase (Revenue = 0)

---

## 📂 Dataset Information
- Dataset: Online Shoppers Intention
- Source: UCI / Kaggle / HuggingFace dataset link
- Total Records: ~12,000+
- Target Column: `Revenue`

### Key Features:
- Administrative
- Administrative_Duration
- Informational
- Informational_Duration
- ProductRelated
- ProductRelated_Duration
- BounceRates
- ExitRates
- PageValues
- SpecialDay
- Month
- OperatingSystems
- Browser
- Region
- TrafficType
- VisitorType
- Weekend

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

---

## 🔄 Workflow

### 1. Data Preprocessing
- Removed duplicates
- Handled categorical encoding
- Checked missing values
- Feature selection

### 2. Exploratory Data Analysis (EDA)
- Revenue distribution analysis
- PageValues vs Purchase behavior
- BounceRates & ExitRates impact
- Correlation heatmap

### 3. Model Building
- Train-test split (80:20)
- Random Forest Classifier used
- Model trained on customer behavior patterns

### 4. Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 🤖 Model Used
- Random Forest Classifier
- Handles non-linear relationships
- Provides feature importance
- Works well for classification tasks

---

## 📊 Results
- Achieved good accuracy on test data
- PageValues, ExitRates, and BounceRates were key predictors
- Model successfully identifies potential buyers

---

## 📈 Sample Prediction
The model can predict whether a customer session will result in a purchase:

- Input: Customer browsing behavior
- Output:
  - `1 → Purchase`
  - `0 → No Purchase`

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Handling class imbalance using SMOTE
- Deploying model using Flask / Streamlit
- Real-time customer prediction system

---

## 📌 Conclusion
This project demonstrates how machine learning can be used in e-commerce to understand customer intent and improve conversion rates by predicting purchase behavior from browsing patterns.

---

## 👨‍💻 Author
- Data Science Learner Project
