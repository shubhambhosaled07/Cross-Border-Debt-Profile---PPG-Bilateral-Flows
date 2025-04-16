# Cross-Border Debt Profile - PPG Bilateral Flows

## Objective

Recent headlines such as "South Asia in Chinese Debt Trap", "Economic Crisis in Sri Lanka", and "Failing Economy of Pakistan" sparked my curiosity about bilateral lending relationships between countries.

This project explores PPG (Public and Publicly Guaranteed) Bilateral Debt between India and its neighboring countries—Bangladesh, Bhutan, Sri Lanka, Nepal, Maldives, and Myanmar—using the World Bank API.

The goal is to analyze 20 years of bilateral lending trends and visualize the data in a user-friendly Excel dashboard.
📄 Check out the full project report (https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Project%20Report.pdf)


## About the dataset

The dataset captures PPG bilateral debt between India and six neighboring countries. Data is sourced from the World Bank API and includes:

Year: Year of debt data
Debtor: Debtor country code
Debt in US$: Amount of debt in USD
YoY Growth %: Year-on-year growth of bilateral debt
All individual datasets are cleaned, merged, and analyzed.

📈 View the full Excel analysis(https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Bilateral%20Debt%20Analysis.xlsx)

## Guidelines to use the script:

1) Find Debtor Country Code
🔹 Run the Debtor Country Code script(https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Python%20Scripts/Debtor%20Country%20Code%20Script.py)
🔸 Or download the Excel file(https://github.com/indtheblacktiger/International-Debt-Statistics/raw/main/Country%20Code%20Data/Debtor%20Country%20Code.xlsx)

2) Find Creditor Country Code
🔹 Run the Creditor Country Code script(https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Python%20Scripts/Creditor%20Country%20Code%20Script.py)
🔸 Or download the Excel file(https://github.com/indtheblacktiger/International-Debt-Statistics/raw/main/Country%20Code%20Data/Creditor%20Country%20Code.xlsx)

3) Extract Bilateral Debt Data
💾 Use the PPG Bilateral Debt script to download the data into Excel format.(https://github.com/indtheblacktiger/International-Debt-Statistics/blob/main/Python%20Scripts/PPG%20Bilateral%20Debt%20Script.ipynb)

## Conclusion of project

1) Total PPG bilateral lending rose from < $500 million in 2000 to ~$45 billion in 2020
2) Bhutan is the largest debtor with ~$18 billion over 20 years
3) Nepal received the least, with < $1 billion in total
4) Bilateral lending has shown a consistent upward trend
5) India's bilateral lending to neighbors is ~1.2% of its total GDP
6) In case of default by any of these countries, the impact on India's financial sector is likely minimal (based on this data alone)