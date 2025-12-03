AAL Sales Analysis — 4th Quarter 2020

A complete data analysis project exploring the sales performance of Australia Apparel Ltd. (AAL) during Q4 2020 using Python, covering data wrangling, cleaning, visualization, and business insights.

Project Overview

This project analyzes the Aus Apparel Sales 4th Quarter 2020 dataset to understand sales performance across:

Australian states

Customer groups (Kids, Men, Women, Seniors)

Monthly, Weekly, and Quarterly time periods

Units sold vs. total revenue

Highest and lowest performing segments

This analysis helps the business identify trends, bottlenecks, and potential opportunities for growth.

 Project Structure
AAL_Sales_Analysis_Project.ipynb
AusApparalSales4thQrt2020.csv
assets/
    └── plots/  (charts exported manually)
README.md

Tech Stack

Python

Pandas (data manipulation)

NumPy (numerical computation)

Matplotlib / Seaborn (visualizations)

scikit-learn (scaling & preprocessing)

 Key Steps Performed
 Data Wrangling

Handling missing values

Converting Date column to proper datetime format

Normalizing numerical features using MinMaxScaler

Cleaning and preparing dataset for analysis

Exploratory Data Analysis (EDA)

Descriptive statistics (mean, median, mode, std dev)

Sales distribution overview

State-wise and group-wise performance comparison

 Time Series Summary

Weekly sales

Monthly trends

Quarterly aggregation

Identifying seasonality and peak sales periods

Visualizations

Bar charts: State-wise sales

Group-wise revenue

Time-series line charts

Combined unit & sales comparison

Distribution plots for scaled features

 Insights

 New South Wales (NSW) and Victoria (VIC) show the highest sales contribution
 Women’s category performs strongest in most months
 December shows significant revenue spikes due to seasonal purchases
 Weekly sales show upward patterns close to festive periods
 Normalized data reveals strong correlation between units sold & total revenue

How to Run
Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

 Open the notebook
jupyter notebook AAL_Sales_Analysis_Project.ipynb

Run all cells to reproduce the analysis
 Dataset

File: AusApparalSales4thQrt2020.csv
Contains:

Date

State

Customer Group

Units Sold

Sales Amount

This dataset was provided as part of the PG Data Science & ML curriculum.

Future Enhancements

Add predictive model for next quarter’s revenue

Build automated Power BI / Streamlit dashboard

Add correlation heatmap and anomaly detection

Deploy as a web-based interactive analytics tool

Author

Pavan Chinta
 Data Science & ML Enthusiast
 GitHub: https://github.com/YOUR_USERNAME


