# Hotel Booking Analysis

Exploratory data analysis of 119,390 hotel booking records (city and resort hotel) to understand cancellations, pricing and guest behavior.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly (Google Colab)

## What I did
- Cleaned the data: removed 31,994 duplicates, dropped `company` (94% missing), filled missing `agent`, `children` and `country`, and removed invalid rows (87,229 rows remained)
- Descriptive statistics and visualizations
- Time series analysis of bookings and ADR
- Segmentation by market segment, customer type and domestic vs international guests
- Cancellation analysis by lead time, special requests, day of week and deposit type
- Answered 10 objective and 5 subjective business questions

## Key findings
- About 27.5% of bookings are cancelled
- Cancellation rises with lead time: about 16% (0-30 days) to about 41% (over a year ahead)
- Guests with special requests cancel far less
- Online TA has the highest cancellation rate among main segments (about 35%)
- August is the busiest month and has the highest ADR
- Domestic (Portuguese) guests cancel more than international guests (about 36% vs 24%)

## Recommendations
Deposits for long-lead bookings, stricter terms for Online TA bookings, seasonal pricing, encouraging special requests, and loyalty perks for repeated guests.
