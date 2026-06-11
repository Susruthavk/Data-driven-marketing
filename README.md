# Data-Driven Marketing using K-Means Clustering

> Published Research Paper | California State University, East Bay
> Authors: Susrutha Vishal Koyyalamudi & Ashish Padavala
> Department: Computer Science

## Overview

This project applies K-Means clustering to segment customers from a real-world e-commerce dataset containing over 500,000 transactions. By identifying distinct customer groups based on purchasing behavior, the model enables businesses to design highly targeted, personalized marketing campaigns.

Key findings:
- 20% of customers are high-spenders (>$450/transaction)
- 52% are mid-range spenders ($150-$300/transaction)
- 17% are low-spenders (<$150/transaction)
- Dominant segments: Employees (41%) and Educators (31%)

## Repository Structure

- CustomKNN.ipynb — Main Jupyter Notebook with full pipeline
- preprocessed.csv — Cleaned and preprocessed dataset
- ppt.pptx — Project presentation slides
- README.md — Project documentation

## Dataset

Source: UCI Machine Learning Repository (UK-based retailer, 2010-2011)
Size: 500,000+ transactions

## Methodology

1. Data Preprocessing — removed missing values, duplicates, invalid codes
2. Feature Engineering — derived 12 behavioral features from raw transactions
3. Outlier Removal — applied IQR method
4. Feature Scaling — StandardScaler normalization
5. Dimensionality Reduction — PCA
6. K-Means Clustering — 3 customer segments

## Tech Stack

- Python, Pandas, NumPy
- Scikit-learn (KMeans, PCA, StandardScaler)
- Matplotlib
- Jupyter Notebook

## Results

Three customer clusters identified:
- Cluster 1: High-value customers — target with premium offers and loyalty rewards
- Cluster 2: Mid-tier customers — target with retention and upselling campaigns
- Cluster 3: Low-engagement customers — target with re-engagement offers

## How to Run

git clone https://github.com/Susruthavk/Data-driven-marketing.git
cd Data-driven-marketing
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook CustomKNN.ipynb

## Author

Susrutha Vishal Koyyalamudi
MS Computer Science, AI & Machine Learning
California State University, East Bay
susruthavishalk@gmail.com
