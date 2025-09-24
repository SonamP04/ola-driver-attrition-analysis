# ola-driver-attrition-analysis
Built an end-to-end data analytics solution to predict driver churn using Python (Logistic Regression, ROC-AUC: 0.849) and designed an interactive Power BI dashboard to deliver actionable retention insights.

Project Overview
This project focuses on predicting driver attrition and understanding churn patterns for Ola using real-world driver data. High churn rates significantly impact operational costs and service quality. The goal is to identify key factors influencing churn and provide actionable insights to improve driver retention.

Key Objectives
- Identify drivers most likely to leave based on demographic and performance data.
- Analyze factors like tenure, income, ratings, and city on churn and business value.
- Build predictive models to forecast churn.
- Develop a Power BI dashboard to visualize churn trends and actionable KPIs.

- Tools & Technologies
- **Python (Pandas, Scikit-learn, Matplotlib, Seaborn)** – Data cleaning, feature engineering, predictive modeling  
- **Power BI** – Interactive dashboards and insights visualization  
- **Jupyter Notebook / Google Colab** – Exploratory Data Analysis (EDA) and modeling

  Key Insights
- Drivers with a **Quarterly Rating of 1** have the highest churn rate.  
- **City performance** varies significantly; C13 and C29 contribute the most to business value.  
- **Tenure < 6 months** is a critical churn window — targeted interventions here can reduce attrition by 5–8%.

  Predictive Modeling
- Built a **Logistic Regression model** to classify churn risk.  
- ROC AUC: **0.849**  
- Recommended A/B test strategy to evaluate retention interventions.

  Recommendations
- Launch coaching + incentive program for low-rated drivers.  
- Prioritize retention in the first 6 months post-joining.  
- Replicate successful practices from top-performing cities.

  Files
- `Ola_Case_Study.ipynb` – Python notebook with data cleaning, EDA, and ML model  
- `Ola Case Study.pbix` – Power BI dashboard  
- `Ola Case Study.pdf` – Final project report

 **Status:** Internship Project | Role: Data Analyst  
📍 Focus: Driver churn prediction, retention strategy, and business insights
  
