Global Urban Air Quality Analysis (2015–2025)

This project analyzes the Global Urban Air Quality Index (AQI) dataset (2015–2025) from Kaggle.
Using Python (Pandas, Matplotlib, Seaborn) in Google Colab, we explore air quality trends, pollutant correlations, and city-level comparisons.

Project Objectives

Clean and preprocess the AQI dataset

Explore AQI distribution across different cities

Analyze temporal trends in AQI (monthly/yearly)

Compare AQI levels across major urban centers

Identify the most polluted cities

Explore correlations between AQI and pollutants

Dataset

Source: Global Urban Air Quality Index Dataset (2015–2025) – Kaggle

The dataset includes:

City, Country

Date/Year/Month

AQI (Air Quality Index)

Pollutants: PM2.5, PM10, NO2, SO2, CO, O3, etc. (depending on availability)

Tools & Libraries

Google Colab / Jupyter Notebook

Python 3

Pandas – data cleaning & analysis

Matplotlib, Seaborn – data visualization

Key Analysis & Visualizations

Data Cleaning – handle missing values, convert dates, normalize columns

AQI Trend Over Time – line plots for top cities

AQI Distribution – boxplots comparing AQI across cities

Correlation Heatmap – AQI vs pollutants

Monthly Average AQI Trends – global and per city

Top 10 Most Polluted Cities – bar chart of average AQI

How to Run

Download the dataset from Kaggle

Upload the CSV to Google Colab using files.upload()

Run each notebook cell step by step (data cleaning → EDA → visualization)

Results will display as plots inside the notebook

Export cleaned dataset with aqi_cleaned_ready.csv

Example Insights

AQI fluctuates seasonally, often peaking in winter months

Strong correlation between PM2.5/PM10 and AQI

Certain cities consistently rank among the most polluted globally

Future Work

Build predictive models for AQI forecasting

Add geospatial analysis (mapping AQI by location)

Deploy results on a dashboard (Streamlit/Plotly Dash)


BY AUTHOR - Likhitha Gopal
