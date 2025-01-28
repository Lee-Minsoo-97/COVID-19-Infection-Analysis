# COVID-19 Infection Analysis in Cameroon

## Project Overview
This project analyzes COVID-19 infection data from a rural city in Cameroon as of **March 30, 2020**. The dataset includes information on infected cases stratified by **age and gender**. The primary goal is to investigate whether there is a significant relationship between **age and gender** in infection rates and to determine which gender was more affected.

## Dataset
The dataset consists of **145 COVID-19 cases**, categorized by:
- **Age Groups**: 10-19, 20-29, 30-39, ..., 80+
- **Gender**: Male, Female

## Methods Used

### 1. **Exploratory Data Analysis (EDA)**
- Descriptive statistics (mean, standard deviation) for infections by gender and age.
- Visualization of infection trends using bar plots and histograms.

### 2. **Statistical Tests**
- **Chi-Square Test for Independence**: Examines if age and gender are dependent variables.
- **Permutation Test**: Used when chi-square assumptions are violated.
- **Wilcoxon Rank Sum Test**: Determines if infection rates significantly differ between males and females.

## Results
- **Chi-Square Test (Permutation-Based)**: Found that **age and gender are dependent variables** (p = 0.1065).
- **Wilcoxon Rank Sum Test**: No significant difference in infection rates between males and females (p > 0.05).

## Authors
- **Jong-Wook Choe**
- **Minsoo Lee**

## License
This project is part of the **STA 104 Exam Final Project** and is for academic purposes only.

