# Credit Risk Analysis Project

## Project Overview

This project aims to develop a robust credit risk prediction model by analyzing various financial and demographic factors. Using advanced data science techniques, the goal is to predict the likelihood of default and provide actionable insights to minimize risk. The analysis covers data cleaning, exploratory data analysis, feature engineering, model selection, and hyperparameter tuning.

## Dataset

The dataset contains 1,000 entries with 21 features related to individuals' credit history and financial status. The key features include:

- **Age**
- **Income**
- **Credit Score**
- **Loan Amount**
- **Loan Duration**
- **Employment Years**
- **Education Level**
- **Marital Status**
- **Number of Dependents**
- **Home Ownership**
- **Car Ownership**
- **Savings Account**
- **Checking Account**
- **Previous Loans**
- **Loan Purpose**
- **Current Debt**
- **Monthly Expenses**
- **Credit History Length**
- **Number of Credit Cards**
- **Number of Loans**
- **Risk Category** (Target variable)

## Steps Performed

### 1. Data Cleaning
- Handled missing values and ensured data consistency across all features.
- Standardized data formats to prepare for analysis.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions of key variables and identified correlations.
- Conducted univariate and bivariate analysis to understand feature relationships.

### 3. Feature Engineering
- Created new features to enhance model performance.
- Performed one-hot encoding and scaling on categorical variables.

### 4. Model Selection & Hyperparameter Tuning
- Implemented and compared several models, including Random Forest, Gradient Boosting, and SVM.
- Tuned hyperparameters using GridSearchCV to optimize model performance.

### 5. Model Evaluation
- Evaluated models using metrics like AUC, precision, recall, and F1 score.
- Selected the best-performing model based on these metrics.

### 6. Insights & Recommendations
- Identified key factors driving credit risk.
- Provided recommendations for improving model performance and data collection strategies.

## Technologies Used

- **Python**: Primary programming language for data analysis.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning models and evaluation.
- **Jupyter Notebook**: Interactive environment for analysis and reporting.

## How to Run the Project

1. Clone the repository.
2. Install the required dependencies from `requirements.txt`.
3. Run the Jupyter Notebook to see the analysis and results.

## Conclusion

This project provides a comprehensive approach to credit risk analysis, leveraging advanced machine learning techniques to predict default risk. The insights generated can be used to develop strategies to mitigate risk and enhance credit decision-making processes.

## Future Work

- Incorporate additional data sources to improve model accuracy.
- Experiment with deep learning models for more complex pattern recognition.
- Deploy the model in a real-time credit scoring application.

