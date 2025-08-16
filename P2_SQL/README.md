# FINC612 Assignment 01 - Part 2: DAX Stock Analysis

## Project Overview

This project focuses on DAX stock index analysis using Python. It extracts stock codes from Wikipedia, downloads historical price data from Yahoo Finance, and performs data cleaning, visualization, and analysis.

## File Structure

```
Part2_SQL/
├── DAX_Analysis_Part2.ipynb     # Main analysis Jupyter Notebook
└── DAX.db                       # Cleaned stock price database
```

## Project Content

### Main Features

1. **Data Acquisition and Preprocessing**
   - Extract DAX index constituent stock codes from Wikipedia
   - Download historical price data from Yahoo Finance (2020-2025)
   - Data cleaning and normalization

2. **Data Visualization**
   - Identify top 5 and bottom 5 performing stocks
   - Generate stock price trend comparison charts
   - Include DAX index as benchmark

3. **Data Analysis**
   - Calculate stock performance rankings
   - Analyze driving factors of best-performing stocks
   - Provide investment insights

### Technology Stack

- **Python**
- **pandas** - Data processing and analysis
- **yfinance** - Yahoo Finance data acquisition
- **matplotlib/seaborn** - Data visualization
- **sqlite3** - Database storage
- **requests/beautifulsoup4** - Web scraping

## System Requirements

### Requirements
- Python 3.8 or higher
- Jupyter Notebook
- Stable internet connection

### Data Sources
- **Stock codes**: Wikipedia DAX page
- **Price data**: Yahoo Finance API
- **Time period**: January 1, 2020 - August 14, 2025

### Data Cleaning Steps
1. Remove stocks with more than 30 NaN values
2. Exclude rows containing any NaN values
3. Price normalization (divide by earliest price)
4. Rename DAX index code

## Analysis Results

### Key Findings
- Identified best and worst performing stocks in DAX index
- Analyzed driving factors of best-performing stocks
- Provided data-driven investment recommendations

### Visualization Content
- Stock price trend comparison charts
- Performance ranking charts
- Risk-return analysis
