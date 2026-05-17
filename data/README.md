# Data

This folder contains all datasets used in the DATA 606 Capstone project:

## Identifying U.S. Counties at Risk of Economic Decline Using Public Socioeconomic Indicators

The data consists of county-level socioeconomic indicators collected from the U.S. Census Bureau’s American Community Survey (ACS) 5-Year Estimates.

---

# Data Sources

The project uses the following ACS datasets:

| Dataset | Description |
|---|---|
| `ACSDT5Y2024.B01003-Data.csv` | Total population data |
| `ACSDT5Y2024.B15003-Data.csv` | Educational attainment data |
| `ACSDT5Y2024.B17001-Data.csv` | Poverty statistics |
| `ACSDT5Y2024.B19013-Data.csv` | Median household income |
| `ACSDT5Y2024.B23025-Data.csv` | Employment and unemployment data |
| `ACSDT5Y2024.B25003-Data.csv` | Housing and homeownership data |

---

# Processed Datasets

| File | Description |
|---|---|
| `county_master.csv` | Cleaned and merged county-level dataset |
| `county_risk_app_ready.csv` | Final processed dataset used in the Streamlit application |

---

# Dataset Description

Each row in the processed dataset represents a single U.S. county and includes socioeconomic indicators such as:

- Population
- Median household income
- Poverty rate
- Unemployment rate
- Educational attainment
- Homeownership rate
- Economic risk score
- Risk category

---

# Key Features

The final dataset includes:

| Feature | Description |
|---|---|
| `county_fips` | Unique county identifier |
| `county_name` | County and state name |
| `total_population` | County population |
| `median_household_income` | Median household income |
| `poverty_rate` | Percentage below poverty line |
| `unemployment_rate` | Percentage unemployed |
| `bachelors_or_higher_pct` | Percentage with bachelor’s degree or higher |
| `homeownership_rate` | Percentage of owner-occupied housing |
| `economic_risk_score` | Composite economic risk metric |
| `risk_category` | Low / Medium / High risk classification |

---

# Data Processing Overview

The datasets were:

- Downloaded from the U.S. Census Bureau ACS portal
- Cleaned and standardized
- Merged using county FIPS codes
- Transformed into interpretable socioeconomic indicators
- Used for exploratory analysis, modeling, and dashboard visualization

---

# Data Source

U.S. Census Bureau – American Community Survey (ACS) 5-Year Estimates

🔗 [U.S. Census Bureau ACS Data](https://data.census.gov/)

---

# Folder Structure

```text
data/
│
├── ACSDT5Y2024.B01003-Data.csv
├── ACSDT5Y2024.B15003-Data.csv
├── ACSDT5Y2024.B17001-Data.csv
├── ACSDT5Y2024.B19013-Data.csv
├── ACSDT5Y2024.B23025-Data.csv
├── ACSDT5Y2024.B25003-Data.csv
├── county_master.csv
├── county_risk_app_ready.csv
└── README.md
```
