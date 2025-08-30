# Crypto Derivative Analysis

## Objective  
The goal of this analysis is to:  

**Analyze how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed). Identify hidden trends or signals that could influence smarter trading strategies.**

---

##  Datasets  

### 1. Historical Trading Data (`historical_data.csv`)  
Contains ~211k transaction-level trade records.  

- `Execution Price` → Price at which trade occurred  
- `Size Tokens` → Number of tokens traded  
- `Size USD` → Value of trade in USD  
- `Side` → BUY / SELL  
- `Closed PnL` → Realized profit/loss  
- `Fee` → Trading fee  
- `Direction` → Trade position (e.g., long/short)  
- `Timestamp` → Trade execution time  

### 2. Fear & Greed Index (`fear_greed_index.csv`)  
Captures market sentiment daily.  

- `value` → Sentiment score
- `classification` → Qualitative category
- `date` → Date of measurement  
- `timestamp` → Numeric timestamp

---

## ⚙️ Installation & Requirements  

This notebook requires Python and the following packages:  

```bash
pip install pandas numpy matplotlib seaborn scikit-posthocs scipy


- Created by [Praveen Kumar Kushwaha](https://github.com/Praveenk9414)