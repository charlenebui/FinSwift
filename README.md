# Financial Analysis Automation Tool

## Overview
This Python-based tool provides automated financial comparison and analysis for public companies using real-time data from Yahoo Finance. It generates comprehensive financial metrics and visualizations, reducing calculation time by approximately 99% compared to traditional Excel-based methods.

## Features
- Automated retrieval of financial statements (Income Statement, Balance Sheet, Cash Flow)
- Multiple company comparison in a single run
- Key financial metrics calculation:
  - EBIT (Earnings Before Interest and Taxes)
  - EBITDA (Earnings Before Interest, Taxes, Depreciation, and Amortization)
  - ROA (Return on Assets)
  - ROE (Return on Equity)
  - Net Profit Margin
  - Gross Profit Margin
  - Earnings Per Share
- Visualization of all metrics through plots and comparison tables
- Historical comparison across multiple years (2020-2023)

## Requirements
- Python 3.x
- pandas
- yfinance
- matplotlib

## Installation

```bash
pip install pandas yfinance matplotlib
```

## Usage

```python
# Import data from yahoo finance
import yfinance as yf
import os
import pandas as pd

# Download matplotlib
!pip install matplotlib
import matplotlib.pyplot as plt
%matplotlib inline
```

1. Run the script
2. Enter the number of companies you want to compare
3. Input the ticker symbols for each company (e.g., AMZN, WMT, ORCL, CRM)
4. The tool will automatically generate comparison tables and visualizations

## Example Output
The tool will generate:
- Financial metric tables for direct numeric comparison
- Bar charts for EBIT and EBITDA comparisons
- Line charts for ROA, ROE, profit margins, and EPS trends

## Benefits
- Real-time data integration from Yahoo Finance
- Significant time savings compared to manual Excel analysis
- Ability to analyze multiple companies simultaneously
- Visual representations for easier trend identification
- Historical performance tracking across multiple years

## Limitations
- Requires companies to have sufficient historical data (at least 4 years)
- Depends on the accuracy of Yahoo Finance data
- Some newer companies may not have complete datasets

## Future Improvements
- Add more financial ratios and metrics
- Implement industry benchmarking
- Enable custom date ranges
- Add export functionality for reports

## License
[Your License Here]
