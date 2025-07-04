# National Health Aand Nutrition Examination Survey - Exploratory Data Analysis (EDA)
This project performs a detailed exploratory data analysis on the NHANES (National Health and Nutrition Examination Survey) 2013-2014 dataset to explore health-related variables, focusing on BMI and its relationship with other factors such as age, gender, smoking, and education.

## Overview
The NHANES dataset contains demographic, examination, and questionnaire data collected through surveys and physical examinations. This EDA project aims to:

Understand the structure and quality of the data

Clean and preprocess the dataset by handling missing values and outliers

Explore distributions and relationships among variables

Conduct univariate, bivariate, and multivariate analyses

## Dataset
### Source: NHANES 2013-2014 (available on Kaggle)

### Key variables analyzed include:

Demographic: gender, age, education, smoking status

Physical measurements: weight, height, BMI

Additional health indicators as available

## Key Steps
Data Loading
Load demographic, examination, and questionnaire CSV files.

Data Cleaning

Remove duplicate rows

Handle missing values by dropping rows with missing critical data

Detect and remove outliers for numerical variables (weight, height, BMI)

Data Transformation

Rename columns for ease of use

Encode categorical variables (e.g., smoking, gender, education) using one-hot encoding

Exploratory Data Analysis

Univariate analysis: distribution of age, BMI, weight, height, smoking, and education

Bivariate analysis: correlation and visualization of BMI with age, gender, and smoking

Test BMI differences by age groups and gender

Evaluate smoking prevalence across demographic groups

## Libraries Used
pandas, numpy — data manipulation

matplotlib, seaborn — visualization

statsmodels — statistical testing
