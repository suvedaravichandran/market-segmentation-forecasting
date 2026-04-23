# Market Segmentation & Demand Forecasting

## Project Overview
Analysed 4,07,664 retail transactions to segment customers 
into behavioural groups and forecast future demand using 
Machine Learning.

## Key Results
- Identified **3 distinct customer segments** using RFM Analysis & K-Means
- **Champions** (13 customers) generate highest revenue (avg £1,12,132)
- **Regular Customers** — 3,239 customers (avg £2,082)
- **Lost Customers** — 1,060 customers (avg £594)
- Forecasted **12 weeks demand** for Champions segment

## Dataset
- Source: UCI Online Retail II Dataset
- Size: 5,25,461 rows → 4,07,664 rows (after cleaning)
- Period: 2009–2010

 Project Structure
market-segmentation/
├── data/
│   ├── cleaned_retail.csv
│   ├── rfm_segments.csv
│   └── forecast_champions.csv
├── visuals/
│   ├── elbow.png
│   ├── segments.png
│   └── forecast.png
├── 01_data_cleaning.ipynb
├── 02_segmentation.ipynb
├── 03_forecasting.ipynb
└── README.md

 Steps Followed
1. **Data Cleaning** — Removed nulls, cancelled orders, negative values
2. **RFM Analysis** — Recency, Frequency, Monetary features created
3. **K-Means Clustering** — Elbow method used to find optimal K=3
4. **Demand Forecasting** — 12 week future revenue forecast

 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn (KMeans, PCA, StandardScaler)
- Matplotlib, Seaborn
- Jupyter Notebook

Visuals
 Customer Segments
![Segments](visuals/segments.png)

 Demand Forecast
![Forecast](visuals/forecast.png)

 Skills Demonstrated
- Data Cleaning & EDA
- Feature Engineering (RFM)
- Unsupervised Machine Learning
- Time Series Forecasting
- Data Visualisation