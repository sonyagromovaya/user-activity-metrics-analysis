# User Activity Analysis

Google Sheets homework using an e-commerce dataset. I looked at how many different users made purchases each day, week and month.

## What I did
- Filtered purchase events and worked with dates.
- Calculated DAU, WAU and MAU using unique user IDs.
- Compared DAU/MAU and WAU/MAU and made line charts.

## Results
- March had the highest MAU: **377 users**.
- Daily activity was fairly stable, with about **10–12 users per day** on average in most full months.
- DAU/MAU stayed around **0.03** and WAU/MAU around **0.23** from January to June.
- July's MAU was only **70**, but July is incomplete in the dataset, so I wouldn't compare it directly with full months.

## Tools
Google Sheets: FILTER, SORT, UNIQUE, COUNTUNIQUE, VLOOKUP, XLOOKUP, AVERAGEIFS.

## Google Sheets
[View my original spreadsheet](https://docs.google.com/spreadsheets/d/1b_Ih-sXn4wI-4aLjGKxZpMaKLzJXSrdmBZiwCtukKm8/edit?usp=sharing)

## Files
- `workbook/` — my full spreadsheet, including formulas and charts (Excel export).
- `charts/` — images of the charts.

*This is a course dataset. Some Google Sheets formulas, such as COUNTUNIQUE, may not recalculate correctly in Excel; the original analysis was done in Google Sheets.*
