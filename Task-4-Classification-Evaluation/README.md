# Task 4: Classification Model Evaluation

This task focuses on building and evaluating a binary classification model
using the Breast Cancer dataset. The goal is to go beyond accuracy and use
multiple evaluation metrics to assess model performance.

---

## 📊 Dataset
- Breast Cancer Dataset (Scikit-learn)
- 569 samples
- 30 numerical features
- Target:
  - 0 → Malignant
  - 1 → Benign

---

## 🧠 Approach
The following steps were performed:
- Data preprocessing and feature scaling
- Training Logistic Regression as baseline
- Evaluating using confusion matrix and classification metrics
- Plotting ROC curve and calculating AUC score
- Handling class imbalance using class weights
- Comparing with Decision Tree classifier

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC score

---

## 🔍 Key Results
- Logistic Regression achieved the best overall performance
- AUC score close to 1 indicates excellent classification ability
- Balanced model improved class fairness
- Decision Tree showed lower performance and signs of overfitting

---

## 📁 Files Included
- `AI_ML_Task4_Classification_Evaluation.ipynb` – Notebook with full implementation
- `Task 4 Report.pdf` – Detailed report

---

## ✅ Conclusion
This task demonstrates the importance of evaluating classification models
using multiple metrics and selecting models based on reliability and
generalization performance rather than accuracy alone.
