# econ3916-lab01-data-portfolio
# The Data Portfolio — Big Mac Index Analysis

## Objective

This project analyzes The Economist’s Big Mac Index to examine international price differences, purchasing power parity, currency valuation, and missing-data patterns.

## Methodology

* Loaded and explored a panel dataset covering 57 countries and 45 time periods from April 2000 to July 2026
* Distinguished among cross-sectional, time-series, and panel data structures
* Calculated implied purchasing power parity exchange rates and currency valuation percentages
* Compared countries using the July 2024 cross-section
* Diagnosed incomplete panels and classified missing-data mechanisms
* Created a cross-sectional valuation bar chart and a time-series comparison

## Key Findings

* The July 2024 cross-section contains 54 countries.
* Switzerland was approximately 41.8% overvalued relative to the United States in July 2024 and has remained persistently overvalued.
* Japan was undervalued on average in every decade covered by the dataset.
* Russia’s departure from the dataset was classified as MNAR because its missingness was associated with McDonald’s exit following geopolitical sanctions.
* Removing countries with incomplete panels could bias the average PPP deviation because these countries are not missing randomly.

## Tools

Python, pandas, NumPy, Matplotlib, and Google Colab

## Data Source

[The Economist’s Big Mac Index](https://github.com/TheEconomist/big-mac-data)
