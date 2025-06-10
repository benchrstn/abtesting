# A/B Test Analysis for Foodtech Company

## Project Overview
In this project, a company conducting food delivery service recently run an A/B test to improve user experience and and conversion rates. The goal is to determine if displaying larger food images on restaurant menu cards leads to higher order by helping users better understand how meals look.

## Dataset Overview
The dataset includes:
- datetime: timestamp of user activity
- variation: group 1 or 2
- platform: iOS or Android
- shop_id: shop identifier
- user_id: unique customer
- session_id: identifier for each purchase session
- final_order_status: success, cancelled, refunded, or blank

## Key Steps
- Data Validation
- Exploratory Data Analysis (EDA)
- Duplicate removal for session to reduce data
- User-level aggregation to ensure independence
- Sampling to balance variation sizes
- Statistical testing with two-proportion z-test
- Results verification with confidence intervals

## Key Insights
- Variation 2 showed a statistically significant improvement in conversion rate
- Conversion lift: 1.04%, p-value < 0.05
- Confidence intervals confirm reliability of the improvement

## Tools
- **Programming**: Python
- **Environment**: Jupyter Notebook
- **Library**: Pandas, Matplotlib, Seaborn, Statsmodels

Full report can be seen in the notebook file.
