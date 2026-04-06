# Childcare-Costs-EDA
# U.S. Childcare Costs — Exploratory Data Analysis

Python/Pandas EDA examining the relationship between childcare costs and household income in the United States from 2008 to 2018.


---

## Dataset

34,567 records spanning 2008–2018. Key variables include median childcare costs for preschool (MCPreschool), median household income (MHI), and female labor force participation rate.

## Key Findings

- Childcare costs rose consistently year-over-year while median household income fluctuated, widening the affordability gap over time
- 2014 marked a critical inflection point: preschool costs surged **37.26%** while median household income declined **2.77%**
- Moderate positive correlation between female labor force participation and childcare costs — higher participation drives demand, but high costs also appear to discourage workforce entry in some clusters
- Income growth consistently lagged behind childcare cost growth across the study period

## Methods

- Year-over-year percent change analysis on childcare costs and household income
- Normalization using MinMaxScaler and log transformations to enable cross-variable comparison
- Correlation analysis between female labor force participation and childcare costs
- Data cleaning and handling of missing/inconsistent values

## Stack

Python, Pandas, NumPy, Matplotlib, scikit-learn

---

*Mary Kate Fitzpatrick — Northwestern University MSIS*
