# Machine Learning — Classical

> Tabular machine learning, end to end. Classification, regression, and the kind of feature work that decides whether a model is useful or just *technically working*.

This is the home for traditional ML — the gradient-boosted trees, regularized linear models, and feature-engineering pipelines that still win most real-world tabular problems. Each notebook follows a complete cycle: EDA → preprocessing → modeling → evaluation → reflection.

---

## 📓 Notebooks in this repo

### 1. Credit Card Fraud Detection — 99% Accuracy 🚀
A highly imbalanced classification problem (fraud is ~0.17% of transactions). The notebook does *not* stop at 99% accuracy — it then digs into precision, recall, PR-AUC, and the operational question of "what is this model actually good for in production?" Resampling strategies, threshold tuning, and an honest discussion of the cost of false negatives.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/credit-card-fraud-detection-achieving-99-acc)**

---

### 2. House Price Prediction — Advanced Regression, R² = 0.9337 🏠
Kaggle's House Prices Advanced Regression dataset done thoroughly. Feature engineering, target transformation (log of SalePrice), encoding strategy, and an ensemble of regularized linear and gradient-boosted models. R² = 0.9337 with calibrated uncertainty.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/house-prediction-adv-regression-v1-r2-0-9337)**

---

### 3. Flood Prediction — Fully Detailed Walkthrough 🌊
A regression problem on flood-risk forecasting, written as a teaching notebook. Walks through every feature, every transformation, and every modeling decision so a junior data scientist can replicate the approach on a similar problem.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/fully-detailed-explained-flood-prediction)**

---

### 4. Apple Quality Prediction 🍎🤖
A classification problem on apple quality. Smaller dataset, so the notebook focuses on robust validation (proper cross-validation, not just train/test split) and avoiding the overfitting that often catches people off-guard on small tabular problems.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/crunching-apple-data-quality-prediction)**

---

### 5. Student Success Prediction 🎓
Predicting student success / dropout from academic and demographic features. The notebook treats this like a real-world deployment scenario — what features are actionable for an educator vs. what's just noise, and how do you build a model that suggests *interventions* rather than just verdicts.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/a-dive-into-success-prediction)**

---

### 6. Used Car Price Prediction 🚗📉
A clean regression baseline on used-car listings. Categorical encoding, outlier handling, and a comparison of linear and tree-based models. A good starting point if you're new to regression problems.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/basic-used-car-price-prediction)**

---

### 7. Accurate Classification — Simplified
A clean, simplified classification workflow that's deliberately stripped down to the essentials. Useful as a "first model" template — no exotic tricks, just the pipeline done correctly.

📔 **[Open on Kaggle →](https://www.kaggle.com/code/samanfatima7/accurate-classification-simplified)**

---

## 🛠 Stack

Python · scikit-learn · XGBoost · LightGBM · CatBoost · pandas · NumPy · Matplotlib · Seaborn

## 📂 How this repo is organized

Each notebook is standalone with its dataset linked from Kaggle. To run locally:

```bash
git clone https://github.com/samanfatima7/machine-learning-classical.git
cd machine-learning-classical
pip install -r requirements.txt
jupyter notebook
```

## 🧭 A note on "classical" ML

Deep learning gets the headlines, but most production tabular problems are still won by gradient-boosted trees with thoughtful feature engineering. These notebooks are deliberately not flashy — they're the bread and butter, and they're the work that actually pays off when you're solving a real business problem with messy data.

## 👋 About

Saman Fatima — Kaggle Grandmaster, data scientist from Pakistan. More work on [Kaggle](https://www.kaggle.com/samanfatima7) · [LinkedIn](https://www.linkedin.com/in/saman-fatima-datascience/).

⭐ if you found something useful, and reach out if you want to collaborate.
