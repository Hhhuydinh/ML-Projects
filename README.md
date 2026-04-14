# Machine Learning Projects

A collection of machine learning projects built while learning 
Python, Pandas, Scikit-learn and PyTorch.

---

## Titanic Survival Predictor
Predicts whether a Titanic passenger survived based on 
passenger data like age, sex, class and fare.

**Libraries:** Python, Pandas, Scikit-learn, NumPy, Matplotlib  
**Model:** Random Forest Classifier  
**Accuracy:** 82%  
**Dataset:** Data was imported from kaggle - https://www.kaggle.com/competitions/titanic/data

### What I did
- Cleaned and preprocessed real Titanic passenger data
- Handled missing values and encoded categorical features
- Trained a Random Forest model and analyzed feature importance
- Found that Fare, Sex and Age were the top predictors of survival

---

## Stock Trend Predictor
Predicts whether QQQ ETF will go up or down the next trading 
day using historical market data.

**Libraries:** Python, Pandas, Scikit-learn, yfinance, Matplotlib, ta  
**Model:** Random Forest Classifier  
**Accuracy:** ~50%

### What I did
- Pulled real time QQQ data using yfinance API
- Engineered features including 7/30 day moving averages, 
  RSI and volume change percentage
- Visualized price history with live price annotation 
  and next day prediction confidence

---

## Currently Learning
- Neural Networks and Backpropagation from scratch
- PyTorch
- Working towards building an LSTM stock predictor
