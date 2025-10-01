# 💰 Cryptocurrency Price Analysis (Bitcoin)  

This project explores Bitcoin historical price data to analyze volatility, trends, and return distributions.  
The dataset includes daily open, high, low, close, and volume values.  

The goal is to use **statistics + Python visualization** to uncover insights into the behavior of Bitcoin returns.  
Data Set used: https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data

---

## 📊 Key Questions & Insights  

1. **What is the average daily return of Bitcoin?**  
   - Calculated mean, median, and standard deviation of daily returns.  
   - Returns are highly volatile with large variance compared to traditional assets.  

2. **How do Bitcoin returns distribute over time?**  
   - Histogram shows a right-skewed distribution with occasional extreme gains/losses.  
   - Median return is close to zero, but mean is pulled upward by rare large spikes.  

3. **What does the volatility look like?**  
   - Boxplot reveals heavy tails and frequent outliers.  
   - Confirms Bitcoin is subject to sudden swings during bull runs and crashes.  

---

## 🛠 Tools Used  

- Python 🐍  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
- Google Colab 📓  

---

## 🚀 Next Steps  

- Extend analysis to other cryptocurrencies (ETH, LTC, etc.).  
- Compare Bitcoin volatility to traditional assets (stocks, gold).  
- Apply moving averages and time series models for trend forecasting.  
- Build a Power BI / Streamlit dashboard for interactive visualization.  

---

## 📂 Project Structure  

```text
Crypto-Stats-EDA/
│
├── crypto_stats_analysis.ipynb   # Main Colab notebook                  
└── README.md                     # Project documentation
