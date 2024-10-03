# Email Campaign Effectiveness Prediction (Classification)

# Deployment:
The project has been deployed on Streamlit for real-time predictions.
You can access the app here.(Please wait it may take some time):
https://email-campaign-effectiveness-prediction.streamlit.app/

# Problem Statement:
The goal of this project is to predict how customers will respond to email campaigns by classifying whether an email will be ignored, read, or acknowledged. This helps businesses optimize marketing strategies and improve engagement rates.

# Data Overview:
The dataset contains various features related to email campaigns and customer behavior, including:
Email Campaign Type (Type of campaign)
Customer Information (Location, past engagement)
Email Metadata (Number of words, links, images)
Engagement Metrics (Total past communications, subject hotness score, time sent)
Approach:

# Exploratory Data Analysis (EDA):
Visualization of email engagement (ignored, read, acknowledged), identifying key patterns, and correlation analysis (e.g., between email length and acknowledgment rates).

# Data Preprocessing:
Handling missing values and encoding categorical features.
Addressing class imbalance using oversampling.

# Modeling:
Machine learning models tested:
Logistic Regression
Decision Tree
XGBoost (with hyperparameter optimization)

# Models Used:
Logistic Regression (Baseline model)
Decision Tree (Improved accuracy)
XGBoost (Final model with around 80% accuracy)

# Results:
XGBoost achieved an accuracy of ~80% and precision of ~75%.
Insights revealed:
Campaign Type 1 had the lowest engagement, while Campaign Type 3 performed best.
Emails sent in the evening were mostly ignored, whereas morning and night emails performed better.

# Outputs:
Predictions on email success based on campaign type, customer location, and email metadata.
Insights on optimal email characteristics (e.g., length, time of day).

# Conclusion:
Email Campaign Type and customer location significantly affect engagement.
Email length and time sent influence customer interaction.
Optimizing these factors can help businesses personalize campaigns and increase success.


