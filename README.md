# ACC102 Individual Assignment: Financial Performance Analysis of US Airlines (2021-2025)

## Project Overview
This project analyzes the financial performance of four major U.S. airlines (AAL, DAL, LUV, UAL) from 2021 to 2025, using data from the WRDS Compustat database. It includes data extraction, cleaning, ratio calculation, and visualization to explore profitability trends across the industry.

## Key Features
- Extract 5-year financial data for four major airlines via WRDS API
- Clean and preprocess raw data (remove duplicates, handle missing values, filter outliers)
- Calculate core financial ratios: net profit margin and operating profit margin
- Generate a line chart of net income trends
- Export cleaned data and summary statistics to Excel files

## Project Structure
- fly.py: Main script containing the complete workflow (data extraction, cleaning, analysis, visualization)
- airlines_clean_data.xlsx: Full cleaned financial dataset
- airlines_analysis_summary.xlsx: Summary statistics of key financial metrics
- airline_net_income_trend.png: Visualization of net income trends

## How to Run
1. Install required libraries first:
pip install wrds pandas matplotlib numpy openpyxl

2. Run the script. When prompted, enter your WRDS username and password, then input the tickers to analyze (e.g., AAL,DAL,LUV,UAL).

3. Output files will be saved to the current project directory.
