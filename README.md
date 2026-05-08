# Machine Learning Projects

A collection of machine learning projects built while learning 
Python, Pandas, Scikit-learn and PyTorch.

---

## 🚢 Titanic Survival Predictor
Predicts whether a Titanic passenger survived based on 
passenger data like age, sex, class and fare.

**Libraries:** Python, Pandas, Scikit-learn, NumPy, Matplotlib  
**Model:** Random Forest Classifier  
**Accuracy:** 82%  
**Dataset:** [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

### What I did
- Cleaned and preprocessed real Titanic passenger data
- Handled missing values and encoded categorical features
- Trained a Random Forest model and analyzed feature importance
- Found that Fare, Sex and Age were the top predictors of survival

---

## Stock Trend Predictor
Currently working with the stock QQQ
Predicts whether QQQ ETF will go up or down the next trading day
using historical market data and machine learning.

**Libraries:** Python, PyTorch, Scikit-learn, yfinance, Matplotlib, ta  
**Dataset:** Real time QQQ data pulled from Yahoo Finance (2009 - present)

### Models & Accuracy
| Model                 | Accuracy |
|-----------------------|----------|
| Random Forest         |   ~53%   |
| MLP Neural Network    |   ~57%   |
| LSTM Neural Network   |   ~55%   |

### What I did
- Downloaded and processed 15 years of real QQQ market data
- Implemented technical indicators including EMA (9, 21, 50, 200 day)
- Built and compared three models: Random Forest, MLP and LSTM
- Implemented minibatch training with early stopping to prevent overfitting
- Visualized full price history with live price annotation and
  next day prediction confidence

---

## Currently Learning
- Built LSTM stock predictor with PyTorch
- Next: Exploring transformer architectures
