# Unemployment Analysis in India (Pre vs Post COVID-19)

Internship project - Oasis Infobyte

## About
This project analyzes unemployment trends across Indian states using a dataset from Kaggle. 
Main focus is on comparing unemployment before and after the COVID-19 lockdown, along with region-wise 
and month-wise trends.

## Dataset
Dataset used: "Unemployment in India" by Gokul Raj Kuppan (Kaggle)
File used: Unemployment_Rate_upto_11_2020.csv

Link: https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india

## Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## What's in the notebook
- Data loading and cleaning (nulls, dtype conversion)
- Region-wise average unemployment rate
- Month-wise unemployment trend
- Time-series line chart for Delhi, Maharashtra, Tamil Nadu
- Top 10 states by average unemployment rate (bar chart)
- Correlation heatmap (unemployment rate, employed count, labour participation rate)
- Pre-COVID vs Post-COVID comparison

## Key Findings
- Post-COVID average unemployment rate (12.96%) was about 40% higher than pre-COVID (9.23%)
- Tamil Nadu and Delhi had the sharpest short-term spikes around April-June 2020
- Haryana and Tripura had the highest average unemployment overall, even though they didn't 
  spike as sharply as Tamil Nadu
- Unemployment rate and labour participation rate showed almost no correlation, which was 
  a bit unexpected

## How to run
1. Clone this repo / download the files
2. Install requirements:
   pip install pandas matplotlib seaborn
3. Open the notebook:
   jupyter notebook Unemployment_Analysis_India.ipynb
4. Run all cells

## Files
- Unemployment_Analysis.ipynb - main notebook
- Unemployment_Rate_upto_11_2020.csv - dataset
- unemployment_Rate_Over_Time.png, Top_10_States_Average_Unemployment_Rate.png, heatmap.png - saved charts

## Author
Aman Sharma
B.Tech CSE-AIML, UIET, KUK