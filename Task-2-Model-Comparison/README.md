# Task 2: Model Comparison for House Price Prediction

This task focuses on comparing multiple regression models to predict house prices
using the California Housing Dataset. The goal is to evaluate different models and
identify the one that performs best based on standard regression metrics.

---

## 📊 Dataset
- California Housing Dataset (Scikit-learn)
- 20,640 records
- 8 numerical input features
- Target variable: House Price

---

## 🧠 Models Implemented
The following models were trained and evaluated:
- Linear Regression (baseline)
- Ridge Regression (regularized linear model)
- Decision Tree Regressor (non-linear model)

All models were trained using the same train-test split to ensure a fair comparison.

---

## 📈 Evaluation Metrics
Model performance was evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help measure prediction accuracy and model reliability.

---

## 🏆 Results Summary
Among the models tested, the **Decision Tree Regressor** achieved the lowest RMSE and
the highest R² score, making it the best-performing model for this dataset.

A comparison table and visual validation are included in the notebook.

---

## 📁 Files Included
- `AI_ML_Task2_Model_Comparison.ipynb` – Notebook with model training, evaluation, and comparison
- `Task2_Model_Comparison_Report.pdf` – Report summarizing methodology and results

---

## ✅ Conclusion
This task highlights the importance of comparing multiple machine learning models
instead of relying on a single approach. While linear models provide simplicity,
tree-based models can better capture non-linear patterns in housing data.
