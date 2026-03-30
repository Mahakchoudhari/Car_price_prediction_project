# 🚗 Car Price Prediction

A Machine Learning web application that predicts the **Selling Price of Second Hand Cars** based on various features like car name, year, km driven, fuel type, and more.

---

## 📌 Project Overview

The used car market is growing rapidly in India. Predicting the right price of a second-hand car is important for both buyers and sellers. This project uses Machine Learning regression algorithms to predict car prices based on car characteristics.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📊 Dataset

- **Name:** Car Dekho Dataset
- 🔗 Dataset Link:
https://www.kaggle.com/datasets/jacksondivakarr/sample34
- **Features:** 12 (Name, Year, KM Driven, Fuel, Seller Type, Transmission, Owner, Seats, Max Power, Engine CC, Mileage, Mileage Unit)
- **Target:** Selling Price 

---

## 🔍 Project Structure

```
Car_price_prediction_project/
│
├── pricing.csv               ← Dataset
├── car_price_prediction.ipynb ← Jupyter Notebook
├── requirements.txt           ← Dependencies
└── README.md
```



## 📈 Steps Followed

1. **Data Preprocessing** — Dropped unnecessary columns, handled missing values, outlier handling using IQR Capping
2. **EDA & Visualizations** — Histplot, Correlation Heatmap, Scatterplot, Boxplot
3. **Encoding** — OneHotEncoder for all categorical features
4. **Train Test Split** — 80/20 split
5. **Feature Scaling** — StandardScaler on X and Y
6. **Model Training** — Random Forest Regressor
7. **Evaluation** — R2 Score, MAE, MSE, RMSE, Actual vs Predicted Plot
8. **Model Comparison** — Linear Regression, Random Forest, SVR, Decision Tree, Polynomial Regression

---

## ✅ Model Performance

| Metric | Score |
|--------|-------|
| R2 Score | 89% |
| Cross Validation R2 | 89.04% |

---

## 🤖 Models Compared

| Model | R2 Score |
|-------|----------|
| Random Forest | 88.81% |
| Linear Regression | 75.80% |
| Decision Tree | 79.30% |
| SVR | 85.49% |
| Polynomial Regression | 80.92% |

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/Mahakchoudhari/Car_price_prediction_project.git
cd Car_price_prediction_project
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
---

## 📦 Requirements

```
scikit-learn
pandas
numpy
matplotlib
seaborn
```

---

## 👩‍💻 Author

**Mahak Choudhari**
B.Tech — Artificial Intelligence & Machine Learning (2nd Year)
[GitHub](https://github.com/Mahakchoudhari)

---
