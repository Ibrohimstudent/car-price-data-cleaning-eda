# Car Price Prediction - Data Cleaning & EDA

## Project Overview

This project demonstrates a complete data cleaning and exploratory data analysis (EDA) workflow using a Kaggle car price prediction dataset.

## Objectives

- Handle missing values
- Remove duplicate records
- Detect and treat outliers
- Explore feature distributions
- Analyze relationships between variables
- Prepare data for machine learning models

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Workflow

1. Dataset Loading
2. Data Cleaning
3. Missing Value Treatment
4. Duplicate Removal
5. Outlier Detection
6. Exploratory Data Analysis
7. Correlation Analysis
8. Key Insights

## Sample Visualizations

### Selling Price Distribution

![Histogram](images/distribution.png)

The histogram visualizes the distribution of vehicle selling prices. The boxplot highlights remaining outliers, while the density curve helps evaluate normality and skewness.

### Correlation Heatmap

![Heatmap](images/heatmap.png)

The correlation heatmap illustrates relationships among numerical features. Strong positive and negative correlations help identify variables that influence selling price.

Insight
Features such as max_power, engine size, and vehicle year show stronger relationships with selling price compared to other variables.

### Outlier Detection

![Outlier Detection](images/outlier_detection.png)
The boxplots compare selling price distributions before and after outlier treatment. The reduction of extreme values results in a more representative dataset.
The histograms show how the target variable distribution changes after removing abnormal observations. The cleaned distribution becomes more balanced and suitable for modeling.

## Key Findings

- Vehicle selling price increases with engine power.
- Newer vehicles generally have higher market value.
- Significant outliers were identified and removed using the IQR method.
- Missing values were successfully handled through imputation techniques.

## Files

- Car_Price_Prediction_Data_Cleaning_and_EDA.ipynb

## Author

- Ibrohim Khudoyberdiyev
- B.Sc. IT (Artificial Intelligence & Data Science) 
- Amity University Tashkent
