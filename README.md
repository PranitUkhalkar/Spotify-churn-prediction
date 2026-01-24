
# Spotify User Churn Prediction System

##  Project Overview
This project focuses on building a **Churn Prediction System** to identify Spotify users who are likely to stop using the service.  
Customer churn prediction is critical for subscription-based platforms, as retaining users is more cost-effective than acquiring new ones.

The project combines **machine learning modeling** with **business-focused analytics dashboards** to provide actionable insights.

---

##  Objectives
- Analyze user behavior and engagement patterns
- Predict churn probability for each user
- Identify key factors driving churn
- Segment users based on churn risk
- Present insights through an interactive Power BI dashboard

---

##  Dataset
- Domain: Music streaming (Spotify-like user data)
- Records: ~500 users
- Features include:
  - Usage Score
  - Podcast Frequency Score
  - Recommendation Rating
  - Premium Subscription Status
  - Engagement Level
  - Satisfaction Metrics

Dataset is stored in: data/spotify_churn.csv


---

##  Machine Learning Approach
The following classification models were trained and evaluated:
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

### Feature Engineering
- Churn flag creation
- Usage and engagement scoring
- Risk segmentation based on churn probability

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- ROC-AUC
- Confusion Matrix
- Churn Probability per user

All ML work is available in: notebooks/spotify_churn_prediction.ipynb


---

##  Power BI Dashboard
An interactive Power BI dashboard was created to translate model outputs into business insights.

### Page 1: Churn Overview & Risk Segmentation
- KPI Cards (Total Users, Churn Rate, Avg Usage Score, Avg Churn Probability)
- Churned vs Active Users
- Customer Risk Segmentation
- User Engagement vs Churn

### Page 2: Churn Drivers & User Behavior Analysis
- Premium Subscription Impact on Churn
- User Engagement Metrics by Churn Status
- High-Risk Customer Snapshot
- Churn Probability Distribution
- Decomposition Tree / Influencer Analysis

Dashboard file: powerbi/churn_dashboard.pbix


---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Power BI

---

##  Key Outcomes
- Successfully predicted churn probability for each user
- Identified key churn drivers such as engagement level and premium status
- Created a business-ready dashboard for decision-makers

---

##  Future Enhancements
- Deploy model using Streamlit
- Automate data refresh
- Add real-time churn monitoring

pandas
numpy
scikit-learn
matplotlib
xgboost
