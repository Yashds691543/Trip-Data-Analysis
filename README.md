# Trip-Data-Analysis
Data Analysis of two datasets using R programming
This R script performs a comprehensive analysis of Divvy bike share data:

Library Loading: It begins by loading essential libraries, including tidyverse for data manipulation and conflicted to manage function conflicts between packages.

Data Collection: The script reads CSV files containing bike trip data for different quarters.

Data Wrangling: It aligns the columns of datasets by renaming them for consistency, converts relevant data types, and combines the datasets into a single frame. Unnecessary columns are removed.

Data Cleanup: The script standardizes user type labels to match the current nomenclature, adds date components for aggregation, calculates ride lengths, and removes records with invalid or negative ride lengths.

Descriptive Analysis: It calculates and visualizes key statistics such as average ride length and compares ride data by user type and day of the week.

Export Summary: Finally, it aggregates and prepares data for further analysis, summarizing ride lengths by user type and day of the week.

The analysis of Divvy bike share data reveals key insights into ridership patterns:

Usage Patterns: The script shows how different user types (members vs. casual riders) utilize the bike share system. By analyzing average ride lengths and counts across days of the week, it provides a clear picture of usage trends.

Data Cleanup Effectiveness: The data cleaning steps ensured that only valid records were included in the analysis, enhancing the accuracy of the findings.

Day-of-Week Trends: Visualizations and summary statistics highlight differences in ride behavior between members and casual users, including variations in ride frequency and duration across different days.

Actionable Insights: The findings can guide operational improvements and marketing strategies, such as targeted promotions or adjustments in service based on observed usage patterns.

Overall, the script facilitates a detailed understanding of Divvy bike share usage, supporting data-driven decision-making for future enhancements and optimizations.







