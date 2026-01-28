Telecom Customer Churn Prediction
Advanced Machine Learning | Predictive Analytics

Project Overview
This project predicts customer churn using a robust Ensemble Voting Classifier. By combining multiple models, the solution achieves higher stability and predictive power than a single model, helping telecom providers reduce revenue loss by identifying at-risk customers early.

Technical Deep Dive
- Ensemble Model:Voting Classifier (XGBoost + Extra Trees + Decision Tree).
- Optimization: Hyperparameter tuning via `RandomizedSearchCV` for peak performance.
- Data Balancing: Implemented SMOTE to handle class imbalance in churned vs. non-churned data.
- Preprocessing: Standardized features using `StandardScaler` to ensure model convergence.

Business Insights
- Identifies the top factors leading to customer exit (e.g., contract types, tenure).
- Provides a probability score for each customer, allowing for targeted retention marketing.
