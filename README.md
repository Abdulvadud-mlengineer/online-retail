# Online Retail Customer Clustering

This project focuses on customer segmentation using clustering techniques based on online retail transaction data.

## Project Overview

The goal of this project is to analyze customer purchasing behavior and group similar customers into clusters. This helps businesses better understand their clients, improve marketing strategies, and increase sales efficiency.

## Objective

To apply unsupervised machine learning (clustering) on online retail data to identify distinct customer groups based on their buying patterns.

## Dataset

The dataset contains transactional data from an online retail store, including:

- Invoice number  
- Product information  
- Quantity purchased  
- Unit price  
- Customer ID  
- Purchase date  
- Country  

## Methodology

1. Data Cleaning  
2. Handling missing values  
3. Feature engineering (RFM analysis: Recency, Frequency, Monetary)  
4. Data scaling  
5. Clustering with K-Means  
6. Cluster analysis and visualization  

## Machine Learning Task

Unsupervised Learning — Clustering

## Algorithms Used

- K-Means Clustering  
- Elbow Method for optimal clusters  

## Evaluation / Analysis

- Cluster visualization  
- Customer behavior interpretation  
- RFM segment analysis  

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## Results

The model groups customers into meaningful segments based on their purchasing behavior, helping to identify high-value customers, inactive customers, and potential loyal customers.

## Future Improvements

- Try DBSCAN or Hierarchical Clustering  
- Add advanced RFM feature engineering  
- Build dashboard for customer segmentation visualization  
- Deploy as web app (FastAPI / Streamlit)
