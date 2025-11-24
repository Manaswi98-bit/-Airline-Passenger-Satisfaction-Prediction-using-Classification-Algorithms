# -Airline-Passenger-Satisfaction-Prediction-using-Classification-Algorithms

A machine learning project designed to predict passenger satisfaction using classification models, feature engineering, and airline survey data.

📌 Project Overview

This project applies classification approaches to understand passenger behavior and predict whether a passenger is Satisfied or Neutral/Unsatisfied.
We analyze survey responses, engineer features, build ML models, and evaluate their performance using multiple metrics.

🧰 Tech Stack

Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Environment: Jupyter Notebook / Google Colab

🔄 Workflow Summary
1. Data Collection

Passenger survey data containing:

Travel class

Inflight service ratings

Seat comfort

Delay information

Customer type

Cleanliness rating

Age, gender

Satisfaction label

2. Exploratory Data Analysis (EDA)

Countplots for satisfaction distribution

Feature distributions

Correlation heatmap

Boxplots for service ratings

Outlier and imbalance detection

3. Feature Engineering

Encoding categorical variables

Scaling numerical features

Handling missing values

Splitting into train and test sets

Feature selection and importance ranking

4. Modeling

Classification algorithms used:

Logistic Regression (baseline)

Random Forest Classifier (best performer)

Gradient Boosting / XGBoost (optional)

5. Evaluation

Metrics:

Accuracy

Precision, Recall, F1-Score

Confusion Matrix

ROC-AUC

Plots:

ROC Curve

Confusion Matrix Heatmap

Feature Importance Chart

6. Prediction & Insights

Model predicts passenger satisfaction on unseen data

Identifies key factors affecting satisfaction such as:

Delays

Seat comfort

Service ratings

Travel class

📈 Key Findings

Service-related features strongly drive satisfaction

Business class passengers show significantly higher satisfaction

Delays drastically reduce satisfaction levels

Ensemble models produce highest accuracy
