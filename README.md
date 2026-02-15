# Insurance_Cost_Prediction_Project
Built ML models to predict insurance charges, with Random Forest and Gradient Boosting delivering the best performance (highest R², lowest RMSE). Smoking status was the most influential feature, followed by age and BMI. Model is stable, production-ready, and supports premium pricing, risk segmentation, and business decision-making.
---
Insurance Cost Prediction Project
Project Overview

This project builds and evaluates multiple Machine Learning models to predict medical insurance charges based on demographic and lifestyle factors. The goal is to identify key cost drivers and develop a production-ready prediction model.
----
Objective

Predict insurance charges accurately

Compare multiple regression models

Identify most influential features

Prepare model for real-world deployment
---
Dataset Information

Features:

Age

Gender

BMI

Number of Children

Smoking Status

Region

Target Variable:

Insurance Charges
---
Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn
---
 Step-by-Step Workflow
Step 1: Data Loading

Imported dataset using Pandas

Checked missing values

Performed initial exploration

Step 2: Data Preprocessing

Encoded categorical variables

Handled feature scaling where required

Split dataset into train and test sets

Step 3: Exploratory Data Analysis (EDA)

Correlation analysis

Distribution plots

Feature impact visualization

Identified smoking status as dominant factor

Step 4: Model Building

Trained multiple regression models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Step 5: Model Evaluation

Used performance metrics:

R² Score

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Best Model:
Random Forest / Gradient Boosting (based on evaluation results)

Step 6: Feature Importance Analysis
---
Extracted feature importance

Smoking status had highest impact

Age and BMI were strong predictors
---
Model Performance

High R² Score

Low prediction error

Good generalization on unseen data
---
Production Recommendations

Deploy tuned ensemble model

Retrain periodically with new data

Monitor performance drift

Add more health-related features
---
Business Applications

Insurance premium pricing

Risk segmentation

Customer profiling

Actuarial analysis support
---
Future Improvements

Apply log transformation

Use XGBoost / LightGBM

Advanced feature engineering
---
Hyperparameter optimization

How to Run the Project
# Clone the repository
git clone https://github.com/yourusername/insurance-cost-prediction.git

# Navigate to project folder
cd insurance-cost-prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
