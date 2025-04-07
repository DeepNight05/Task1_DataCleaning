# Customer Personality Data Cleaning

This project is part of my Data Analyst Internship submission and focuses on cleaning and preprocessing the **Customer Personality Analysis** dataset from Kaggle. The primary objective was to prepare the dataset for deeper customer segmentation and behavior analysis by handling inconsistencies and visualizing core demographic patterns.

---

## Dataset Information

- **Source:** [Kaggle – Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  
- **Original File:** `marketing_campaign.csv`  
- **Records:** Demographic and purchase behavior data of customers from a marketing campaign  

---

## Objectives

1. Remove missing values and duplicates to ensure dataset integrity.  
2. Standardize categorical fields by trimming and converting to lowercase.  
3. Convert date formats for temporal analysis.  
4. Normalize and rename columns for improved readability and consistency.  
5. Save a clean version of the dataset for further analysis.  

---

## Data Cleaning Process

- Checked for and visualized missing values  
- Dropped null entries and duplicate records  
- Converted string-based columns to lowercase and removed extra whitespace  
- Renamed columns using a consistent naming convention  
- Converted date fields to proper datetime formats  
- Validated and converted column types using pandas’ `convert_dtypes()`  

---

## Visualizations

The following initial insights were derived post-cleaning:

- **Missing Value Heatmap** – Identified and confirmed missing fields before dropping them  
- **Income Distribution** – Histogram displaying skewness and distribution spread  
- **Education Levels** – Bar chart of customer education demographics  
- **Spending Behavior** – Bar chart showing average spend per product category  

These visuals help in building a strong foundation for customer segmentation and targeting strategies.

---

## Tools and Libraries

- Python 3.11  
- pandas  
- seaborn  
- matplotlib  
- Jupyter Notebook  
- Visual Studio Code  

---

## Summary

This project demonstrates key data cleaning and preprocessing steps necessary in a real-world analytical workflow. The cleaned dataset is ready to be used for customer segmentation, clustering, and deeper behavioral analysis.
