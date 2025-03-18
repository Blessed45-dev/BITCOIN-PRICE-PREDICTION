# BITCOIN-PRICE-PREDICTION 

This project explores *Bitcoin price prediction* using *machine learning and deep learning* models. The study compares *LSTM, GRU, Bi-Directional LSTM, Decision Trees, Random Forest, Gradient Boosting, and SVR, with a **Stacked Ensemble Model* achieving the highest prediction accuracy.

---

## 🔍 *Project Overview*
- *Dataset: Historical Bitcoin prices from **Yahoo Finance (2015-2023)*.
- *Objective*: Develop predictive models to forecast Bitcoin prices.
- *Models Used*:
  - *Machine Learning*: Linear Regression, Decision Tree, Random Forest, Gradient Boosting, SVR.
  - *Deep Learning*: LSTM, GRU, Bi-LSTM.
  - *Stacked Ensemble Model* (combines LSTM, GRU, Bi-LSTM for better accuracy).
- *Best Performing Model: **Stacked Ensemble (R² = 0.9874, RMSE = 0.0124)*.
- *Evaluation Metrics*: RMSE, MAPE, R².
- 
## 📊 *Key Findings*
- *Stacked Ensemble Model outperformed individual models*.
- *ARIMA & SARIMA struggled* with Bitcoin's extreme volatility.
- *Hyperparameter tuning significantly improved model accuracy*.
- *Bitcoin volatility analysis* showed price spikes in *2017, 2021, 2023*.

---

## 🚀 *Technologies Used*
- *Python*
- *Libraries*:
  - Data Processing: pandas, numpy, scipy
  - Machine Learning: scikit-learn, XGBoost
  - Deep Learning: TensorFlow, Keras
  - Time Series Forecasting: statsmodels, ARIMA
  - Visualization: Matplotlib, Seaborn
 
  - ## 📂 *Project Structure*
├── BITCOIN-PRICE-PREDICTION.ipynb # Jupyter Notebook with implementation
├── Bitcoin_Prediction_Report.pdf # Detailed report with findings 
