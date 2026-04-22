# ACC102 Track 2: S&P 500 Return and Volatility Analysis (2020–2024)

## 1. Analytical Problem & Target User
This project analyses the return and risk performance of the S&P 500 index over 2020–2024 to support evidence-based investment understanding.
Target users: finance students, individual investors, and researchers studying U.S. equity market trends.

## 2. Dataset Information
- Source: WRDS CRSP dsi table
- Variables: date, sprtrn (daily simple return)
- Period: 2020-01-01 to 2024-12-31
- Access date: 15 April 2026
- Data quality: authoritative, widely used in financial research

## 3. Python Workflow & Methods
- Data extraction: wrds package + SQL query
- Data cleaning: datetime conversion, missing value removal
- Core analysis: cumulative return, average daily return, annualised volatility
- Visualisation: matplotlib line plot of cumulative return
- Output: cleaned dataset exported to Excel for further use

## 4. Key Insights
- The S&P 500 achieved strong long-term cumulative growth.
- Noticeable short-term fluctuations correspond to major market events.
- Annualised volatility quantifies the historical investment risk.
- Results demonstrate the risk–return profile of a passive buy-and-hold strategy.

## 5. Repository Structure
- main.ipynb: complete analytical workflow
- README.md: project documentation
- requirements.txt: package dependencies
- cleaned_data.xlsx: processed output
- demo_video.mp4: project demonstration

## 6. How to Run
1. Install required packages: wrds, pandas, matplotlib, openpyxl
2. Log in with valid WRDS credentials
3. Run all cells in Jupyter Notebook
4. View charts and exported Excel output

## 7. Limitations and Future Improvements
- Descriptive analysis only; no forecasting or regression modelling
- Excludes dividends, inflation, and transaction costs
- Future steps: add Sharpe ratio, multi-index comparison, and interactive visualisation

## 8. Demo Video Link
https://video.xjtlu.edu.cn/Mediasite/Play/b6f2f9e7dbf74938b45d5a1af63f49df1d
