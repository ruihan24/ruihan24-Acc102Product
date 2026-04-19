# ACC102 Individual Assignment: Financial Performance Analysis of US Airlines (2021-2025)

## 1.Project Background & Problem Statement
This project addresses the need to evaluate the financial health and profitability trends of major U.S. airlines in the post-pandemic era. With significant volatility in the aviation industry, it aims to identify which carriers have maintained stable performance, improved their profit margins, or faced ongoing challenges between 2021 and 2025.

## 2.Data Description
The analysis uses data extracted from the WRDS Compustat database, focusing on four major U.S. airlines:
- American Airlines (AAL)
- Delta Air Lines (DAL)
- Southwest Airlines (LUV)
- United Airlines (UAL)

Key variables include annual operating revenue, net income, and operating profit, covering the fiscal years 2021 to 2025.

## 3.Methodology
The analysis follows a structured workflow:
1. Data Extraction: Pull financial records from WRDS using Python.
2. Data Cleaning: Remove duplicates, handle missing values, and filter out extreme outliers.
3. Financial Ratio Calculation: Compute net profit margin and operating profit margin to assess profitability.
4. Trend Analysis: Visualize net income trends using line charts to compare performance over time.
5. Summary Reporting: Generate descriptive statistics for key metrics.

## 4.Results & Key Findings
- The project produces a clear trend analysis of net income across the four airlines.
- It identifies periods of recovery, growth, or decline in profitability.
- The generated charts and tables highlight which carriers maintained stronger financial performance relative to peers.

## 5.How to Run
Run the Python script: When prompted, enter your WRDS username and password.
Input the airline tickers: Enter the tickers you wish to analyze (e.g., AAL,DAL,LUV,UAL).
Output generation: The script will generate a cleaned dataset, summary statistics, and a net income trend chart in your project directory.

## 6.Product / Demo Links
Source Code: https://github.com/ruihan24/ruihan24-Acc102Product
Generated Outputs (Excel & Chart): Included in the repository

## 7.Limitations & Future Improvements
Limitations: The analysis is limited to four major carriers and annual financial data. It does not account for external factors such as fuel prices, labor costs, or macroeconomic shocks.

Improvements: Future work could include quarterly data, additional airlines, and regression analysis to explore drivers of profitability.
