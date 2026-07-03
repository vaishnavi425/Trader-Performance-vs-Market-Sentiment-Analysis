# Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on the Hyperliquid trading platform. The objective is to understand how market sentiment influences trader profitability and behavior and to derive actionable trading insights.

---

## Objective

* Analyze the impact of Fear and Greed market sentiment on trader performance.
* Compare trading behavior under different market conditions.
* Identify profitable trader segments.
* Generate actionable recommendations based on data analysis.

---

## Dataset

### 1. Bitcoin Fear & Greed Index

* Daily market sentiment
* Columns include:

  * Date
  * Classification (Fear / Greed)

### 2. Historical Trader Data

* Hyperliquid trading history
* Includes:

  * Account
  * Coin
  * Execution Price
  * Size (USD & Tokens)
  * Direction
  * Closed PnL
  * Fee
  * Timestamp
  * Transaction Details

---

## Project Workflow

1. Import Libraries
2. Load Datasets
3. Data Cleaning
4. Data Exploration
5. Timestamp Conversion
6. Dataset Merging
7. Feature Engineering
8. Exploratory Data Analysis (EDA)
9. Trader Segmentation
10. Business Insights
11. Strategy Recommendations

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Analyses Performed

* Missing Value Analysis
* Duplicate Detection
* Daily PnL per Trader
* Win Rate Analysis
* Trade Frequency Analysis
* Average Trade Size Analysis
* Long vs Short Analysis
* Trader Segmentation
* Fee Analysis
* Fear vs Greed Performance Comparison
* Correlation Analysis
* Profit Distribution

---

## Key Insights

* Trader profitability varies significantly across market sentiment conditions.
* A small percentage of traders contribute to a large portion of total profits.
* Trade frequency and trade size change under different market sentiments.
* Trader segmentation helps identify consistent winners and higher-risk trading behavior.

---

## Strategy Recommendations

* Apply conservative position sizing during Fear markets.
* Focus on disciplined trading instead of increasing trade frequency.
* Monitor trader segments separately for better risk management.
* Use sentiment indicators as supporting signals rather than standalone trading signals.

---

## How to Run

1. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

2. Open the Jupyter Notebook.

3. Run all cells from top to bottom.

---

## Project Structure

```
Trader-Performance-vs-Market-Sentiment-Analysis/
│
├── Trader_Performance_Analysis.ipynb
├── historical_data.csv
├── fear_greed_index.csv
├── README.md
├── Report.md
├── requirements.txt   
```
