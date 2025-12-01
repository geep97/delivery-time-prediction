📦 Delivery Time Prediction – Data Analytics Project

This project analyzes 45,000+ food delivery records to understand what factors influence delivery time and to build a foundation for a machine-learning prediction model.
It includes data cleaning, feature engineering, exploratory data analysis (EDA), visualizations, and actionable insights for a delivery company.

🚀 Project Objectives

Clean and prepare a real-world delivery dataset

Analyze patterns affecting delivery duration

Compare vehicle performance (bike, scooter, motorcycle, electric scooter)

Create new features (e.g., distance_km using Haversine formula)

Build the groundwork for a future delivery time prediction model

Provide recommendations to optimize delivery operations

📂 Project Structure
delivery-time-prediction/
│
├── data/
│   ├── raw/
│   │   └── deliverytime.csv
│   └── processed/
│       └── delivery_cleaned.xlsx
│
├── notebooks/
│   └── delivery_analysis.ipynb
│
├── reports/
│   └── Delivery Time Prediction Project Report.pdf
│
├── src/
│   └── (Optional: scripts for cleaning, EDA, modeling)
│
└── README.md

📊 Key Insights
1️⃣ Electric scooters deliver fastest

Electric scooters and scooters have the lowest delivery times.

Motorcycles are slightly slower.

Bicycles are the slowest, adding 5–6 extra minutes on average.

2️⃣ Delivery time distribution

Most deliveries take 20–28 minutes.

Right-skewed distribution → some long delays around 45–55 minutes.

3️⃣ Order type

Meals take longest to deliver (~26.4 min).

Drinks are the fastest (~26.2 min).

Differences are small but consistent.

4️⃣ New feature created

distance_km: calculated using the Haversine formula

This will be the strongest feature for prediction models.

🛠️ Tools & Technologies

Python

Jupyter Notebook

Pandas, NumPy

Matplotlib / Seaborn

Scikit-Learn

Haversine Formula

Excel / CSV data handling

 Report

A full project summary is included in:

📄 reports/Delivery Time Prediction Project Report.pdf

The report contains:

Visualizations

Boxplots by vehicle type

Delivery time distribution

Summary tables

Recommendations

 Future Work

Add weather and traffic data

Build machine-learning models

Linear Regression

Random Forest

Gradient Boosting

Deploy a real-time delivery time predictor

Turn into an API or mobile app integration
