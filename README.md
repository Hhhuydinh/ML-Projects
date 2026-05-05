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
**Dataset:** [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

### What I did
- Cleaned and preprocessed real Titanic passenger data
- Handled missing values and encoded categorical features
- Trained a Random Forest model and analyzed feature importance
- Found that Fare, Sex and Age were the top predictors of survival

---

## Stock Trend Predictor
Currently working with the stock QQQ 

Predicts whether QQQ ETF will go up or down the next trading day.

**Libraries:** Python, PyTorch, Scikit-learn, yfinance, Matplotlib, ta  
**Models:** Random Forest → Neural Network (MLP)  
**Accuracy:** Random Forest 50-53% → Neural Network 55-58% 

### What I did
- Pulled real time QQQ data using yfinance API
- Engineered features including EMAs (9, 21, 50, 200) and volume change
- Built and trained a PyTorch MLP neural network
- Improved accuracy over Random Forest baseline
- Visualized price history with live price and next day prediction

---

## Currently Learning
- Working towards building an LSTM stock predictor
