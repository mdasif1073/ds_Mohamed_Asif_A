ds_Mohamed Asif

Data Science Assignment: Web3 Trading Team
This repository contains the submission for the Web3 Trading Team's data science assignment. The project explores the relationship between trader behavior and market sentiment using two datasets: historical Hyperliquid trading data and the Bitcoin Fear & Greed Index.

Repository Structure
ds_Mohamed Asif A/
├── notebook_1.ipynb     # Main Colab notebook with all analysis and code.
├── csv_files/           # Processed data outputs.
│   ├── trader_summary.csv
│   └── fear_greed_comparison.csv
├── outputs/             # Visual outputs and plots.
│   ├── exploratory_plots_dashboard.png
│   ├── fear_greed_comparison.png
│   ├── volume_vs_pnl.png
│   ├── sharpe_by_sentiment.png
│   ├── trader_clusters.png
│   └── model_roc.png
├── ds_report.pdf        # Final summarized insights and explanations.
└── README.md           
Getting Started
Clone the Repository:

Bash

git clone https://github.com/your-username/ds_<candidate_name>.git
Access the Notebook:
The core analysis and code are located in notebook_1.ipynb. This notebook is designed to be run in Google Colab. The code is well-commented and self-explanatory.

Data:
The project uses two CSV files hosted on Google Drive, with links provided within the Colab notebook for automatic download.

historical_data.csv - https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view
fear_greed_index.csv - https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

Project Overview
The analysis covers three main areas:

Exploratory Data Analysis (EDA): An initial deep dive into the data to understand the relationship between daily trading metrics (PnL, volume, etc.) and market sentiment (Fear vs. Greed).

Trader Segmentation: Unsupervised machine learning (K-Means Clustering) was used to segment traders into different behavioral profiles based on their trading habits.

Predictive Modeling: A supervised machine learning model (Random Forest) was built to predict the profitability of a trade, with SHAP used for model explainability to identify the key drivers of success.

Key Findings
Trade volume is significantly higher during periods of Greed.

Risk-adjusted returns are slightly better during periods of Fear, supporting a contrarian strategy.

Traders can be clustered into distinct behavioral groups.

A machine learning model can predict trade profitability with high accuracy, with key drivers including trade execution price and volume.