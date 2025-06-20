# 📊 Yes Bank Stock Closing Price Prediction

This mini-project focuses on predicting the **closing stock prices of Yes Bank** using historical data and machine learning models. The project includes exploratory data analysis (EDA), hypothesis testing, feature engineering, model building, and evaluation.

---

## 📌 Problem Statement

To develop a machine learning-based predictive model that forecasts the **closing price** of Yes Bank stock using features such as Open, High, Low, and other relevant stock market indicators.

---

## 📂 Dataset

- File: `data_YesBank_StockPrices.csv`
- Size: ~2000 records of historical stock data
- Features include:
  - Date
  - Open
  - High
  - Low
  - Close
  - WAP
  - No. of Shares
  - No. of Trades
  - Total Turnover

---

## 📈 Project Workflow

1. **Importing Libraries & Loading Dataset**
2. **EDA & Data Cleaning**
   - Checked for missing/duplicate values
   - Statistical summary
3. **Hypothesis Testing**
   - Defined & tested 3 hypotheses using statistical methods
4. **Feature Engineering**
   - Extracted new features like `Day`, `Month`, `Year`
   - Handled multicollinearity
5. **Model Building**
   - Trained and evaluated the following models:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - XGBoost Regressor
6. **Model Evaluation**
   - Metrics: MAE, MSE, RMSE, R² Score

---

## 🤖 Model Performance

| Model                  | MAE                    | MSE                   | RMSE                 | R² Score |
|------------------------|------------------------|------------------------|----------------------|----------|
| Linear Regression      | 5.76 × 10⁻¹³           | 4.91 × 10⁻²⁵           | 7.01 × 10⁻¹³         | 1.0000   |
| Decision Tree Regressor| 13.18                  | 810.56                 | 28.47                | 0.9206   |
| Random Forest Regressor| 12.03                  | 713.03                 | 26.70                | 0.9302   |
| XGBoost Regressor      | 10.07                  | 547.14                 | 23.39                | 0.9464   |


> 🔍 Although Linear Regression gave a perfect score, XGBoost was selected as the most **robust and generalizable** model.

---

## 📚 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost
- Google Colab

---

## 📌 Conclusion

This project demonstrates how machine learning can effectively predict stock prices. XGBoost provided the best balance between accuracy and generalization.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/prabh2002/yesbank-stock-prediction.git
