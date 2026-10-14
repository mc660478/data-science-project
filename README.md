# Macao Residential Property Price Index: Q3 Comparison, 2020–2025

## Research question
How did Macao's overall residential property price index change between the third quarters of 2020 and 2025?

## Dataset source and usage
The six values in this project are transcribed from the Macao Statistics and Census Service (DSEC), *Residential Property Price Index, July–September 2025*. The report includes a comparison table of third-quarter values for 2020–2024 and reports the Q3 2025 overall index in the same publication.

Official source:
https://www.dsec.gov.mo/getAttachment/bde05008-86a7-4395-a616-c5c54ad617bb/E_IPH_FR_2025_M09.aspx

The index is based on 2011 = 100. This project retains attribution to DSEC. Check the source publisher's terms before reusing the original material.

## Methods and tools
- Python
- pandas for organizing the data and calculating percentage changes
- Matplotlib for two visualizations
- Descriptive comparison of the third-quarter index from 2020 to 2025

## Key findings
- The index changed only slightly from 269.0 in Q3 2020 to 269.3 in Q3 2021.
- It then declined in each of the following Q3 observations, reaching 191.6 in Q3 2025.
- The Q3 2025 index was about 28.8% lower than the Q3 2020 index.

These are descriptive findings; they do not establish the causes of price changes.

## One limitation
The project uses only six observations of an overall price index. It does not include household income, mortgage costs, transaction-level prices, or differences between property types. Therefore, it cannot directly measure housing affordability.

## Files
- `project.ipynb`: reproducible analysis and code
- `requirements.txt`: Python packages needed to run the notebook
- `figures/property_price_index_trend.png`: trend visualization
- `figures/q3_year_on_year_change.png`: percentage-change visualization

## How to run
1. Install Python 3 and Jupyter Notebook (or use Google Colab).
2. Install dependencies with `pip install -r requirements.txt`.
3. Open `project.ipynb`.
4. Run all cells from top to bottom.

The data values are included in the notebook, so the analysis does not require a separate download to run. If you update the data, verify the values against the latest DSEC publication and update the source citation.
