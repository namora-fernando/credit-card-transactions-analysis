# Comparative Analysis of Credit Card Customer Transactions: Active vs Churned

## Repository Outline

```
|
├─ dataset.csv                          # Original dataset from Kaggle
├─ notebook.ipynb                       # Notebook of exploratory data analysis using python
├─ README.md                            # Project overview explanation
├─ requirements.txt                     # Python dependencies
```

## Problem Background

The Bank's credit card customers dataset is analyzed to compare customer transaction behavior between active and churned customers. This study focuses on customer transaction activity as a key indicator of customer loyalty and engagement, which is measured using the total transaction amount over the last 12 months. To analyze differences in transaction behavior between active and churned customers, both overall and across different credit card categories. By analyzing historical data, this study aims to identify differences in transaction behavior associated with churn status. The findings are expected to support better understanding of customer engagement patterns and provide data-driven foundation for future customer retention strategies.

## Project Output

This project output includes business understanding, data understanding, exploratory data analysis (EDA) by visual; descriptive statistics; and inferential statistics, along with valuable insights of the dataset with Python notebooks.

The EDA conducted to analyze differences in transaction behavior between active and churned credit card customers.

Interactive dashboards built in Tableau are also linked with to support this study analysis.

### Python Notebook Outline

- **i. Introduction**: <br>
> the introduction of the author of this project
- **ii. Problem Statement and Dataset Description**: <br> 
> topic and background of the study, problem statement, source dataset, and explanation of problems to be analyze
- **iii. Data Loading**: <br> 
> the process for data loading and simple exploration
- **iv. Data Cleaning**: <br>
> the preparataion of data for more thorough analysis
- **v. Exploration and Analysis**: <br>
> the analysis process by visualization, descriptive statistics, and inferential statistics and insights findings to answer business questions
- **vi. Conclusion**: <br>
> the conclusion and recommendation of insights after analysis process

## Data

Data sourced from [Kaggle](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers), the column will be use for analysis:

- `Attrition_Flag`: represents the customer status, whether attrited (churned) or not
- `Customer_Age`: represents the customer's age in years old
- `Gender`: represents the customer's gender
- `Card_Category`: represents type of credit card held by customer
- `Total_Trans_Amt`: represents the total transactions amount for the last 12 months

Dataset characteristics:

- Total 10127 rows
- 5 Columns will be used
- No missing values (of 5 columns above)

## Method

This project is about exploratory data analysis (EDA) of the dataset

1. Start from busineess understanding storytelling, analysis will be conducted
2. Data understanding, with the boundary of business question to be analyze
3. EDA - by visualization, descriptive statistics, and inferential statistics with Python libraries
4. Insights for each visualization on notebook
5. Tableau dashboards with interactivity for additional visual

## Stacks

- **Python**: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`
- **Tableau Public**: interactive dashboards for additional visualization
> Version of Python used: 3.10.12


## Reference

- Data source reference: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers
- [Customer Transaction Comparison](https://public.tableau.com/app/profile/fernando.namora/viz/P0M1_fernando_namora/CustomerTransactionComparison)
- [Descriptive Statistics](https://public.tableau.com/app/profile/fernando.namora/viz/P0M1_fernando_namora/DescriptiveStatistics)
- [Inferential Statistics](https://public.tableau.com/app/profile/fernando.namora/viz/P0M1_fernando_namora/InferentialStatistics)