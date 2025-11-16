🌞 Solar Energy Prediction (Edunet Internship Project)

📘 Overview

This project predicts solar power generation using real data from Indian Solar Power Plants.
Developed as part of the Edunet Foundation Internship under the domain Energy Prediction.


---

🗓 Weekly Progress

Week 1 – Data Loading & Understanding

Uploaded and extracted dataset files

Loaded CSV into Google Colab

Explored dataset shape, columns, and sample data



---

Week 2 – Model Training & Prediction

Preprocessed data (converted DATE_TIME, extracted HOUR)

Split data into train/test sets

Trained Linear Regression and Random Forest models

Evaluated performance using R² Score and MAE

Random Forest achieved R² = 1.0 and MAE = 0.145 🎯



---

Week 3 – EDA, Feature Engineering & Advanced Modeling

Performed detailed EDA:

AC Power distribution

Hourly trends

Correlation heatmap


Added feature engineering:

HOUR, WEEKDAY

ROLLING_DC_4

EFFICIENCY


Trained advanced model using XGBoost

Evaluated model with R² and MAE

Saved final model for dashboard use



---

⚙ Tools & Libraries

Python

Google Colab

Pandas

NumPy

Scikit-learn

XGBoost

Matplotlib

Seaborn



---

📊 Results Summary

Model	R² Score	MAE	Remarks

Linear Regression	1.00	0.715	Baseline model
Random Forest	1.00	0.145	Excellent performance
XGBoost (Week 3)	~0.99–1.00	Improved	Feature-rich model



---

👨‍💻 Author

Roy
Engineering Student — Edunet Foundation Internship
