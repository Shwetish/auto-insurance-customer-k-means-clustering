# auto-insurance-customer-k-means-clustering
Mixed-data K-Means clustering project analyzing auto insurance customer details, premium costs, and vehicle data after dummy encoding and normalization.

# Auto Insurance Customer Segmentation & Clustering

## 1. Business Problem
* **1.1. Business Objective:** Analyze customer details related to auto insurance policies to segment policyholders into behavioral groups using transformed categorical features and scaled metrics.
* **1.2. Constraints:** Mixed data types requiring dummy encoding for categorical variables alongside feature scaling for continuous financial values.

## 2. Data Dictionary
| Feature | Data Type | Description |
| :--- | :--- | :--- |
| Customer Demographics & Policy Details | Mixed | Information regarding vehicle class, coverage type, monthly premiums, and claim history. |

## 3. Exploratory Data Analysis (EDA)
* **3.1. Summary:** Evaluated statistical distributions of customer premiums and claim metrics.
* **3.2. Univariate Analysis:** Inspected frequency plots of vehicle types and policy coverages.
* **3.3. Bivariate Analysis:** Explored correlations between claim amounts and premium rates.

## 4. Data Pre-processing
* **4.1. Data Cleaning & Feature Engineering:** Converted categorical variables using one-hot encoding/dummies and normalized numerical columns.

## 5. Model Building
* **5.1. Model Execution:** Built K-Means models on the fully processed mixed feature space.
* **5.2. Scree Plot:** Used Elbow graphs to identify optimal cluster points.
* **5.3. Validation & Insights:** Labeled clusters and derived actionable marketing and risk evaluation insights.

## 6. Business Benefits & Impact
* Helps auto insurance firms design personalized bundle packages, optimize cross-selling initiatives, and accurately price policies according to precise customer segmentation.
