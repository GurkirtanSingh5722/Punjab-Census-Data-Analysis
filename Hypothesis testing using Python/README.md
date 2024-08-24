# Population Data Analysis of Punjab (1901-2011)

## Overview

This project involves a detailed analysis of the population census data of Punjab from 1901 to 2011. The analysis focuses on understanding demographic trends, sex ratio variations, and growth rates across different districts. Additionally, a Power BI dashboard has been created to visually represent the findings.

## Table of Contents

1. [Project Description](#project-description)
2. [Data Description](#data-description)
3. [Methodology](#methodology)
4. [Analysis](#analysis)
   - [Handling Missing Data](#handling-missing-data)
   - [Statistical Tests](#statistical-tests)
   - [ANOVA for Sex Ratio](#anova-for-sex-ratio)
5. [Power BI Dashboard](#power-bi-dashboard)
6. [Results](#results)
7. [How to Use](#how-to-use)
8. [Conclusion](#conclusion)
9. [Future Work](#future-work)
10. [References](#references)

## Project Description

This project aims to analyze the population trends in Punjab, focusing on key indicators such as sex ratio, population growth, and district-wise demographic changes over time. The dataset covers census years from 1901 to 2011, with particular attention to the period from 1951 to 2011, where data is more complete and reliable.

## Data Description

The dataset used in this analysis contains the following columns:

- **District:** The name of the district in Punjab.
- **Census Year:** The year the census was conducted.
- **Persons:** The total population recorded.
- **Absolute Change Since Previous Census:** The change in population since the last census.
- **Percentage Change Since Previous Census:** The percentage change in population since the last census.
- **Males:** The number of males recorded.
- **Females:** The number of females recorded.
- **Sex Ratio:** The ratio of females per 1000 males.

## Methodology

1. **Data Cleaning:** 
   - Filtering the dataset to focus on census years from 1951 to 2011.
   - Handling missing data using extrapolation methods.

2. **Data Analysis:**
   - **Growth Rate Calculation:** Calculating the population growth rate across different census years.
   - **Sex Ratio Analysis:** Analyzing the variation in sex ratios across districts and over time.
   - **Statistical Testing:** Performing hypothesis testing, including ANOVA, to determine significant differences in sex ratios and population growth.

3. **Visualization:** 
   - Creating visual representations of the data using Power BI to help identify trends and patterns.

## Analysis

### Handling Missing Data

Missing data for some districts (e.g., Kapurthala, Patiala, Sangrur, Bathinda) from 1901 to 1941 was handled by focusing the analysis on the years from 1951 to 2011, where more complete data was available.

### Statistical Tests

- **ANOVA Test:** Conducted to assess whether the sex ratio varies significantly from district to district.
- **Growth Rate Analysis:** Calculated the growth rate for each decade to understand population dynamics over time.

### ANOVA for Sex Ratio

The ANOVA test was performed to determine if there are significant differences in the sex ratios across different districts in Punjab.

## Power BI Dashboard

A Power BI dashboard has been created to provide an interactive visualization of the population data analysis. The dashboard includes:

- **Sex Ratio Trends:** Visual representation of how the sex ratio has changed across different districts and census years.
- **Population Growth Analysis:** Charts depicting the growth rates over the decades.
- **District Comparisons:** Comparisons of population metrics across districts.

## Results

The analysis revealed significant variations in sex ratios across different districts. The growth rate analysis showed consistent population increases across most districts, with some notable exceptions.

## How to Use

1. **Data Analysis:**
   - Clone the repository and run the analysis scripts in Python.
   - Ensure that all required libraries (e.g., pandas, scipy, matplotlib) are installed.

2. **Power BI Dashboard:**
   - Open the Power BI dashboard file (`PunjabPopulationDashboard.pbix`) using Power BI Desktop.
   - Explore the interactive visualizations to gain insights from the data.

## Conclusion

The population data analysis provides valuable insights into demographic changes in Punjab from 1901 to 2011. The significant variations in sex ratios across districts highlight the importance of regional analysis in understanding demographic trends.

## Future Work

- Extend the analysis to include additional demographic indicators such as literacy rate, age distribution, and economic status.
- Incorporate data from other regions of India for a comparative analysis.
- Use machine learning models to predict future demographic trends based on historical data.

## References

- Census of India (1901-2011)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Scipy Documentation](https://docs.scipy.org/doc/scipy/)

