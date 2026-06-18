# 🌍 World Indicators Data Analysis

## Overview

This project explores global development trends using data from the Human Development Index (HDI) dataset and World Bank indicators. Through exploratory data analysis (EDA), the project investigates relationships between economic performance, human development, population dynamics, and health outcomes across countries and regions.

The goal is to uncover patterns that explain how different factors contribute to human well-being and economic growth while highlighting disparities between regions and income groups.

---

## Objectives

This analysis seeks to answer the following questions:

1. Which regions experienced the highest Human Development Index (HDI) growth in the 21st century?
2. What factors are most strongly associated with life expectancy?
3. How does infant mortality relate to life expectancy?
4. What differentiates high-income countries from low-income countries?
5. Which countries recorded the highest GDP growth and population growth?
6. How do GDP growth and population growth compare across different regions?

---

## Dataset Sources

### Human Development Index (HDI) Dataset

Contains country-level HDI values across multiple years, along with regional classifications.

### World Bank Indicators Dataset

Includes socioeconomic and development indicators such as:

* GDP (USD)
* GDP per Capita (USD)
* Population Density
* Life Expectancy
* Birth Rate
* Death Rate
* Infant Mortality Rate
* Internet Usage
* Electric Power Consumption
* Income Group Classification
* Regional Information

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```text
├── World Indicator Data.ipynb
├── HDI.csv
├── WorldBank.xlsx
└── README.md
```

---

## Key Analyses Performed

### 1. HDI Growth Analysis

Calculated HDI growth from 2000 onwards to identify regions with the strongest improvements in human development.

#### Key Findings

* South Asia recorded the highest average HDI growth.
* Europe & Central Asia and Sub-Saharan Africa also demonstrated substantial improvements.
* Most regions experienced positive development trends throughout the century.

---

### 2. Factors Correlated with Life Expectancy

Examined relationships between life expectancy and socioeconomic indicators using correlation analysis.

#### Key Findings

Strong positive relationships were observed between life expectancy and:

* GDP per Capita
* Internet Usage
* Electric Power Consumption

Strong negative relationships were observed between life expectancy and:

* Infant Mortality Rate
* Death Rate
* Birth Rate

These findings suggest that economic development, infrastructure, and access to technology contribute significantly to longer life expectancy.

---

### 3. Life Expectancy vs Infant Mortality

Created a scatter plot to visualize the relationship between life expectancy and infant mortality rates.

#### Key Findings

* Countries with lower infant mortality generally have higher life expectancy.
* The relationship is strongly negative and consistent across regions.
* Wealthier countries tend to cluster around high life expectancy and low infant mortality.

---

### 4. High-Income vs Low-Income Country Comparison

Compared major development indicators between high-income and low-income countries.

#### Key Findings

High-income countries generally exhibit:

* Higher GDP per Capita
* Higher life expectancy
* Greater internet access
* Higher electricity consumption

Low-income countries generally exhibit:

* Higher birth rates
* Higher infant mortality rates
* Lower access to infrastructure and technology

---

### 5. GDP Growth Analysis

Calculated percentage GDP growth across countries and identified the top-performing nations.

#### Key Findings

Several rapidly developing and resource-driven economies recorded exceptional GDP growth over the study period.

---

### 6. Population Growth Analysis

Analyzed population density growth across countries.

#### Key Findings

Countries experiencing rapid urbanization and migration showed significant increases in population density.

---

### 7. GDP Growth vs Population Growth

Explored whether economic growth and population growth move together.

#### Key Findings

* A generally positive relationship exists between GDP growth and population growth.
* Some countries are notable outliers, indicating unique economic or demographic dynamics.

---

### 8. Regional Growth Comparison

Compared average GDP growth and population growth across global regions.

#### Key Findings

* Middle East & North Africa showed strong growth performance.
* Regional differences reveal varying stages of economic and demographic development.

---

## Visualizations

The project includes:

* Correlation Heatmaps
* Scatter Plots
* Bar Charts
* Regional Comparison Charts

These visualizations help communicate patterns and relationships within the data.

---

## Overall Conclusions

This analysis demonstrates that:

* Economic prosperity, health outcomes, and human development are deeply interconnected.
* Significant disparities remain between high-income and low-income countries.
* Improvements in infrastructure, technology access, and healthcare are strongly associated with better quality of life.
* Regional development patterns vary considerably, reflecting differences in policy, resources, demographics, and economic structure.

---

## Future Improvements

Potential extensions of this project include:

* Predictive modeling for HDI and life expectancy.
* Time-series forecasting of GDP growth.
* Interactive dashboards using Power BI, Tableau, or Plotly.
* Geospatial analysis and mapping of development indicators.
* Machine learning models to identify key drivers of development outcomes.

---

## Author

**Busola Adewale**

Data Analyst | Geology Graduate

Passionate about transforming data into insights that drive understanding, decision-making, and impact.
