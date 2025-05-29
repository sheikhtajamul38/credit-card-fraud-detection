# Credit Card Fraud Detection

A end-to-end pipeline for detecting fraudulent credit-card transactions using machine learning. This project covers data exploration, feature engineering, model training/comparison, and a FastAPI endpoint for real-time scoring.

## 🚀 Features

* **EDA & Visualization**: Class imbalance, amount distributions, temporal & geographic patterns
* **Feature Engineering**: Customer age, hour/day features, geodesic distance, tx-per-card, merchant fraud rate
* **Models**:

  * XGBoost (raw & isotonic-calibrated)
  * LightGBM
  * CatBoost
  * Random Forest
* **Evaluation**: Precision/Recall/F1 on fraud class, confusion matrices, composite ranking
* **Deployment**: Saved model & metadata, FastAPI for live predictions

## 📦 Installation

```bash
git clone [https://github.com/your-org/fraud-detection.git](https://github.com/sheikhtajamul38/credit-card-fraud-detection/)
```

## ⚙️ Usage

1. **Notebook**

   ```bash
   jupyter notebook credit-card-fraud-detection.ipynb
   ```
2. **Train & Compare**
   Runs all models and saves `model_comparison.csv`.


## 📊 Results

* **Best F1 (fraud)**: Calibrated XGBoost (\~0.40)
* **High Recall**: Raw XGBoost (\~0.95)
* **Balanced Trade-off**: LightGBM & CatBoost

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Implement changes and tests
4. Open a pull request for review

© 2025 Fraud Detection Project
