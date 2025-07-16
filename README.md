# Data Visualization, Preprocessing, and Statistical Analysis Lab

This repository demonstrates the application of data visualization, data preprocessing, and statistical analysis techniques using Jupyter Notebooks, as part of MSCS 634 Lab 1.

## Dataset Summary

The project utilizes one or more CSV datasets stored within the repository. These datasets are integral to demonstrating practical techniques for cleaning, exploring, and visualizing data. Each dataset typically includes variables relevant to real-world scenarios, such as demographic, transactional, or categorical attributes, which are analyzed and visualized within the notebooks.

**Key variables commonly include:**
- Numerical columns 
- Categorical columns (e.g., Gender, Occupation, ProductCategory)
- Date/time columns

**Key Insights from Analysis:**
- Discovered trends and correlations among variables, such as relationships between demographic attributes and purchasing behavior.
- Identified patterns in categorical variables and their impact on target metrics.
- Uncovered data quality issues, such as missing or inconsistent entries, and addressed them to improve analysis integrity.

## Major Steps in Data Cleaning and Exploration

1. **Importing Data:** Loaded the CSV datasets into pandas DataFrames for manipulation and analysis.
2. **Initial Exploration:** Reviewed data types, summary statistics, and checked for null values.
3. **Data Cleaning:**
   - Detected and imputed or removed missing values, depending on the variable type and context.
   - Standardized categorical values for consistency.
   - Converted columns to appropriate data types (e.g., string to datetime).
   - Handled duplicate entries and verified data integrity.
4. **Outlier Detection:** Used statistical methods (e.g., z-score, IQR) and visualizations to detect and manage outliers.
5. **Feature Engineering:** Created new variables or transformed existing ones to enhance analysis, such as binning ages or encoding categorical values.
6. **Exploratory Data Analysis (EDA):**
   - Visualized distributions and relationships using matplotlib and seaborn.
   - Generated correlation matrices and summary plots.
   - Used groupby and aggregation to summarize trends and differences across categories.

## Challenges and Solutions

- **Missing or Inconsistent Data:**  
  Encountered missing or inconsistent entries in several columns. Addressed this by applying appropriate imputation for numerical columns (mean or median) and filling with mode for categorical columns. In some cases, rows with extensive missing data were removed.
- **Outliers and Skewed Distributions:**  
  Presence of extreme values or skewed distributions affected summary statistics. These were visualized using histograms and boxplots, with outliers mitigated by transformation or exclusion, depending on their impact on analysis.
- **Data Type Inconsistencies:**  
  Some columns were in incorrect formats (e.g., numeric data as strings). These were converted using pandas' type conversion functions to ensure correct analysis.
- **Categorical Encoding:**  
  Non-numeric categorical variables required encoding for statistical analysis and modeling. Applied one-hot encoding or label encoding as appropriate.

---

This README provides a comprehensive overview of the dataset(s), methods, and insights derived from the project. All steps from data loading to analysis are documented in the Jupyter Notebooks in this repository, ensuring reproducibility. No further additions are required for a complete project summary.
