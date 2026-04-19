# 👥 Employee Performance Predictor

An HR analytics and Machine Learning project that predicts employee performance levels using classification algorithms trained on 1,000 synthetic employee records.

---

## 📊 Project Overview

| Item | Details |
|---|---|
| Dataset | Synthetic — 1,000 employees, 12 features, 6 departments |
| Task | Multi-class Classification (High / Medium / Low) |
| Models | Random Forest + Logistic Regression |
| Best Accuracy | 66% (Logistic Regression) |
| Libraries | pandas, numpy, matplotlib, seaborn, scikit-learn |

---

## 🔍 What This Project Does

- Generates realistic HR data with salary, training hours, satisfaction, manager ratings
- Full EDA with 6-chart combined dashboard
- Trains and compares 2 ML classification models
- Shows feature importance — which factors actually predict performance
- Live prediction demo for 3 new employees with probability scores

---

## 🏆 Top 3 Performance Predictors

1. Manager Rating
2. Satisfaction Score
3. Projects Completed

---

## 📈 Output Charts

### EDA Dashboard
![EDA](chart1_eda_dashboard.png)

### Feature Correlation Heatmap
![Correlation](chart2_correlation.png)

### Model Evaluation
![Model](chart3_model_evaluation.png)

### Feature Importance
![Features](chart4_feature_importance.png)

### HR Insights Dashboard
![HR Insights](chart5_hr_insights.png)

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest, Logistic Regression)

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open `Employee_Performance_Predictor.ipynb` in Jupyter Notebook and run all cells.

---

## 📁 Project Files

| File | Description |
|---|---|
| `Employee_Performance_Predictor.ipynb` | Main notebook |
| `employee_data.csv` | 1,000-record HR dataset |
| `chart1_eda_dashboard.png` | 6-chart EDA dashboard |
| `chart2_correlation.png` | Feature correlation heatmap |
| `chart3_model_evaluation.png` | Confusion matrix + accuracy |
| `chart4_feature_importance.png` | Feature importance ranking |
| `chart5_hr_insights.png` | HR analytics dashboard |
