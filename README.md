# US Accidents Machine Learning Analysis (2016–2023)

## Overview
This project analyzes the US Accidents dataset (2016–2023) using data preprocessing, exploratory data analysis (EDA), and machine learning techniques. The goal is to understand accident patterns and predict accident severity.

## Dataset
- Source: Kaggle (US Accidents Dataset)
- Size: ~7.7 million records
- Features: Weather conditions, time, location, and road attributes

## Methodology
The following steps were implemented:

1. Data Preprocessing
   - Removed columns with excessive missing values
   - Filled missing data using appropriate techniques

2. Exploratory Data Analysis (EDA)
   - Visualized accident patterns (severity, weather, time, location)

3. Feature Engineering
   - Extracted features such as hour, day, month, and weekend indicator

4. Model Training
   - Logistic Regression
   - Random Forest
   - Gradient Boosting

5. Model Evaluation
   - Accuracy
   - Precision
   - Recall
   - F1 Score

## Results
Machine learning models were able to predict accident severity with reasonable accuracy. Ensemble models performed better compared to basic models.

## Real-World Impact
The findings can help traffic authorities and planners identify high-risk conditions and improve road safety strategies. This contributes to better traffic management and accident prevention.

## Files
- Notebook: `US_Accidents_Methodology.ipynb`
- Cleaned Dataset: `us_accidents_cleaned.csv`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
