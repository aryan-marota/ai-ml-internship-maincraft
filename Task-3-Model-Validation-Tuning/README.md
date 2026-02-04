# Task 3: Model Validation and Hyperparameter Tuning

This task focuses on improving model reliability by detecting overfitting,
validating models using cross-validation, and tuning hyperparameters systematically.

The objective is to select a final model based on generalization performance
rather than training accuracy alone.

---

## 📊 Dataset
- California Housing Dataset (Scikit-learn)
- 20,640 records
- 8 numerical features
- Target variable: House Price

---

## 🧠 Approach
The following steps were performed:
- Overfitting detection using train vs test performance
- Model validation using 5-fold cross-validation
- Hyperparameter tuning using GridSearchCV
- Comparison with baseline linear models

---

## 🔧 Models Used
- Linear Regression (baseline)
- Ridge Regression (regularized baseline)
- Decision Tree Regressor (tuned)

---

## 📈 Key Results
The tuned Decision Tree model showed improved generalization performance,
achieving lower RMSE and higher R² score compared to baseline models.

---

## 📁 Files Included
- `AI_ML_Task3_Model_Validation_Tuning.ipynb` – Complete notebook with validation and tuning
- `Task 3 Report.pdf` – Detailed report explaining methodology and results

---

## ✅ Conclusion
This task demonstrates the importance of validation and tuning in professional
machine learning workflows and highlights how overfitting can be reduced through
systematic model optimization.
