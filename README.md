# Crypto Trader Behavior Analysis Using Market Sentiment

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader behavior using historical trading data and the Bitcoin Fear & Greed Index.

The objective of the project is to uncover patterns in trader profitability, trading activity, market participation, and risk behavior under different market sentiment conditions such as Fear, Greed, Extreme Fear, and Extreme Greed.

The project also includes a machine learning model to predict trade profitability using sentiment and trading behavior features.

---

# Datasets Used

## 1. Bitcoin Market Sentiment Dataset
- Contains Fear & Greed Index classifications
- Columns include:
  - date
  - classification
  - value

## 2. Historical Trader Dataset
- Contains historical crypto trading activity
- Columns include:
  - Account
  - Coin
  - Execution Price
  - Size USD
  - Side
  - Direction
  - Closed PnL
  - Fee
  - Timestamp

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Workflow

1. Data Loading
2. Data Cleaning
3. Timestamp Conversion
4. Dataset Merging
5. Exploratory Data Analysis (EDA)
6. Trader Behavior Analysis
7. Sentiment-Based Performance Analysis
8. Trader Segmentation
9. Predictive Modeling
10. Strategy Recommendations

---

# Key Analyses Performed

## Market Sentiment Analysis
- Fear vs Greed distribution
- Sentiment impact on profitability

## Profitability Analysis
- Average Closed PnL
- Win rate analysis
- Profitability distribution

## Trader Behavior Analysis
- Buy vs Sell activity
- Long vs Short positions
- Trade size analysis
- Transaction fee analysis

## Trader Segmentation
- Frequent vs infrequent traders
- Consistent winners vs lower-performing traders

## Correlation Analysis
- Relationships between trade size, fees, and profitability

## Machine Learning Bonus
- Random Forest classification model
- Profitability prediction
- Feature importance analysis

---

# Key Insights

- Extreme Greed conditions showed the highest trader win rates and profitability.
- Fear market conditions resulted in larger trade sizes and higher transaction fees.
- Trading direction was the most important feature in predicting profitability.
- Profitability was highly concentrated among a small number of traders.
- Market sentiment significantly influenced trader behavior and trading activity.

---

# Machine Learning Results

- Model Used: Random Forest Classifier
- Prediction Target: Trade Profitability
- Model Accuracy: ~92%

---

# Strategy Recommendations

1. Apply stricter risk management during Fear market conditions due to increased volatility and aggressive trading behavior.

2. Momentum-following strategies may perform better during Extreme Greed conditions because of higher trader win rates and stronger bullish sentiment.

---
# Conclusion

This project demonstrates how market sentiment and trader behavior can be analyzed using data science techniques to generate meaningful financial insights and support data-driven trading strategies.

# Project Structure

```text
Crypto_Trading_Analysis/
│
├── crypto_trader_analysis.ipynb
├── README.md
├── historical_data.csv
├── fear_greed.csv


