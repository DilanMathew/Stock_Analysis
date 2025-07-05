# 📊 Stock Data Analysis and Visualization (2023-2024)

This project performs **end-to-end data processing, analysis, and visualization** of stock market data provided in YAML format (organized by date and month). It transforms the data into a structured CSV format and derives key market insights using Python.

---


## ✅ Features

### 🔄 Data Extraction
- Reads YAML files organized by month and day.
- Extracts and merges data into 50 individual **stock-wise CSV files**.

### 📈 Data Analysis & Visualizations

**Key Metrics:**
- ✅ Top 10 Green Stocks (highest yearly return)
- ✅ Top 10 Loss Stocks (lowest yearly return)
- ✅ Market Summary (avg. price, volume, red vs green count)

**Visual Charts:**
1. 📊 **Volatility Analysis** – Standard deviation of daily returns
2. 📈 **Cumulative Return Over Time** – Top 5 performing stocks
3. 🏭 **Sector-wise Performance** – Average yearly return by sector
4. 🔥 **Correlation Heatmap** – Closing price correlation across stocks
5. 📆 **Top 5 Gainers and Losers (Month-wise)** – 12-month dashboard

---

## ⚙️ Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- PyYAML

