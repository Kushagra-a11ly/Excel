# 💰 Global Billionaires Wealth Dataset

> A structured dataset and dashboard profiling the world's wealthiest individuals, enriched with country-level economic and social indicators.

![Excel](https://img.shields.io/badge/Data-Excel-217346?logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-Unspecified-lightgrey)

---

## 📖 Overview

This project contains a dataset profiling the world's wealthiest individuals, combining personal, financial, and demographic information with country-level economic and social indicators. It is designed to support exploratory data analysis, visualization, and research into global wealth distribution and its relationship with national economic factors.

## 🎯 Project Purpose

The goal of this project is to analyze patterns in global billionaire wealth, including:

- Which countries and industries produce the most billionaires
- How self-made status varies across regions
- How national economic indicators (GDP, tax rates, life expectancy, population) correlate with individual wealth outcomes

## 📊 Dataset Description

Each row represents one individual on the billionaires list. Columns are grouped as follows:

### Personal Information
| Column | Description |
|---|---|
| `Rank` | Position on the wealth ranking list |
| `Person Name` | Full name of the individual |
| `Firstname` / `Lastname` | Individual's first and last name |
| `Gender` | Gender of the individual |
| `Age` | Current age |
| `Birthyear` / `Birthmonth` / `Birthday` | Date of birth details |
| `Self Made` | Whether wealth is self-made or inherited |

### Wealth & Source
| Column | Description |
|---|---|
| `Finalworth` | Estimated net worth |
| `Category` | Wealth/industry category |
| `Source` | Primary source of wealth |
| `Industries` | Industry or industries the individual operates in |

### Location
| Column | Description |
|---|---|
| `Country` | Country of residence/citizenship |
| `Region` | Broader geographic region |
| `City` | City of residence |

### Country-Level Indicators
| Column | Description |
|---|---|
| `Cpi_Country` | Consumer Price Index of the country |
| `Gdp_Country` | Gross Domestic Product of the country |
| `Life_Expectancy_Country` | Average life expectancy |
| `Tax_Revenue_Country_Country` | Tax revenue as % of GDP |
| `Total_Tax_Rate_Country` | Total tax rate applicable |
| `Population_Country` | Total population of the country |

## 🔍 Use Cases

- Analyzing global wealth distribution by country, region, and industry
- Studying the relationship between national economic indicators and billionaire wealth
- Comparing self-made vs. inherited wealth trends across demographics
- Visualizing wealth concentration geographically

## 📈 Dashboard

An interactive Excel dashboard accompanies this dataset, visualizing key insights such as wealth distribution, industry breakdowns, and self-made vs. inherited trends.

- **Tool Used:** Microsoft Excel (PivotTables, PivotCharts, Slicers)
- **Access:** Included in the `Dataset` folder of this repository
- **Key Features:**
  - Interactive filters by country, region, and industry
  - Visual comparison of billionaire wealth against GDP, tax rates, and population
  - Ranking and demographic breakdowns (age, gender, self-made status)

## 📁 Repository Structure

```
Global Billionaires Wealth Dataset/
└── Dataset/
    ├── Global Billionaires Wealth Dataset.xlsx   # Dataset + Dashboard
    └── README.md                                 # Project documentation
```

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `Global Billionaires Wealth Dataset.xlsx` from the **Dataset** folder in Microsoft Excel or Google Sheets.
3. Refer to the column descriptions above to understand the data structure.
4. Explore the built-in dashboard, or use PivotTables/charts to run your own analysis.

## 📝 Notes

- Some columns (e.g., `Population_Country`) may appear duplicated in the raw source data and should be reviewed/cleaned before analysis.
- Ensure proper handling of missing or null values, particularly in demographic and country-level fields.

## 📄 License

Specify the appropriate license for this dataset and project here.

## 👤 Author

**Kushagra**
GitHub: [Kushagra-a11ly](https://github.com/Kushagra-a11ly)
