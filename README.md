# NYSE Market Performance & Risk Analysis

## Project Overview
This project analyzes historical stock market data from the New York Stock Exchange (NYSE) to understand overall market trends, sector-wise performance, and the risk–return characteristics of stocks. The analysis combines Python-based data analytics with an interactive Power BI dashboard to deliver business-focused insights.

---

## Objectives
- Analyze overall NYSE market performance over time
- Evaluate sector-wise returns, volatility, and trading activity
- Study the risk vs return relationship at stock and sector levels
- Build an interactive dashboard for data-driven financial insights

---

## Dataset
Source: Kaggle – NYSE Stock Market Dataset

The dataset includes:
- Daily stock prices (open, high, low, close)
- Trading volume
- Company symbols
- Sector classification (GICS Sector)

Large datasets were pre-aggregated in Python to ensure optimal dashboard performance.

---

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Power BI
- Kaggle Notebook Environment

---

## Key Analysis Performed
- Data cleaning and preprocessing of historical stock price data
- Daily return and volatility calculation for risk assessment
- Sector-wise aggregation of returns, volatility, and volume
- Risk vs return analysis to identify stable and high-growth stocks
- Market trend and trading volume analysis using time-series data

---

## Dashboard Highlights
The Power BI dashboard contains two main pages:

Market Overview
- Average market price trend over time
- Trading volume activity
- Key performance indicators displayed using cards

Sector & Risk Analysis
- Sector-wise risk vs return comparison
- Sector dominance by number of listed companies
- Stock-level risk vs return scatter analysis
- Interactive slicers for date range and sector selection

---

## Key Insights
- Market performance and volatility vary significantly across sectors
- Higher returns are generally associated with higher risk
- Certain sectors dominate the NYSE in terms of company count
- Pre-aggregating large datasets improves dashboard performance without losing analytical depth

---

## Business Value
This project demonstrates how financial market data can be transformed into actionable insights using data analytics and visualization techniques. The analysis supports informed decision-making by highlighting market trends, sector behavior, and risk patterns.

---

## Project Structure
NYSE-Market-Performance-Analysis/
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_kpi_analysis.ipynb
│   ├── 03_market_trends.ipynb
│   └── 04_sector_risk_analysis.ipynb
│
├── powerbi/
│   └── nyse_dashboard.pbix
│
├── data/
│   └── dataset_source.txt
│
├── images/
│   ├── dashboard_overview.png
│   └── dashboard_sector_risk.png
│
└── README.md


---

## Conclusion
The NYSE Market Performance & Risk Analysis project showcases practical financial data analysis skills by combining Python analytics with interactive business intelligence dashboards. It reflects real-world analytical workflows used in finance and data analytics roles.
