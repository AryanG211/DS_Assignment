<h1 align="center">Market Sentiment Impact on Crypto Trading</h1>

<p align="center">
  <em>Data Science Analysis of Market Psychology and Real Trading Behavior</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Colab-%23F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-%23150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-%23013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff?style=for-the-badge&logo=matplotlib&logoColor=black" />
  <img src="https://img.shields.io/badge/CSV-Datasets-gray?style=for-the-badge" />
</p>

---

## Overview

This project investigates how the Fear & Greed Index influences actual cryptocurrency trading activity.  
All data processing, merging, sentiment labeling, and visual analysis were conducted in a Google Colab environment.

The study evaluates whether traders behave differently under various sentiment conditions such as Extreme Greed, Greed, Neutral, Fear, and Extreme Fear.  
Key behavioral metrics include position size, trade volume, price distribution, buy vs sell patterns, and profitability variation.

---

## Project Structure

ds_<candidate_name>/
├── notebook_1.ipynb # Main analysis notebook (Google Colab)
├── csv_files/ # Raw and merged input datasets
│ └── *.csv
├── outputs/ # All generated graphs and visualizations
│ └── *.png / *.jpg
├── ds_report.pdf # Final 2-page summary report
└── README.md


---

## Colab Notebook

Open the main processing and analysis notebook here:

*Colab Link:* Paste your link here after uploading notebook_1.ipynb  
Example:  
https://colab.research.google.com/drive/XXXX

---

## Analysis Description

The project examines whether trader decisions exhibit measurable changes when market sentiment shifts.  
The analysis focuses on:

- Position size variation (tokens)  
- Differences in trade volume (USD)  
- Buy vs Sell behavior patterns  
- Execution price distributions  
- Profitability (Closed PnL) behavior  
- Sentiment frequency distributions  

All insights are supported by plots saved in the outputs/ folder.

---

## Visualizations Generated

The exploratory data analysis produces the following charts:

- Average Position Size vs Market Sentiment  
- Average Trade Volume vs Market Sentiment  
- Buy vs Sell Count Comparison Across Sentiments  
- Execution Price Distribution Across Sentiments  
- Profitability (Closed PnL) Distribution Across Sentiments  
- Sentiment Frequency Bar Chart  

These figures illustrate how traders respond when market psychology shifts toward fear or greed.

---

## Report Summary

The document ds_report.pdf contains:

- Introduction  
- Dataset overview  
- Methodology  
- Visual results with interpretations  
- Key findings  
- Conclusion and future extensions  

The report remains concise at two pages, following assignment requirements.

---

## Tools & Technologies

| Category | Tools |
|---------|-------|
| Analysis Environment | Google Colab |
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Storage | CSV datasets |

---

## How to Reproduce the Analysis

1. Open the project notebook using the Colab link above.  
2. Upload all CSV files into the csv_files/ directory in the Colab file explorer.  
3. Run all notebook cells in sequence.  
4. Generated charts will automatically be saved to the outputs/ folder.  

---
