# Flight Price Prediction Project

## Overview

This project focuses on predicting flight ticket prices using a real-world dataset. The aim is to uncover key factors influencing airfare and build a predictive model that estimates ticket prices accurately. The project is designed to reflect the skillset of a Data Analyst / Business Analyst, with a balance of data cleaning, feature engineering, visualization, and basic modeling.

## Problem Statement

Flight prices can vary significantly based on several factors such as airline, duration, number of stops, and time of travel. The goal of this project is to:

- Identify the key drivers affecting flight prices.
- Build a predictive model to estimate ticket prices based on available features.
- Present insights in a business-friendly and visual manner.

## Dataset

The dataset contains details about flights including:

- Airline
- Source and Destination
- Date of Journey
- Departure and Arrival Times
- Duration
- Total Stops
- Additional Info
- Price (target variable)

## Key Steps Performed

### Data Cleaning & Preprocessing
- Parsed date and time columns.
- Extracted relevant features (hour, minute, day, month, etc.).
- Handled null values and removed irrelevant columns.

### Feature Engineering
- Converted categorical columns using Label Encoding.
- Removed less informative or redundant features.

### Exploratory Data Analysis (EDA)
- Visualized relationships between features and price.
- Identified trends such as pricing variation by airline or duration.

### Modeling
- Used Random Forest Regressor for prediction.
- Achieved an R² score of 0.85, indicating strong predictive power.

### Feature Importance Analysis
- Identified top features influencing ticket price:
  - Duration
  - Airline
  - Date
  - Additional Info

## Final Output

A feature importance plot was created to visually present what drives the ticket prices. The most influential features turned out to be Duration, Airline, and Date.

## Business Takeaway

"We used Random Forest to estimate which factors drive ticket prices. The model achieved an R² of 0.85, indicating good predictive power. ‘Duration’, ‘Airline’, and ‘Date’ were identified as the top drivers."

This allows stakeholders to better understand which factors impact pricing, aiding in strategy and pricing decisions.

## Technologies Used

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook

## How to Run

- Clone the repo or download the .ipynb file.
- Open in Jupyter Lab or Jupyter Notebook.
- Run all cells sequentially.

