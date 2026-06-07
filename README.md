# Global Natural Disaster Analysis

## Overview

Natural disasters have significant impacts on human populations, economies, and infrastructure worldwide. This project analyzes global disaster data from the Emergency Events Database (EMDAT) to identify patterns in disaster occurrence, affected populations, fatalities, and economic damages.

Using Python, Pandas, Matplotlib, and Seaborn, this project performs data cleaning, exploratory data analysis (EDA), and visualization to better understand the effects of natural disasters across countries and over time.

---

## Dataset

Source:

EMDAT (Emergency Events Database)

https://www.emdat.be/

The dataset contains information on:

- Country
- Year
- Disaster Type
- Disaster Subtype
- Event Totals
- Total Affected Population
- Total Deaths
- Total Damage (Adjusted USD)

---

## Project Objectives

The main goals of this project are to:

1. Clean and preprocess disaster data.
2. Analyze the frequency of disaster types.
3. Identify the most common disaster subtypes.
4. Examine trends in affected populations and deaths over time.
5. Determine which countries experience the greatest disaster impacts.
6. Compare disaster types based on:
   - Total Deaths
   - Total Affected Population
   - Economic Damage

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed unnecessary columns.
- Rounded numerical values for consistency.
- Removed rows containing missing values.
- Reset dataset indexing after cleaning.

Final cleaned dataset size:

- 646 observations

---

## Exploratory Data Analysis

### 1. Disaster Frequency Analysis

- Distribution of disaster types
- Identification of the most frequent disaster category

### 2. Disaster Subtype Analysis

- Most common subtype within each disaster category

### 3. Time Trend Analysis

- Total affected population by year
- Total deaths by year

### 4. Country Impact Analysis

- Top countries by:
  - Population affected
  - Disaster-related deaths

### 5. Yearly Disaster Impact Comparison

- Stacked bar chart comparing affected populations across disaster types and years

### 6. Impact Comparison by Disaster Type

Comparison of:

- Total Deaths
- Total Affected Population
- Total Economic Damage

---

## Key Findings

- Weather-related disasters are among the most frequently recorded events.
- Disaster impacts vary substantially from year to year.
- Certain countries experience disproportionately large disaster burdens.
- Economic losses and human losses do not always follow the same patterns.
- Different disaster types affect populations in different ways.

---

## Results

The analysis provides visual and statistical insights into:

- Global disaster frequency
- Human impacts
- Economic impacts
- Geographic distribution of disaster effects
- Long-term disaster trends

These findings can support disaster preparedness initiatives and future research into disaster risk reduction.

---

## Future Improvements

Potential enhancements include:

- Predictive machine learning models
- Climate change impact analysis
- Geospatial mapping
- Interactive dashboards using Plotly or Tableau
- Advanced statistical modeling

---

## Author

Samir

## License

This project is intended for educational and research purposes.
