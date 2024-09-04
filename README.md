# Credit Risk Analysis Project

## Project Overview

This project is designed to predict credit risk, focusing on identifying the likelihood that a borrower will default on a loan. The analysis uses a dataset containing key financial and demographic attributes and applies various machine learning techniques to assess and manage credit risk. The results of this project can be used by financial institutions to make informed lending decisions and reduce potential losses.

## Dataset

The dataset includes the following features:

- **Age**: The borrower's age.
- **Income**: The borrower's annual income.
- **LoanAmount**: The amount of the loan applied for by the borrower.
- **CreditScore**: A numerical score representing the creditworthiness of the borrower.
- **LoanTerm**: The duration of the loan in months.
- **EmploymentYears**: The number of years the borrower has been employed.
- **DebtToIncomeRatio**: The ratio of the borrower’s monthly debt payments to their monthly income.
- **NumOfCreditLines**: The total number of credit lines the borrower has.
- **NumOfOpenCreditLines**: The number of currently active credit lines.
- **RiskScore**: A calculated score indicating the risk level associated with the borrower.

## Methodology

The project workflow includes:

1. **Exploratory Data Analysis (EDA)**: Understanding the dataset through visualizations and statistical summaries.
2. **Data Preprocessing**: Handling missing data, normalizing features, and preparing the dataset for modeling.
3. **Feature Engineering**: Creating and refining features to improve model performance.
4. **Model Development**: Building predictive models such as Ridge Regression and performing clustering analysis using KMeans.
5. **Model Evaluation**: Assessing model accuracy using metrics like R² score and determining the importance of each feature.
6. **Clustering Analysis**: Grouping borrowers into clusters to identify distinct risk profiles.

## Key Insights

- The **Ridge Regression** model provided the best performance with an **R² score of 0.9907**, indicating that the model strongly fits the data.
- **Income** was identified as the most critical feature in predicting credit risk, followed by the **Income to Loan Ratio**.
- The **KMeans clustering** algorithm identified three distinct groups in the dataset, which may correspond to different risk categories.
- Clustering analysis showed that **Cluster 0** consists of borrowers with higher income levels, while **Cluster 1** includes borrowers with higher credit scores.

## Recommendations

- Financial institutions should prioritize improving borrower **credit scores** and managing **debt-to-income ratios** to reduce credit risk.
- Tailored financial products or strategies can be developed for different borrower segments identified through clustering analysis.
- Further analysis could focus on the impact of different **age groups** and **credit score ranges** on the risk of default.

## Conclusion

This project successfully demonstrates the application of machine learning techniques in credit risk assessment. By analyzing key features and identifying distinct borrower segments, the model can assist financial institutions in improving their risk management processes and making more informed lending decisions.

## How to Run the Project


 Open the provided Jupyter Notebook file.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

