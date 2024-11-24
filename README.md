# Covid19-in-Australia

This repository contains the analysis and visualizations of the development of COVID-19 in Australia. The project focuses on exploring and understanding the weekly trends in new cases and deaths, normalizing cases by population, and investigating the relationships between these variables for the states of NSW, VIC, QLD, SA, and WA.

---

## Project Overview

This project was completed as part of COMP 5070 - Statistical Programming for Data Science. The primary objectives are:
1. **Aggregating and analyzing COVID-19 data** from daily to weekly format.
2. **Visualizing the spread and impact of COVID-19** using population-normalized metrics and trend analysis.
3. **Exploring correlations** between new cases and deaths across different states.

---

## Files in the Repository

- **`Manoj_covid_assignment.ipynb`**: The Jupyter Notebook containing the Python code, analysis, and visualizations.
- **`python covid 19 australia.pdf`**: PDF document summarizing the analysis.
- **`data.zip`**: The dataset used in this analysis, containing daily and weekly records of new COVID-19 cases and deaths for Australian states.
- **`COMP5070_Assignment1_SP2_2023.docx`**: Assignment instructions and guidelines for the project.

---

## Data Description

The dataset used for this analysis includes:
- **Variables**: 
  - New cases (`NEW`): Officially reported cases.
  - Adjusted cases (`NET`): Adjusted by authorities.
  - New deaths: Daily reported deaths.
- **Coverage**:
  - States: NSW, VIC, QLD, SA, WA.
  - Timeline: Data provided as daily records until September 9, 2022, and weekly thereafter.

Population data from the Australian Bureau of Statistics (ABS) was used for normalization purposes.

---

## Key Steps in the Analysis

1. **Data Preprocessing**:
   - Aggregating daily data into weekly records.
   - Using the `NEW` column for cumulative case calculations.

2. **Exploratory Data Analysis (EDA)**:
   - Distribution analysis of weekly cases and deaths across states.
   - Trend visualization of cumulative cases starting from the week after 1,000 cases were reported.

3. **Population-Normalized Analysis**:
   - Weekly cases were normalized by population for a comparative study across states.

4. **Correlation Study**:
   - Investigating the relationship between new cases and deaths.

5. **Visualization**:
   - Multiple line plots and comparative graphs to understand trends and patterns.

---

## Requirements

- **Python**: Version >= 3.8
- **Libraries**:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `numpy`

---

## Results

The analysis highlights the following:
- Trends in COVID-19 spread and impact over time.
- Differences in normalized weekly cases across states.
- Correlation insights between new cases and reported deaths.

The full results and insights are documented in the notebook and PDF.

---
