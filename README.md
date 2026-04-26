# Investigating the Heterogeneity of Technology Stock Returns Amidst the AI Surge (2021–2025)

## 1. Project Overview

### Research Question
**Did all AI-related technology stocks benefit equally during the AI boom?**

### Motivation
Since 2022, the rapid development of artificial intelligence (AI) has significantly influenced financial markets. Many investors believe that all technology stocks have benefited from the AI boom. However, this assumption may not be accurate. This project aims to test whether the benefits of the AI surge were evenly distributed or concentrated in specific sectors.

### Target Audience
- **Beginner Investors**: To understand that major trends do not guarantee uniform returns.
- **Undergraduate Students**: To learn how to use data science tools (Python) to verify economic assumptions.

---

## 2. Features

* **Automated Pipeline**: Reads and cleans financial data from `acc102 data.xlsx`.
* **Key Financial Metrics**:
    * **Annualized Returns**: Measures long-term average growth.
    * **Cumulative Returns**: Tracks total wealth accumulation over 5 years.
    * **Volatility (Standard Deviation)**: Assesses the risk profile of high-growth stocks.
* **Data Visualization**: Generates professional bar charts to reveal performance dispersion.
* **Automatic Export**: All results and charts are saved to a dedicated `outputs/` folder.

---

## 3. Prerequisites

To run the script, ensure you have the following libraries installed:

**pip install pandas numpy matplotlib openpyxl**

---

## 4. Project Structure

* **Untitled1.ipynb**: The core analysis script (Jupyter Notebook).
* **acc102 data.xlsx**: Source dataset containing historical stock prices.
* **outputs/**: Automatically generated folder containing:
    * **yearly_return_bar_chart.png**: Visual comparison of returns.
    * **financial_metrics.csv**: Detailed calculation results.

---

## 5. Usage

1. **Prepare Data**: Place `acc102 data.xlsx` in the project root directory.
2. **Configuration**: The script is pre-configured to analyze seven stocks: `MSFT, NVDA, AMD, TSM, PLTR, ADBE, CRM`.
3. **Run Analysis**: Execute all cells in `Untitled1.ipynb`.
4. **Check Results**: View the summary output and check the `outputs/` folder for visual reports.

---

## 6. Key Findings & Reflection

* **Uneven Distribution**: The AI boom was not a "rising tide for all." **NVDA** emerged as the clear leader (infrastructure provider), while software giants like **ADBE** and **CRM** showed significantly lower growth.
* **Risk-Reward Awareness**: High-return stocks like **PLTR** also exhibited higher volatility, reminding investors that risk must be evaluated alongside returns.
* **Data vs. Narrative**: This project demonstrates that market narratives should always be verified with quantitative data rather than accepted at face value.

---

**Note**: Please ensure the Excel file column headers match the ticker symbols exactly for accurate processing.

---
