In-Vehicle Coupon Recommendation: Predictive Modeling & EDA
Executive Summary
This project analyzes consumer decision-making in dynamic driving scenarios to predict whether a driver will accept an in-vehicle promotional coupon. By evaluating a combination of demographic data, consumer habits, and real-time situational factors, the project identifies the optimal conditions for targeted marketing.
The Business Problem
To maximize promotional ROI, businesses must move away from generic coupon distribution and adopt context-aware marketing. The objective of this project is to allow food chains and retailers to predict coupon acceptance based on driving context (destination, weather, passengers) and individual habits, enabling highly personalized, data-driven marketing campaigns.
Methodology & Data Preprocessing
Analyzed a multivariate dataset of 12,684 instances from the UCI Machine Learning Repository (ID: 603).
Data Cleaning: Removed highly sparse columns (e.g., car), applied mode imputation for missing categorical values, and standardized data types for modeling.
Feature Engineering: Recoded inconsistent categories, grouped age ranges, and chronologically ordered features (e.g., expiration times, visit frequencies) to improve model interpretability.
Key Behavioral Insights
Expiry Impact: Coupons with a 1-day expiration showed a 22% to 24% higher acceptance rate for restaurants compared to 2-hour expiry coupons, indicating that longer windows significantly boost redemption.
Demographic Surprises: Professionals in Healthcare Support (69.83%) and Construction & Extraction (68.83%) had the highest acceptance rates, challenging the common assumption that students are the most likely demographic to use coupons.
Habit Independence: Inexpensive restaurant (<$20) and take-out coupons maintained high acceptance rates regardless of how often the driver typically visits those establishments.
Machine Learning Performance
Three classification models were trained and evaluated to predict coupon acceptance:
Support Vector Machine (SVM): Best performing model, achieving 73.59% Accuracy and an 80.54% ROC-AUC score.
Logistic Regression: Achieved 68.78% Accuracy and 73.65% ROC-AUC.
Decision Tree: Achieved 67.90% Accuracy and 71.15% ROC-AUC.
Strategic Recommendations
These predictive models and insights provide a blueprint for retail, food delivery, and ride-sharing businesses—particularly in emerging markets like Bangladesh—to introduce in-vehicle coupon systems. By targeting the right customer segments under optimal driving conditions, companies can significantly boost redemption rates, optimize their promotional timing, and reduce wasted marketing spend.

