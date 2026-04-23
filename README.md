# Trader Sentiment Analysis

## Overview
This project is an end-to-end analytics workflow designed to study the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **Hyperliquid trader performance**. By combining sentiment data with historical trading activity, the project uncovers how trader behavior changes under different market conditions and predicts profitable trades using machine learning.

The project is structured in a professional GitHub-ready format with datasets, charts, notebooks, and documentation for easy reproducibility.

---

## Objectives
- Analyze how Bitcoin Fear & Greed sentiment impacts trading performance.
- Measure trader profitability using key metrics.
- Identify behavioral patterns across different sentiment regimes.
- Segment traders into meaningful user archetypes.
- Predict profitable trades using machine learning.
- Deliver business recommendations for retention, monetization, and risk control.

---

## Tech Stack
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
## Project Structure

```text
primetrade-trader-sentiment-analysis/
│── Analysis.ipynb
│── README.md
│── historical_data.csv
│── fear_greed_index.csv
│── charts/
```
---


## Key Features

### Data Processing
- Cleaned missing and inconsistent values.
- Standardized date formats.
- Merged sentiment and trading datasets.
- Removed duplicates and invalid records.

### Feature Engineering
Created metrics such as:
- Profit & Loss (PnL)
- Win Rate
- Trade Frequency
- Average Trade Size
- Long/Short Ratio
- Daily Profitability
- Trader Activity Score

### Exploratory Analysis
- Sentiment vs profitability trends
- Trader behavior during fear and greed phases
- Distribution of winning vs losing trades
- Correlation between metrics

### Machine Learning
Built a **Random Forest Classifier** to predict profitable trades.

**Model Accuracy:** `74%`

### Trader Segmentation
Clustered users into trading archetypes such as:
- Aggressive Traders
- Conservative Traders
- High-Frequency Traders
- Opportunistic Traders

---

## Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/your-username/primetrade-trader-sentiment-analysis.git
cd primetrade-trader-sentiment-analysis
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run Jupyter notebook
```bash
jupyter notebook
```
### 4. Open
```bash
analysis.ipynb
```

---
## Results & Insights

### Market Sentiment Impact
- Greed phases showed higher trade frequency.
- Fear phases showed lower participation but selective profitability.

### Trader Behavior
- Successful traders adjusted trade size based on sentiment.
- Overtrading during extreme greed reduced returns.

### Business Recommendations
- Launch premium sentiment-based signals.
- Build trader retention campaigns during fear markets.
- Introduce risk alerts during extreme greed periods.
- Personalize trader dashboards by segment.

---

## Sample Visualizations
Stored inside the charts folder:
```bash
/charts
```



- PnL Distribution
- Correlation Heatmap
- Sentiment vs Win Rate
- Trader Segmentation Plot
- Trade Frequency Trends

---

## Future Improvements
- Use XGBoost / LightGBM for better accuracy.
- Real-time API integration.
- Deep learning sequence models.
- Dashboard using Streamlit / Power BI.
- Portfolio optimization engine.

---

## Author
Riya Kesharwani

---

## License
This project was developed as part of the Primetrade.ai internship assignment and is shared for portfolio demonstration purposes.








