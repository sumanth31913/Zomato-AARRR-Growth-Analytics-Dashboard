🍽️ Zomato AARRR Growth Analytics Dashboard

A comprehensive Power BI dashboard designed using the AARRR (Acquisition, Activation, Retention, Referral, Revenue) framework to analyze customer growth, engagement, and revenue performance for a food delivery platform similar to Zomato.

📌 Project Overview

This project demonstrates how product and growth teams can use the AARRR framework to track the complete customer journey, identify growth bottlenecks, and make data-driven decisions.

The dashboard provides insights into:

User acquisition channels
Customer activation and engagement
Retention and repeat usage
Referral performance
Revenue growth trends
Geographic revenue distribution
🎯 Business Objective

The primary goal of this dashboard is to answer key business questions:

Acquisition
Which channels bring the most users?
What are the top-performing acquisition sources?
Activation
How many users become active customers?
What percentage of users place their first order?
Retention
How many customers return after their first purchase?
What is the retention performance over time?
Referral
How many users refer others?
What is the referral contribution to growth?
Revenue
Which cities generate the highest revenue?
How is revenue growing over time?
📊 Dashboard Features
Executive Summary

Key performance indicators:

Total Users
Activated Users
Retained Users
Referral Users
Total Revenue
Revenue Trend Analysis

Tracks monthly revenue performance and growth trends.

Insights:

Revenue fluctuations across months
Peak revenue periods
Business growth tracking
User Growth Trend

Analyzes monthly user acquisition growth.

Insights:

User growth pattern
Signup trends
Customer acquisition performance
Acquisition Channel Analysis

Visualizes user acquisition across:

Instagram
Google Ads
Organic Search
Facebook
Referral

Insights:

Best-performing marketing channels
User acquisition distribution
Revenue by City

Identifies top-performing cities based on revenue contribution.

Cities Included:

Bengaluru
Hyderabad
Mumbai
Delhi
Pune
Chennai
🛠️ Tools & Technologies
Power BI
Interactive Dashboard Development
Data Modeling
Visualization Design
SQL
Data Cleaning
Data Analysis
Business Queries
DAX
KPI Measures
Retention Calculations
Revenue Metrics
User Metrics
📂 Dataset Structure
Users Table
Column
user_id
signup_date
city
acquisition_source
device_type
Orders Table
Column
order_id
user_id
order_date
order_amount
restaurant_id
Restaurants Table
Column
restaurant_id
restaurant_name
city
category
Referrals Table
Column
referral_id
referrer_user_id
referred_user_id
referral_date
📈 Key Metrics
Total Users
DISTINCTCOUNT(users[user_id])
Activated Users
DISTINCTCOUNT(orders[user_id])
Retained Users

Users with more than one order.

Referral Users

Distinct users who referred other users.

Total Revenue
SUM(orders[order_amount])
💡 Key Insights
Instagram emerged as one of the strongest acquisition channels.
Bengaluru generated the highest revenue among all cities.
Revenue showed a stable growth trend across the year.
User acquisition remained consistent throughout the selected period.
Referral users contributed significantly to organic growth.
🚀 Future Enhancements
Add complete AARRR Funnel Visualization
Implement Cohort Retention Analysis
Add Customer Segmentation
Track Customer Lifetime Value (CLV)
Build Churn Prediction Model
Include Marketing ROI Analysis
📚 Learning Outcomes

Through this project, I gained hands-on experience in:

Product Analytics
Growth Metrics Analysis
AARRR Framework
Power BI Dashboard Development
DAX Calculations
SQL Data Analysis
Business Intelligence Reporting
👨‍💻 Author

Sumanth Mannem
