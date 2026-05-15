# Walmart Weekly Sales Analysis & Forecasting

This project provides a comprehensive analysis of Walmart's weekly sales data. It combines **Python-based data science** (Exploratory Data Analysis and Machine Learning) with **Power BI** for interactive business intelligence reporting.

## 2026 Analysis Overview
The primary goal was to identify the impact of economic factors (CPI, Unemployment, Fuel Price) and temporal events (Holidays, Christmas weeks) on sales performance.

### Key Features
* **Temporal Feature Engineering:** Extracted Month, Week of Year, Quarter, and custom "Is Christmas Week" flags.
* **Outlier Management:** Identified and handled sales anomalies using the IQR (Interquartile Range) method to stabilize model training.
* **Predictive Modeling:** Built a **Random Forest Regressor** to predict weekly sales.
* **Visual Insights:** A Power BI dashboard to visualize store-wise performance and economic correlations.

## Model Performance
The Random Forest model achieved high precision after handling outliers:
* **R² Score:** 0.957 (95.7% variance explained)
* **RMSE:** 115,029.72

## Project Structure
* `notebooks/`: Contains the `.ipynb` file with full data cleaning and ML training.
* `reports/`: Contains the Power BI `.pbix` file.
* `data/`: Raw and cleaned datasets.

## How to Use
1. Clone the repo: `git clone https://github.com/YourUsername/walmart-sales-analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook to see the data pipeline.
4. Open the Power BI file in the `reports/` folder to explore the dashboard.

## Dashboard Preview
![Dashboard Screenshot](visuals/first.jpg) 
![Dashboard Screenshot](visuals/Second.jpg) 


