**Predictive Maintenance Using Machine Learning**

🛠️ Overview

This project predicts potential machine failures in industrial and manufacturing sectors using machine learning techniques. By analyzing sensor and operational data, it enables:

Proactive maintenance scheduling

Reduced downtime

Minimized operational costs

📊 Dataset Description

Source: Kaggle Predictive Maintenance Dataset

Records: 10,000 data points with 14 features

Failure Types:

Tool Wear Failure

Heat Dissipation Failure

Power Failure

Overstrain Failure

Random Failures

🎯 Objective

Develop a predictive model to identify impending machine failures, improving:

Maintenance scheduling

Reduction of unexpected downtimes

📋 Key Steps

1. Data Preprocessing

No Missing Values: The dataset contains complete data.

Outlier Handling:

Identified using Interquartile Range (IQR).

Applied log transformation for extreme values.

Scaling:

Standardized numerical features (e.g., air temperature, rotational speed).

Encoding:

Categorical features transformed using One-Hot Encoding.

2. Exploratory Data Analysis (EDA)

Key Patterns:

Temperature Correlation: Strong positive relationship between air and process temperatures.

Rotational Speed vs Torque: Inverse correlation observed.

3. Feature Engineering

Mechanical Power: Product of rotational speed and torque.

Temperature Difference: Difference between process and air temperatures.

Applied log transformation to engineered features for stability.

4. Model Training

Models Evaluated:

Random Forest

Gradient Boosting

XGBoost

AdaBoost

Logistic Regression

Best Model:

XGBoost achieved 97.8% accuracy.

🏆 Results

XGBoost Performance

Accuracy: 97.8%

Precision: 0.64

Recall: 0.72

F1 Score: 0.68

Key Insights

Proactive Maintenance: Effectively identifies failures before escalation.

Resource Optimization: Enables efficient scheduling and cost reduction.

🚀 Key Takeaways

Proactive Maintenance:

Identify machine failures early to prevent costly downtimes.

Resource Optimization:

Efficient scheduling reduces unnecessary maintenance costs.

🔮 Future Work

Real-time Data Integration: Enable dynamic analysis.

IoT Deployment: Use sensor data for continuous monitoring.

Adaptive Model Retraining: Improve predictions over time.

🙌 Acknowledgments

Dataset: Provided by Kaggle.

Libraries: Utilized open-source tools for development.

