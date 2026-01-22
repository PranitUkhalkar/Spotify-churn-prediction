 **Project Overview**

Customer churn is a major challenge for subscription-based platforms like Spotify.
This project builds a machine learning–driven churn prediction system and presents actionable business insights through an interactive Power BI dashboard.

The goal is to identify high-risk users, understand key churn drivers, and support retention strategies.

🧠 Problem Statement

Predict which users are likely to churn and analyze behavioral factors such as:

Usage engagement

Premium subscription status

Content satisfaction

Listening behavior

🛠️ Tools & Technologies

Python (Pandas, Scikit-learn)

Machine Learning: Logistic Regression, Random Forest, XGBoost

Power BI for visualization & business insights

Excel / CSV for data handling

📂 Dataset

Spotify user behavior dataset containing:

Engagement metrics

Usage scores

Satisfaction ratings

Subscription status

Churn label (1 = churned, 0 = active)

🔧 Feature Engineering

Churn Flag (binary)

Risk Segmentation (High / Low risk)

Engagement levels

Aggregated usage & satisfaction scores

🤖 Machine Learning Model

Trained supervised classification models

Generated churn probability per customer

Used probabilities to segment customers by risk

📊 Dashboard Overview (Power BI)
Page 1: Executive Overview

Total Users

Churned vs Active Users

Churn Rate

Risk Segmentation

Engagement vs Churn

Premium Subscription Impact

Page 2: Behavioral Analysis

User Engagement Comparison

Churn Probability Distribution

High-Risk Customer Snapshot

Churn Drivers Analysis

💡 Key Insights

High churn observed among low-engagement and non-premium users

Premium users show significantly better retention

High-risk customers have strong behavioral signals identified by the ML model

📌 Note on Churn Probability

Churn probability values are generated from trained ML models.
High values (close to 1.0) indicate strong confidence of churn risk based on user behavior patterns.

🚀 Future Enhancements

Deploy model using Streamlit

Real-time churn prediction

Automated retention recommendations

👤 Author
Pranit Ukhalkar
