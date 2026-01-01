# Customer Airline Booking Prediction

## 📌 Project Overview
This project builds a predictive machine learning model to identify customers who are likely to purchase holidays. The goal is to enable proactive customer engagement by using booking and behavioural data.

The analysis emphasizes **data preparation, model interpretability, and business relevance**.

---

## 🎯 Business Objective
- Predict whether a customer will purchase a holiday
- Identify the most influential factors driving purchases
- Enable targeted marketing and proactive customer acquisition

---

## 🧠 Methodology

### 1. Data Exploration & Preparation
- Explored customer booking data and target distribution
- Handled categorical variables through encoding
- Scaled numerical features for model stability
- Addressed class imbalance using class weighting

---

### 2. Model Selection
**Logistic Regression** was selected due to:
- High interpretability
- Clear explanation of feature impact
- Suitability for binary classification with imbalanced data

This aligns well with business decision-making requirements.

---

### 3. Model Training
- Data split into training and test sets
- Features scaled using standardisation
- Logistic Regression trained with:
  - Balanced class weights
  - Stable solver for convergence

---

### 4. Model Evaluation
Model performance was assessed using:
- Confusion Matrix
- Precision, Recall, and F1-score
- ROC-AUC score
- Cross-validation

Special focus was placed on **recall for purchasers**, as identifying buyers is critical from a business perspective.

---

### 5. Model Interpretation
- Feature coefficients were extracted
- A visualisation was created to show how each variable contributed to predictions
- Insights were translated into business-friendly language

---

## 📊 Model Performance

The Logistic Regression model demonstrated strong predictive capability despite significant class imbalance in the dataset.

Key evaluation metrics:
- **ROC-AUC:** ~0.72, indicating good separation between purchasers and non-purchasers
- **Recall (Purchasers):** ~74%, ensuring most potential buyers are correctly identified
- **Overall Accuracy:** ~70%
- **Cross-validation:** Consistent performance across folds

The model prioritised recall over precision for purchasers, aligning with the business objective of maximising customer acquisition opportunities.

---

## 🛠 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📊 Key Findings
- The model achieved a strong ROC-AUC score despite class imbalance
- Certain behavioural and booking-related variables showed high predictive power
- Logistic Regression provided clear, explainable insights suitable for stakeholders

---

## ✅ Key Takeaway
This project demonstrates how well-prepared data combined with interpretable machine learning can support proactive customer targeting and informed commercial decisions.
