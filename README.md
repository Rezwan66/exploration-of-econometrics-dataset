# exploration-of-econometrics-dataset
---
This is an analysis of the 'Cost' and 'Impressions' metrics of a dataset of a company for different campaigns over time. The analysis is done using Python on Jupyter Notebook and common Excel functionalities.

---
Documentation of Tasks
---
1. Reformatted column widths
2. Edited all text size to same size, all font family to calibri, all text align to bottom align
3. Read the raw dataset and campaign lookup tab into Jupyter notebook using Pandas.
4. Checked for and dropped missing values and missing columns in both datasets.
5. Changed data type of the 'Impressions' column of the raw dataset into int64.
6. Extracting week number from date to aggregate the sum and mean values of the columns by week.
7. Focussing on and plotting weekly time-series charts for total weekly costs and impressions.
8. Dropped the Campaign and Daily Information columns to find that the aggregate data produce the same results.
9. Calculating relevant metrics for the entire dataset (sum, mean) at a top-line level.
10. Analyzing additional metrics at the top-line aggregated level and drilling down into a granular level
11. Slicing the data based on other relevant dimensions.
