🌌 Aurora Borealis Prediction Using Data Fusion & Random Forest | Python & Scikit-Learn

Built an end-to-end supervised machine learning pipeline to predict locations with high potential for observing the Aurora Borealis by combining light pollution data with external solar activity data. This project demonstrates real-world data fusion, feature engineering, labeling strategy design, and model evaluation.

The workflow integrates imputed Globe at Night sky quality measurements with geomagnetic activity indicators (Ap index) sourced from the GFZ Helmholtz Centre for Geosciences. Seasonal features were engineered from timestamps, and a labeled dataset was constructed using domain-driven criteria. A Random Forest classifier was trained and evaluated to distinguish favorable and unfavorable aurora-viewing locations.

This project highlights practical experience in supervised learning, dataset construction, feature engineering, and model evaluation for predictive analytics. 

🛠 Tools & Technologies

Python

Pandas & NumPy

Scikit-Learn (RandomForestClassifier)

Jupyter Notebook

Data Fusion & Feature Engineering

Supervised Machine Learning

🔍 Key ML & Data Tasks

Integrated external solar activity data (Ap index) with observational sky quality data

Engineered seasonal binary features from datetime fields

Constructed synthetic labels based on latitude, sky darkness, and solar intensity

Built balanced training and testing datasets

Trained a Random Forest classifier to predict aurora-favorable locations

Evaluated model performance using classification metrics and reports

📁 Data Outputs

2014_2024_solar_activity.csv – cleaned solar activity dataset

train.csv – labeled training dataset

test.csv – labeled testing dataset
