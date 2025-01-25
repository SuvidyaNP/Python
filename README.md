# ABC Company Employee Data Analysis

## Overview
This project involves analyzing a dataset from ABC Company containing 458 rows and 9 columns. The objective is to preprocess the data, perform comprehensive analysis tasks, create graphical representations, and summarize key insights to better understand employee distribution, roles, salary structures, and other patterns within the company.

The analysis is structured into three main phases: preprocessing, analysis tasks, and graphical representation.

---

## Preprocessing Steps
1. **Data Cleaning**:
   - Corrected inconsistencies and ensured integrity in the dataset.
   - Replaced values in the "height" column with random numbers between 150 and 180 to standardize the data.

2. **Feature Engineering**:
   - Created an "age_group" column by binning the "age" column into intervals.

3. **Validation**:
   - Verified the dataset for missing values and duplicates to ensure quality before proceeding with analysis.

---

## Analysis Tasks
1. **Distribution of Employees Across Teams**:
   - Calculated the number and percentage of employees in each team.
   - Highlighted the disparities in team sizes and their relative contribution to the workforce.

2. **Segregation of Employees by Position**:
   - Grouped employees based on their positions to identify common roles within the company.

3. **Predominant Age Group**:
   - Analyzed the distribution of employees across age groups to identify the most represented demographic.

4. **Highest Salary Expenditure**:
   - Evaluated salary distribution to determine which team and position incurred the highest costs.

5. **Correlation Between Age and Salary**:
   - Investigated the relationship between employees' ages and their salaries to uncover trends or patterns.

---

### Required libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## Conclusion
This project highlights critical trends and patterns within ABC Company’s workforce, offering actionable insights for decision-making. By understanding employee distribution, salary dynamics, and demographic trends, the company can make data-driven choices to enhance productivity, optimize resource allocation, and strengthen workforce diversity.
