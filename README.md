# 🚗 Uber Driver Activation Prediction

A machine learning project that predicts whether a new Uber driver will actually start driving — built for Soar into Data Datathon.

---

## 🚀 What We Built
We analyzed Uber’s driver signup data to identify key patterns and predict which users will become active drivers.

Our model helps Uber:
- Understand early drop-off points
- Improve driver onboarding
- Allocate support resources more effectively

---

## 📊 Key Results
- **Models Used**: Logistic Regression, Random Forest, XGBoost
- **Best Accuracy**: ~93%
- **Best Balance of Precision/Recall**: XGBoost (92% precision, 94% recall)
- **Confusion Matrix Analysis**: Highlighted importance of data balancing

---

## 🧹 Data Preparation
- Removed irrelevant columns (e.g., IDs, unused text)
- Handled missing values (e.g., `'unknown'`, `-1`)
- Created binary target: `started_driving`
- Engineered features like `onboarding_delay` and `vehicle_age`
- Balanced dataset: 6,000 drivers and 6,000 non-drivers

---

## 📁 Files
- `Driven by Data.ipynb` — full code and model development
- `new_copy_combined.csv` — cleaned dataset used for training
- `README.md` — this file

---

## 💡 What We Learned
- Accuracy isn’t enough — precision and recall revealed model weaknesses
- Balancing the data was critical to model fairness
- XGBoost provided the best trade-off between flexibility and performance

---

## 👥 Team
- Justin Le– ML / Data Cleaning
- Johnson Nguyen – ML / Data Cleaning
- Joe Cheung – Visualization / Presentation

---

## 📣 Built For
🛠️ Soar into Data Datathon | 📅 2025

