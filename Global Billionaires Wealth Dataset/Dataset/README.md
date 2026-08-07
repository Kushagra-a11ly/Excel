Global Billionaires Wealth Dataset
Overview

This project contains a dataset profiling the world's wealthiest individuals, combining personal, financial, and demographic information with country-level economic and social indicators. It is designed to support exploratory data analysis, visualization, and research into global wealth distribution and its relationship with national economic factors.

Project Purpose

The goal of this project is to analyze patterns in global billionaire wealth — such as which countries and industries produce the most billionaires, how self-made status varies by region, and how national economic indicators (GDP, tax rates, life expectancy, population) correlate with individual wealth outcomes.

Dataset Description

Each row in the dataset represents one individual on the billionaires list. The columns are grouped as follows:

Personal Information
Rank – Position on the wealth ranking list
Person Name – Full name of the individual
Firstname / Lastname – Individual's first and last name
Gender – Gender of the individual
Age – Current age
Birthyear / Birthmonth / Birthday – Date of birth details
Self Made – Indicates whether the individual is self-made or inherited their wealth
Wealth & Source
Finalworth – Estimated net worth
Category – Wealth/industry category the individual is associated with
Source – Primary source of wealth
Industries – Industry or industries the individual operates in
Location
Country – Country of residence/citizenship
Region – Broader geographic region
City – City of residence
Country-Level Indicators
Cpi_Country – Consumer Price Index of the individual's country
Gdp_Country – Gross Domestic Product of the country
Life_Expectancy_Country – Average life expectancy in the country
Tax_Revenue_Country_Country – Tax revenue as a percentage of GDP
Total_Tax_Rate_Country – Total tax rate applicable in the country
Population_Country – Total population of the country
Use Cases
Analyzing global wealth distribution by country, region, and industry
Studying the relationship between national economic indicators and billionaire wealth
Comparing self-made vs. inherited wealth trends across demographics
Visualizing wealth concentration geographically
Dashboard

In addition to the raw dataset, an interactive dashboard has been developed to visualize key insights from the data, including wealth distribution by country and region, industry breakdowns, self-made vs. inherited wealth trends, and correlations with national economic indicators.

Tool Used: Specify tool here (e.g., Power BI, Tableau, Streamlit)
Access/Preview: Add link or screenshot of the dashboard here
Key Features:
Interactive filters by country, region, and industry
Visual comparison of billionaire wealth against GDP, tax rates, and population
Ranking and demographic breakdowns (age, gender, self-made status)
Repository Structure
Global Billionaires Wealth Dataset/
└── Dataset/
    ├── Global Billionaires Wealth Dataset.xlsx   # Main dataset file
    └── README.md                                  # Project documentation
Getting Started
Clone or download this repository.
Open Global Billionaires Wealth Dataset.xlsx from the Dataset folder in Microsoft Excel or Google Sheets.
Refer to the column descriptions above to understand the data structure.
Use Excel features (PivotTables, charts, filters) or connect to your preferred BI tool to begin analysis.
Notes
Some columns (e.g., Population_Country) may appear duplicated in the raw source data and should be reviewed/cleaned before analysis.
Ensure proper handling of missing or null values, particularly in demographic and country-level fields.
License

Specify the appropriate license for this dataset and project here.
