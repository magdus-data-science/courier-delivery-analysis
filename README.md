# Courier Delivery Analysis
This project analyzes bicycle courier deliveries using Python and machine learning techniques. The analysis focuses on operational efficiency, earnings, weather conditions, and delivery duration prediction.

## Business Problem

The goal of this project was to identify factors affecting courier earnings and delivery efficiency in urban food delivery operations.

## Dataset

The dataset contains completed bicycle courier deliveries including:
- timestamps,
- delivery duration,
- weather conditions,
- earnings,
- tips,
- delivery districts,
- multiplier factors.

## Tech Stack

- Python (feature engineering, eda, machine learning)
  - pandas
  - numpy
  - matplotlib
  - geopandas
  - seaborn
  - plotly
  - scikit-learn
  - jupyter

- R (cleaning, feature engineering, statistics)
  - readr
  - lubridate
  - tidyverse
  - dplyr
  - corrplot
- PowerBI (dashboard)


## Project Structure

├── data/
├── notebooks/
├── dashboard/
├── reports/
└── README.md

## Methodology

1. Data cleaning and preprocessing
2. Feature engineering
3. Exploratory Data Analysis
4. Statistical analysis
5. Machine learning modeling
6. Dashboard development

## Key Insights

- Evening hours generated the highest earnings.
- Wind speed increased average delivery duration.
- Weekend orders produced higher average earnings.
- Some districts consistently showed lower operational efficiency.

## Machine Learning

Random Forest achieved:
- MAE: ~7 minutes
- RMSE: ~9 minutes

The model showed moderate predictive performance due to missing operational variables 
such as traffic intensity and restaurant preparation time.

## How to Run

git clone ...
cd courier-delivery-analysis

pip install -r requirements.txt

jupyter notebook

## Future Improvements

- Add traffic data
- Add route distance
- Deploy dashboard online
- Improve model performance using boosting algorithms
- Add measured restaurant time
