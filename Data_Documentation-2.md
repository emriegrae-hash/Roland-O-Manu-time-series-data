# Data Documentation — Manufacturers' New Orders: Total Manufacturing (AMTMNO)

## 1. Dataset Overview

| Field | Detail |
|---|---|
| Dataset name | Manufacturers' New Orders: Total Manufacturing |
| Series ID | AMTMNO |
| Source | U.S. Census Bureau, via FRED (Federal Reserve Bank of St. Louis) |
| Source URL | https://fred.stlouisfed.org/series/AMTMNO |
| File | AMTMNO.csv |
| Periodicity | Monthly |
| Coverage | February 1992 – July 2026 (414 observations) |
| Units | Millions of U.S. dollars |
| Seasonal adjustment | Seasonally adjusted |

## 2. Data Dictionary

| Variable Name | Readable Name | Units | Allowed Values | Definition |
|---|---|---|---|---|
| `observation_date` | Observation Date | Calendar date (YYYY-MM-DD) | 1992-02-01 to 2026-07-01, monthly | The calendar month the record applies to. |
| `AMTMNO` | Manufacturers' New Orders | Millions of $ | 223,500 to 665,895 | The total dollar value of new orders received by U.S. manufacturers that month, net of cancellations, seasonally adjusted. |


## 3. Data Collection Methodology

This data is collected by the U.S. Census Bureau through the Manufacturers' Shipments, Inventories, and Orders (M3) Survey, a monthly voluntary survey of U.S. manufacturers. About 3,000 companies (roughly 4,700 reporting units) report their shipments, new orders, and inventories directly to the Census Bureau each month.

The survey is released monthly: an advance estimate comes out about a week after month-end, followed by a full report with revisions about a month later. Because the reporting panel isn't randomly sampled, results depend on how representative the participating companies are of the overall manufacturing sector, and historical values can be revised in later releases.

## 4. Why This Dataset Intrigues Me

What intrigues me about this dataset is that it's real-life manufacturing data that shows real seasonality. When new orders spike or drop sharply, it cascades downstream — capacity gets tight or slack, suppliers get squeezed or under-utilized, and inventory strategy has to shift. Practicing forecasting on this series is practicing the exact skill of anticipating that cascade before it hits.
