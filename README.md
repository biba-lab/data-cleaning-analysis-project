📱 Smartphone Usage & Addiction Analysis
Data Analysis Project – Python, Pandas, Seaborn, Matplotlib

📌 Overview
This project analyzes a dataset of 7,500 users to explore smartphone usage patterns, screen time habits, addiction levels, stress, sleep, and the impact on academic/work performance.
The goal is to understand how different factors (age, gender, notifications, app usage, stress…) influence daily screen time and addiction.
The analysis was performed using Python, with a focus on data cleaning, exploratory data analysis (EDA), visualization, and correlation insights.

🛠️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Google Colab

📂 Dataset
The dataset includes variables such as:
Age, gender
Daily screen time (hours)
Social media, gaming, work/study usage
Notifications per day
App opens per day
Sleep hours
Stress level
Addiction level
Academic/work impact

🔧 Data Cleaning
Main cleaning steps:
Removed duplicates
Removed rows with missing values
Standardized column names
Filtered unrealistic values (age < 10 or > 100, screen time > 24h)
Converted categorical levels into numeric codes
Created new grouped variables:
age_group
notif_group

📊 Exploratory Data Analysis (EDA)
1. Screen Time by Age Group
Boxplots and group means show how screen time varies across age ranges (18–25, 25–30, 30–35).
2. Screen Time by Gender
Comparison of daily usage between male and female users.
3. App Usage Analysis
Average time spent on:
Social media
Gaming
Work/Study
With breakdown by gender.

📈 Visualizations
The notebook includes:
Boxplots
Bar charts
Heatmaps
Grouped means
Correlation plots
These help visualize relationships between usage patterns and behavioral factors.
