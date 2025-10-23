# Trader Behavior Analysis

This repository contains the completed data science assignment for the Junior Data Scientist – Trader Behavior Insights role.

##  KAG-365 Assignment Overview

The project's objective is to analyze the relationship between trader performance (profitability, volume, risk) and the Bitcoin market sentiment (Fear & Greed Index).

The analysis is contained in the `notebook_1.ipynb` file, which loads, cleans, merges, and visualizes the provided datasets. The final insights and chart explanations are summarized in `ds_report.pdf`.

## Repository Structure

The submission follows the required format:

ds\_hari\_sri\_venu\_gopal/
│
├── notebook\_1.ipynb         \# The main Google Colab notebook with all code.
├── ds\_report.pdf            \# The final report explaining insights and charts.
│
├── csv\_files/
│   └── daily\_behavior\_summary.csv \# Processed data created by the notebook.
│
└── outputs/
├── 1\_volume\_vs\_sentiment.png
├── 2\_pnl\_vs\_sentiment.png
├── 3\_risk\_vs\_sentiment.png
└── 4\_correlation\_heatmap.png

## How to Run

1.  The primary file is **`notebook_1.ipynb`**.
2.  It is designed to be run in **Google Colab**.
3.  The notebook will automatically install any required libraries (like `gdown`) and download the raw datasets from the provided Google Drive links.
4.  Running all cells (`Runtime > Run all`) will regenerate the `csv_files/` and `outputs/` folders and all their contents.

## Tools Used

* **Python**
* **Google Colab**
* **Pandas:** For data loading and manipulation.
* **Matplotlib & Seaborn:** For data visualization.
  
