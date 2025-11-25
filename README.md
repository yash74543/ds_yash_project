# 📊 Trader Behavior vs Market Sentiment — Data Science Project

This project analyzes how trader behavior changes under different Bitcoin market sentiment
conditions such as **Fear** and **Extreme Fear**, using:

- Execution Price  
- Trading Volume  
- Position Size  
- Profitability  
- Loss Probability  
- Sentiment (Fear / Greed)

The goal is to uncover insights that help traders make better decisions.

---

## 📁 Project Structure

ds_yash_project/
│── csv_files/ # raw datasets (historical trading + fear & greed index)
│── outputs/ # charts generated from analysis
│── notebook_1.ipynb # main analysis notebook
│── ds_report.pdf # final report with insights + visualizations
│── README.md # project documentation
│── ds_yash.zip # compressed project folder



---

## 📚 Datasets Used

### **1. Historical Trading Data (Hyperliquid)**
Contains:  
- Execution Price  
- Size Tokens  
- Size USD  
- Side (Buy/Sell)  
- Start Position  
- Closed PnL  
- Transaction Hash  
- Timestamp  

### **2. Bitcoin Fear & Greed Index**
Contains:  
- Value (0–100)  
- Classification (Fear, Extreme Fear, Greed, Neutral)  
- Timestamp  
- Date  

---

## 🧹 Methods Used

- Data Cleaning  
- Timestamp Conversion  
- Date Alignment  
- Dataset Merge (sentiment matching)  
- Exploratory Data Analysis  
- Statistical Analysis  
- Visualizations  

---

## 🔍 Key Insights

### **Insight 1 — Profitability Under Fear**
- **Average Profit:** **48.74 USD per trade**  
Traders perform better and capture opportunities during *fear dips*.

---

### **Insight 2 — Trading Volume Under Fear**
- **Total Volume:** **~1.19 Billion USD**  
Large money moves during fear periods → increased activity.

---

### **Insight 3 — Position Size**
- **Average Size:** **4623 tokens**  
Traders take **bigger positions** during fear, indicating accumulation.

---

### **Insight 4 — Loss Probability**
- **Loss Chance:** **8.3%**  
Very low → fear periods are *relatively safer* to trade.

---

### **Insight 5 — Number of Trades**
- **Total Trades:** **211,224**  
High volume + high activity → sentiment heavily affects market behavior.

---

## 📈 Visualizations

Included charts:

- Profit vs Sentiment  
- Trading Volume  
- Position Size  
- Loss Probability  
- Number of Trades  

(All charts are available in `outputs/` folder)

---

## 📝 Final Conclusion

Fear sentiment leads to:

- Higher trading volume  
- Larger position sizes  
- Better profitability  
- Lower loss probability  

Overall, **fear-driven markets offer better trading opportunities**.

---

## ✍️ Author

**Yash**  
Data Science Assignment — Trader Behavior Insights  
November 2025

