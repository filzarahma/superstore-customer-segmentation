# Superstore Customer Segmentation

## Overview

This project implements customer segmentation for a superstore dataset using RFM (Recency, Frequency, Monetary) analysis combined with K-means clustering. The analysis helps identify different customer segments to enable targeted marketing strategies and improved customer relationship management.

## Key Features

- **RFM Analysis**: Segmentation based on three key metrics:
  - **Recency**: How recently a customer made a purchase
  - **Frequency**: How often a customer makes purchases
  - **Monetary Value**: How much money a customer spends

- **K-means Clustering**: Unsupervised machine learning algorithm used to identify natural groupings in the RFM data

- **Interactive Sales Dashboard**: Visualization of sales data and customer segments, built with Metabase and powered by Docker and Supabase

## Files

- `rfm segmentation with kmeans.ipynb`: Jupyter notebook containing the complete analysis code
- `Sales Dashboard.pdf`: Visual dashboard showing key sales metrics and customer segment insights

## Dashboard

You can view the interactive dashboard online:
- **Interactive Dashboard**:

![Preview PDF](https://github.com/filzarahma/superstore-customer-segmentation/blob/main/Sales%20Dashboard.pdf)

## Technologies Used

- **Analysis**: Python 3.x, Jupyter Notebook
- **Dashboard**: Docker, Supabase, Metabase
- **Libraries**: pandas, numpy, sklearn, matplotlib, seaborn

## Getting Started

1. Clone this repository
2. Install required dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Run the Jupyter notebook: `jupyter notebook "rfm segmentation with kmeans.ipynb"`
4. Review the `Sales Dashboard.pdf` for visual insights

## Results

The analysis identifies distinct customer segments such as:
- High-value loyal customers
- Mid-value regular customers
- Low-value infrequent customers
- New customers with high potential

These segments can be used to develop targeted marketing strategies and improve customer retention.
