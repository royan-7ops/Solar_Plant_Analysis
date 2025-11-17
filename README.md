🌞 Solar Energy Prediction (Edunet Internship Project)

📘 Overview

This project predicts solar power generation using real-world data collected from Indian Solar Power Plants.
It was developed as part of the Edunet Foundation Internship under the domain Energy Prediction.
The goal is to analyze solar generation behavior, engineer meaningful features, and build accurate ML models for AC Power prediction.


🗓 Weekly Progress

Week 1 – Data Loading & Understanding

Uploaded and extracted dataset files in Google Colab

Loaded CSV data using Pandas

Explored dataset structure (shape, columns, datatypes, sample rows)



Week 2 – Model Training & Prediction

Preprocessed data (DATE_TIME conversion, extracted HOUR)

Split data into Training & Testing sets

Trained:

Linear Regression

Random Forest Regressor


Evaluated performance using R² Score and MAE

Random Forest Results:

R² = 1.0

MAE = 0.145 🎯



Week 3 – EDA, Feature Engineering & Advanced Modeling

Exploratory Data Analysis (EDA)

AC Power distribution

Hourly energy trends

Correlation heatmap to understand feature relationships


Feature Engineering

HOUR – extracted from timestamp

WEEKDAY – detects weekday/weekend behavior

ROLLING_DC_4 – 4-point moving average of DC Power

EFFICIENCY – AC/DC ratio to capture conversion performance



Advanced Modeling

Trained XGBoost Regressor for improved performance

Evaluated model using R² and MAE

Saved the final trained model for future dashboard integration



⚙ Tools & Libraries

Python

Google Colab

Pandas

NumPy

Scikit-learn

XGBoost

Matplotlib

Seaborn



📊 Results Summary

Model	R² Score	MAE	Remarks

Linear Regression	1.00	0.715	Baseline model
Random Forest	1.00	0.145	Excellent performance
XGBoost (Week 3)	~0.99–1	Lower	Feature-rich model



👨‍💻 Author

Roy
Engineering Student | Edunet Foundation Internship (Energy Prediction)
