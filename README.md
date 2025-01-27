# Data Science Project: Analysis of eCommerce Transactions – ZeoTap Internship Assignment



## Overview

This repository contains the solution to the Data Science Intern Assignment provided by Zeotap. The primary objective of this assignment is to analyze and process eCommerce data to derive actionable insights, segment customers, and build predictive models. The tasks cover the entire data science lifecycle, including data cleaning, exploratory data analysis (EDA), clustering, and lookalike modeling.

---

## Project Objectives

1. **Exploratory Data Analysis (EDA):**

   - Perform an in-depth analysis of the datasets to understand key trends, patterns, and relationships.
   - Handle missing values and outliers to ensure data quality.

2. **Customer Segmentation:**

   - Apply clustering algorithms to segment customers based on their transactional and behavioral data.
   - Visualize clusters and provide insights for targeted marketing strategies.

3. **Lookalike Modeling:**

   - Develop models to identify potential customers who resemble the most profitable segments.

4. **Recommendations and Insights:**

   - Summarize findings and provide actionable recommendations for business decision-making.

---

## Dataset Description

The project leverages the following datasets:

1. **Transactions.csv**

   - Contains customer transaction details.
   - Fields: `Transaction_ID`, `Customer_ID`, `Product_ID`,`Quantity`, `Price`, `Transaction_Date`.

2. **Customers.csv**

   - Provides demographic and behavioral data about customers.
   - Fields: `Customer_ID`, `CustomerName`, `Region`, `SingupDate`.

3. **Products.csv**

   - Includes information on products.
   - Fields: `Product_ID`, `ProductName`, `Category`, `Price`.

4. **Lookalike.csv**

   - Data for generating lookalike models to predict new customer behavior.
   - Fields: Various behavioral and demographic features.

---

## Folder Structure

```
Data-Science-Intern-Assignment-Zeotap/
|
|-- data/                     # Contains the raw datasets
|   |-- Customers.csv
|   |-- Transactions.csv
|   |-- Products.csv
|   |-- Lookalike.csv
|
|-- notebooks/                # Jupyter notebooks for analysis and modeling
|   |-- EDA.ipynb             # Exploratory Data Analysis
|   |-- Clustering.ipynb      # Customer segmentation
|   |-- Lookalike_Modeling.ipynb # Lookalike model development
|
|-- outputs/                  # Final results and visualizations
|   |-- Clustering_Results.csv
|   |-- Lookalike_Predictions.csv
|
|-- reports/                  # Summary reports and insights
|   |-- EDA_Summary.pdf
|   |-- Clustering_Report.pdf
|   |-- Lookalike_Report.pdf
|
|-- README.md                 # Project documentation (this file)
```

---

## Key Steps

### 1. Exploratory Data Analysis (EDA)

- **Objective:** Understand the data distribution, identify trends, and address missing or inconsistent data.
- **Tasks:**
  - Analyze features like customer demographics, purchase behavior, and product categories.
  - Visualize data using histograms, scatter plots, and heatmaps.
  - Compute summary statistics for insights.

### 2. Clustering

- **Objective:** Segment customers into distinct groups based on their purchasing and behavioral patterns.
- **Algorithm:** K-Means Clustering.
- **Steps:**
  1. Preprocess data (normalize features and handle missing values).
  2. Apply the elbow method to determine the optimal number of clusters.
  3. Fit the K-Means model and evaluate results using metrics like silhouette score.
  4. Visualize clusters using PCA (Principal Component Analysis).

### 3. Lookalike Modeling

- **Objective:** Predict potential customers similar to the most valuable segments.
- **Approach:**
  - Train a supervised machine learning model (e.g., Random Forest, Logistic Regression) using labeled data from profitable customer segments.
  - Evaluate model performance using metrics like accuracy, precision, and recall.
  - Generate predictions and visualize results.

### 4. Insights and Recommendations

- **Deliverables:**
  - Business-friendly insights from EDA and clustering.
  - Detailed reports and presentations summarizing findings.

---

## Tools and Technologies

- **Programming Language:** Python
- **Libraries:**
  - Data Manipulation: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn
- **Development Environment:** Jupyter Notebook

---

## How to Run the Project

### Prerequisites

1. Install Python 3.8 or later.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Data-Science-Intern-Assignment-Zeotap.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Data-Science-Intern-Assignment-Zeotap
   ```
3. Run the notebooks in the following order:
   - `EDA.ipynb`
   - `Clustering.ipynb`
   - `Lookalike_Modeling.ipynb`

---

## Results

1. **EDA Insights:**

   - Key trends in customer demographics and transactional data.
   - Identification of top-selling products and peak purchasing periods.

2. **Customer Segments:**

   - Segmented customers into actionable groups (e.g., high spenders, frequent buyers).
   - Visualizations of clusters for better interpretability.

3. **Lookalike Predictions:**

   - Identified potential new customers for marketing campaigns.

---

## Contributors

- Venkaiahgari Saiprakash

---



This project is licensed under the MIT License. See the LICENSE file for details.

