# Telco Customer Churn Analysis 📊

## Project Overview
End-to-end data analytics project analyzing customer churn 
for a telecom company using Excel, Python and Machine Learning.

## Problem Statement
A telecom company is losing 26.6% of its customers every year.
This project identifies WHY customers churn and PREDICTS 
which customers are likely to leave in the future.

## Tools and Technologies
- Microsoft Excel — Data Cleaning and Dashboard
- Python — EDA, Visualization and Machine Learning
- Libraries — pandas, numpy, matplotlib, seaborn, scikit-learn
- Google Colab — Python environment
- GitHub — Version control and project hosting

## Dataset
- Source: Kaggle — Telco Customer Churn (BlastChar)
- Size: 7032 customers, 21 features
- Target column: Churn (Yes/No)

## Project Structure
- churn_analysis.ipynb — Complete Python analysis notebook
- telecom_cleaned_analysis.xlsx — Excel dashboard and pivot tables
- archive.zip — Original raw dataset

## Steps Performed

### 1. Data Cleaning
- Removed 11 blank rows in TotalCharges column
- Converted TotalCharges from text to numeric
- Fixed SeniorCitizen column from 0/1 to Yes/No
- Created Tenure_Group and Charges_Group columns

### 2. Exploratory Data Analysis
- Overall churn rate calculation
- Churn analysis by Contract type
- Churn analysis by Tenure group
- Churn analysis by Monthly Charges

### 3. Data Visualization
- Pie chart for overall churn rate
- Bar charts for each analysis
- Excel dashboard with all insights

### 4. Machine Learning
- Logistic Regression model — 78.54% accuracy
- Random Forest model — 79.25% accuracy
- Feature importance analysis
- Confusion matrix evaluation
- New customer churn prediction

## Key Findings

| Insight | Finding |
|---|---|
| Overall Churn Rate | 26.6% |
| Month-to-month churn | 42.7% |
| One year contract churn | 11.3% |
| Two year contract churn | 2.8% |
| New customers (0-12 months) | 47.7% churn |
| Loyal customers (49+ months) | 9.5% churn |
| High charges ($60+) churn | 33.9% |
| Low charges ($0-30) churn | 9.8% |

## Machine Learning Results
- Best model: Random Forest Classifier
- Accuracy: 79.25%
- Top 3 churn drivers: TotalCharges, MonthlyCharges, tenure

## Business Recommendations
1. Convert month-to-month customers to annual plans
   - Reduces churn from 42.7% to 2.8%
2. Focus retention on 0-12 month customers
   - New customers churn 5x more than loyal ones
3. Offer discounts to high paying customers ($60+)
   - High charges increase churn risk to 33.9%
4. Target electronic check users with auto-payment offers
   - Electronic check users have highest churn rate

## How to Run
1. Open `churn_analysis.ipynb` in Google Colab
2. Upload the dataset from archive.zip
3. Run all cells in order
4. View outputs and charts

## Author
Meghana T
Aspiring Data Analyst
[LinkedIn Profile Link]
[GitHub Profile Link]
