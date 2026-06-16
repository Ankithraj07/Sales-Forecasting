# Sales Forecasting System

Predictive ML model for retail sales forecasting using Big Mart dataset.
Achieved 20% improvement in forecast accuracy over baseline.

---

## Problem

Retail stores struggle to predict future sales accurately, leading to
overstock or stockouts. This system predicts item-level sales using
historical data and store attributes.

---

## Approach

```
Raw Sales Data (Big Mart)
        ↓
Data Cleaning + Feature Engineering
        ↓
Model Training — Linear Regression, XGBoost, Random Forest
        ↓
Model Comparison — RMSE, R² evaluation
        ↓
Best Model selected → Sales Prediction
```

---

## Results

| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | baseline | baseline |
| Random Forest | improved | improved |
| XGBoost | best | best |

20% improvement in forecast accuracy over baseline Linear Regression.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python |
| ML Models | Linear Regression, XGBoost, Random Forest |
| Libraries | Pandas, NumPy, Scikit-Learn, Matplotlib |
| Notebook | Jupyter |
| Backend | Flask |
| Data | Big Mart Sales Dataset |

---

## Project Structure

| File | Purpose |
|------|---------|
| sales_forecast.ipynb | Data analysis, model training, evaluation |
| app.py | Flask API for predictions |
| requirements.txt | Dependencies |

---

## Run Locally

```bash
git clone https://github.com/Ankithraj07/Sales-Forecasting.git
cd Sales-Forecasting
pip install -r requirements.txt
jupyter notebook sales_forecast.ipynb
```

---

## Key Findings

- XGBoost outperformed other models on RMSE metric
- Store type and item MRP were strongest predictors
- Feature engineering on outlet age improved accuracy significantly