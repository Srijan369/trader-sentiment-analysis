````markdown
# 📊 Trader Performance vs Market Sentiment Analysis

## 🎯 Project Objective

This project analyzes how the Bitcoin Fear & Greed Index affects trader behavior and performance on Hyperliquid. The goal is to identify patterns in trading activity, win rates, leverage usage, and profitability across different market sentiment conditions, while generating actionable trading recommendations.

### Key Questions Answered
- Do traders perform better in Fear or Greed markets?
- How does trading activity change with sentiment?
- Which trader segments are most successful?
- What strategies work best in different sentiment conditions?

---

# 📁 Dataset Information

| Dataset | Original Size | After Cleaning | Date Range |
|----------|---------------|----------------|------------|
| Bitcoin Fear & Greed Index | 2,644 rows | 2,644 rows | Feb 2018 – May 2025 |
| Hyperliquid Trader Data | 211,224 rows | 2,810 unique trades | Dec 2023 – May 2025 |

> **Note:** 98.7% of raw trade data were duplicates. Analysis was performed on cleaned and processed trader data.

---

# 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/YOUR_USERNAME/trader-sentiment-analysis.git
cd trader-sentiment-analysis
````

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run:

```bash
analysis.ipynb
```

---

# 📊 Visualizations Included

1. Fear & Greed Index Over Time
2. Daily PnL Distribution by Sentiment
3. Win Rate by Sentiment Level
4. Trading Activity by Sentiment
5. Long/Short Ratio by Sentiment
6. Correlation Heatmap
7. Trader Segment Performance
8. Sentiment Impact by Trader Type

---

# 📊 Key Insights

## 📈 Overall Statistics

| Metric                | Value    |
| --------------------- | -------- |
| Trading Days Analyzed | 264 days |
| Unique Traders        | 30       |
| Profitable Traders    | 83.3%    |
| Average Daily PnL     | $1,163   |
| Average Win Rate      | 39%      |

---

## 📉 Sentiment Impact

| Sentiment | Avg Daily PnL | Win Rate | Trades/Day |
| --------- | ------------- | -------- | ---------- |
| Fear      | $3,826        | 36.2%    | 17.6       |
| Neutral   | $967          | 34.2%    | 11.0       |
| Greed     | $167          | 41.2%    | 7.8        |

---

## 🔍 Key Findings

* Fear periods generated higher profitability compared to Greed periods.
* Traders were significantly more active during Fear conditions.
* Greed periods showed slightly higher win rates but lower overall profitability.
* High-frequency traders performed more consistently than low-frequency traders.
* Low-frequency traders experienced larger losses during Greed periods.

---

# 💡 Recommendations

* Reduce position size during Extreme Fear
* High-frequency traders should focus on Fear periods
* Low-frequency traders perform better in Neutral/Fear periods
* Avoid trading during extreme sentiment (0-25, 75-100)
* Use tighter stop-loss strategies during highly volatile market conditions

---

# 📁 Project Structure

```text
trader_sentiment_analysis/
│
├── Data/
│   ├── fear_greed_index.csv
│   └── historical_data.csv
│
├── Output/
│   ├── charts/
│   ├── reports/
│   └── processed datasets
│
├── analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📝 Requirements

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* jupyter

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 📧 Contact

For questions about this analysis, please reach out.
