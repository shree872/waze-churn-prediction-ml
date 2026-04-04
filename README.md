# waze-churn-prediction-ml# Waze Churn Prediction (Machine Learning Project)

# Project Overview

This project focuses on predicting user churn using machine learning techniques. The goal is to identify users likely to stop using the platform and provide insights to improve user retention.

# Business Objective

The objective of this project is to help stakeholders at Waze identify high-risk users and take proactive measures to reduce churn and improve customer retention.

# Dataset

* Source: Waze dataset (Google Advanced Data Analytics Certificate)
* Description: Contains user activity, engagement metrics, and behavioral data

# Key Insights from Analysis

* Users with lower engagement levels were more likely to churn
* Certain usage patterns showed strong correlation with churn
* Behavioral features played a key role in predicting churn

# Machine Learning Model

* Model Used: Random Forest (Cross validation)
* Techniques: Feature Engineering, Model Training, Evaluation
* Performance: precision->0.457163; recall->0.126782;	F1->0.198445;	accuracy->0.81851
  

# Business Recommendations

* The model is good for churn prediction when guiding further exploratory efforts, then it can have value.
* New features could be engineered to try to generate better predictive signal. In the case of this model, the engineered features made up over half of the top 10 most-predictive features used by the model.
* It could also be helpful to reconstruct the model with different combinations of predictor variables to reduce noise from unpredictive features.
* It would be helpful to have drive-level information for each user (such as drive times, geographic locations, etc.).
* It would probably also be helpful to have more granular data to know how users interact with the app.

# Project Files

* Notebook: 
* Executive Summary: 

# Tools & Technologies

Python, Pandas, NumPy, Matplotlib, Scikit-learn

