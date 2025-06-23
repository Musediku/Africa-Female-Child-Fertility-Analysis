# Understanding Adolescent Fertility in Africa: A Data-Driven Perspective

## Project Overview

Adolescent fertility remains a pressing concern across Africa, significantly contributing to various health risks, interrupted educational pathways, and long-term socio-economic challenges. This data exploration project aims to shed light on the regional distribution and underlying drivers of fertility rates among young women (ages 15–19) across African nations. By leveraging publicly available data, this analysis seeks to provide data-informed insights that can guide effective policymaking to reduce early childbearing, improve maternal health, increase educational attainment, and break cycles of poverty.

## Goals of This Project

* **Data Gathering and Preparation:** Collect, inspect, and prepare relevant datasets from various sources for analysis.
* **Data Quality Assessment:** Evaluate data quality, resolve inconsistencies, and handle missing values.
* **Exploratory Data Analysis (EDA):** Conduct initial exploratory analysis to uncover broad patterns, trends, and correlations.
* **Policy Insights:** Provide helpful insights for policymakers aiming to reduce adolescent fertility rates across Africa.

## Key Indicators Explored

| Variable                   | Description                                                         | Source           | Year (Most Recent) |
| -------------------------- | ------------------------------------------------------------------- | ---------------- | ------------------ |
| Adolescent Fertility Rate  | Births per 1,000 women ages 15–19                                   | World Bank       | 2023               |
| Female Youth Literacy Rate | % of young women (15–24) who can read/write                         | UNESCO Institute | 2022               |
| Child Labor (Female, 5–17) | % of girls (5–17) engaged in child labor                            | UNICEF           | 2023               |
| Urbanization Rate          | % of population living in urban areas                               | World Bank       | 2023               |
| Human Development Index    | Composite index measuring health, education, and standard of living | UNDP             | 2022               |

## Notebook Structure

* **Data Gathering:** Loading and merging datasets from multiple sources, including World Bank API, UNESCO, UNICEF, and UNDP. Focused on the most recent data (2023, with some 2022).
* **Data Cleaning and Wrangling:** Handling missing data, dropping irrelevant columns, and standardizing country codes.
* **Exploratory Data Analysis (EDA):** Generating summary statistics and performing univariate, bivariate, and multivariate analyses.
* **Summary of Findings & Policy Recommendations:** Highlighting key insights and outlining directions for policy research.
* **Data Limitations:** Discussing challenges such as missing data, inconsistent years, and absence of some socio-cultural variables.

## Key Findings (Preliminary)

* The mean adolescent fertility rate is approximately **82.5 births per 1,000 women aged 15–19**, significantly higher than the global average (\~39 per 1,000 in 2023).
* The distribution shows a slight left skew, indicating more countries with above-average fertility rates.
* There is wide variation (IQR \~57) and significant disparities across African nations (min: 4.32, max: 163.1 births per 1,000).
* These findings highlight the need for targeted policy interventions adapted to regional contexts.

## How to Run the Notebook

1. Clone the repository:

   ```bash
   git clone https://github.com/Musediku/Africa-Female-Child-Fertility-Analysis.git
   cd Africa-Female-Child-Fertility-Analysis
   ```
2. Install necessary Python libraries:

   ```bash
   pip install xlrd numpy pandas matplotlib seaborn requests plotly
   ```
3. Download the required datasets manually from their official sources and place them in the `/data` folder:

   * UNESCO Literacy Rate dataset
   * UNICEF Child Labour dataset
   * UNDP HDI dataset
4. Run the Jupyter notebook:

   ```bash
   jupyter notebook "Fertility rate project.ipynb"
   ```

## Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork this repository and open pull requests or issues.

## Disclaimer

This project is for exploratory data analysis purposes only and aims to provide insights based on publicly available data. Policy recommendations are generalized and should be validated with in-depth socio-cultural and localized studies.

---

**Contact:**
Fisayo Musediku
Email: [musedikudaniel@gmail.com](mailto:musedikudaniel@gmail.com)
LinkedIn: [https://www.linkedin.com/in/fisayomi-musediku](https://www.linkedin.com/in/fisayomi-musediku)
Medium: [https://medium.com/@beyond\_numbers](https://medium.com/@beyond_numbers)

---
