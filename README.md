# Customer Purchase Behaviour & Sales Forecasting

## Project Overview
This project focuses on analyzing e-commerce customer purchase behaviour and sales patterns using Python. It uses the UCI Online Retail II dataset to perform data cleaning, exploratory data analysis, statistical testing, predictive modelling, and time-series forecasting.

## Objectives
- Analyze customer purchasing behaviour.
- Identify sales trends across countries and products.
- Calculate important business KPIs.
- Perform statistical analysis on purchase patterns.
- Classify invoices into high-value and low-value categories.
- Forecast monthly revenue.

## Dataset
**Source:** [UCI Machine Learning Repository – Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail)

- Approximately 1 million transaction records.
- 8 original columns.
- Covers December 2009 to December 2011.
- Contains invoice details, products, quantities, prices, customers, and countries.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Statsmodels

## Project Workflow
1. Business Understanding
2. Dataset Acquisition and Understanding
3. Data Cleaning and Preprocessing
4. Feature Engineering and KPI Calculation
5. Exploratory Data Analysis (EDA)
6. Statistical Analysis
7. Predictive Modelling
8. Time-Series Forecasting
9. Business Insights and Recommendations
10. Final Conclusion

## Key Results
- Total Revenue: 20,476,260.45
- Total Orders: 40,077
- Identified Customers: 5,878
- Average Order Value: 510.92
- Repeat Purchase Rate: 72.39%
- Logistic Regression Accuracy: 82.15%
- Baseline Forecast MAPE: 26.26%

## Machine Learning
Two classification models were evaluated:
- Logistic Regression
- Random Forest

The objective was to classify completed invoices into high-value and low-value categories.

## Time-Series Forecasting
- Baseline Forecasting
- Holt's Exponential Smoothing

The baseline model performed better than Holt's model on the selected test period.

## Business Recommendations
- Improve customer retention through loyalty programs.
- Explore opportunities in countries beyond the UK.
- Use product sales analysis for inventory planning.
- Increase average order value through bundles and cross-selling.
- Use forecasting results as an initial benchmark for revenue planning.

## Limitations
- Some customer IDs are missing.
- Revenue calculations do not subtract returns and refunds.
- The classification model uses completed invoice information.
- The dataset contains only 25 monthly observations for forecasting.

## Author
**Muhammad Nihal Z**

GitHub: [nihalzak](https://github.com/nihalzak)
