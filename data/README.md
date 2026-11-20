# Data

The analysis uses six spreadsheets from the Bank of England's yield curve statistics page:
https://www.bankofengland.co.uk/statistics/yield-curves

They are not included in this repository. Download them into this folder, keeping these names:

| File | What it is |
|---|---|
| `OIS_daily_data_2016_to_2024.xlsx` | OIS curves, daily, archive |
| `OIS_daily_data_2025_to_present.xlsx` | OIS curves, daily, archive |
| `OIS_daily_data_current_month.xlsx` | OIS curves, daily, latest month |
| `GLC_Nominal_daily_data_2016_to_2024.xlsx` | Nominal government liability (gilt) curves, daily, archive |
| `GLC_Nominal_daily_data_2025_to_present.xlsx` | Nominal government liability (gilt) curves, daily, archive |
| `GLC_Nominal_daily_data_current_month.xlsx` | Nominal government liability (gilt) curves, daily, latest month |

The report uses data to 5 October 2026. The Bank replaces the current-month files each month, so running the notebook with newer files updates every number to the latest date. The trade levels and the pre-war reference date are set in the notebook's setup cell.

Please credit the Bank of England as the source of the data when reusing any results.
