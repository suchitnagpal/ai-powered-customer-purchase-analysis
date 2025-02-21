# Customer Purchase Data Analysis and Recommendation System

This repository contains Python notebooks for analyzing customer purchase data and building a recommendation system. The project is part of a coding assignment for a position at BookedBy, authored by Suchit Singh Nagpal (sn3791@rit.edu).

## Table of Contents

1. [Introduction](#introduction)
2. [Notebooks](#notebooks)
   - [Dataset_creation.ipynb](#1-dataset_creationipynb)
   - [Insights.ipynb](#2-insightsipynb)
   - [Classification.ipynb](#3-classificationipynb)
   - [Recommendation.ipynb](#4-recommendationipynb)
   - [Apriori.ipynb](#5-aprioripy)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)

## Introduction
This project focuses on:
- Analyzing Customer Purchase Data: Gain insights into customer behavior through various visualizations.
- Customer Classification: Use clustering techniques to segment customers based on their purchasing habits.
- Recommendation System: Develop multiple recommendation approaches, including collaborative filtering, content-based filtering, item-based filtering, and hybrid filtering.
- Association Rule Mining: Apply the Apriori algorithm to uncover relationships between products and categories.

## Notebooks

### 1.. Dataset_creation.ipynb

- Purpose: Generate a synthetic dataset simulating customer purchases in a retail scenario.
- Features: 
- Creation of synthetic data for products, customers, and purchase transactions.
- Output saved as a CSV file (customer_purchases3.csv), which serves as the data source for subsequent notebooks.
- Note: Run this notebook to generate the dataset, or use the provided CSV file in the zipped folder.


### 2. Insights.ipynb

This notebook provides insights into customer purchase behavior with visualizations:
- Top-selling categories and products by revenue and purchase frequency.
- Average customer spending per order and trends over time.
- Correlation between the number of orders and average spending per order.
- Average spending per order by category.
- Average order value, and spending per customer.
- Temporal Trends
- Cohort analysis to study customer retention over time.

### 3. Classification.ipynb

In this notebook, customer purchase data is classified using clustering techniques:
- Feature engineering based on frequency, spending, and category preferences.
- K-Means Clustering: Visualizes distinct customer segments.
- Agglomerative Clustering: Focuses on product-based segmentation.
- RFM Analysis: Uses Recency, Frequency, and Monetary metrics to classify customers.

### 4. Recommendation.ipynb

This notebook contains various recommendation methods:
- Collaborative Filtering: Uses purchase behavior of similar customers.
- Content-Based Filtering: Recommends products based on product attributes.
- Item-Based Collaborative Filtering: Uses purchase patterns to find similar items.
- Hybrid Filtering: Combines collaborative and content-based filtering.

The notebook showcases how to generate recommendations for customers and products using each method.


### 5. Apriori.ipynb

This notebook applies the Apriori algorithm to identify association rules in purchase data:
- Transformation of purchase data into transaction format.
- Extraction of frequent itemsets and association rules.
- Visualization of category associations using network graphs.

## Installation and Setup

1. Clone the repository
- Download the zipped file from Google Drive.
- Extract the contents to a desired location on your computer.

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Each notebook is self-contained and can be executed independently. Ensure you have Jupyter Notebook or Jupyter Lab installed to run the `.ipynb` files.

1. Open a notebook in Jupyter:
   ```bash
   jupyter notebook notebook_name.ipynb
   ```

2.  Select the desired notebook (e.g., Dataset_creation.ipynb, Insights.ipynb, etc.) and follow the in-notebook instructions to execute the code cells, analyze data, run models, and generate visualizations.
If needed, regenerate the synthetic dataset by running Dataset_creation.ipynb. The resulting CSV file (customer_purchases3.csv) will be used by the other notebooks for analysis and modeling.