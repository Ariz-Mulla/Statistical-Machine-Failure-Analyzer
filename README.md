# Statistical Analysis Projects

A pair of individual statistics projects, each carrying a dataset through the full analytics pipeline — visualization, descriptive statistics, probability, and inference — on real-world engineering and health data. Project 1 was built in Excel; Project 2 in MATLAB.

## 1 - Machine Failure Risk Analysis (Excel)

Analyzes 1,000 readings from industrial machines (`machine_failure_dataset.csv`: temperature, vibration, power usage, humidity, machine type, and a binary failure-risk flag) to determine whether the machines are operating within acceptable limits.

Includes:

* Visualization — histogram, boxplot, and a normal probability (QQ) plot
* Descriptive statistics — mean, median, mode, standard deviation, variance, range, quartiles/IQR, and outlier flagging via the 1.5×IQR rule
* Probability — empirical event probabilities from the data (e.g. Temperature > 50, Failure Risk = 1) and their intersection/union
* Distribution fitting — a normal distribution fit to the data, with its PDF overlaid on the histogram
* Sampling distributions built from repeated samples at n = 5, 20, and 50
* Inference — 95% confidence intervals and hypothesis testing

Files: `Project1_Machine_Failure_Risk_Analysis.xlsx` (the completed analysis), `machine_failure_dataset.csv` (dataset), and `Machine-Failure-Report.pdf` (report).

## 2 - Heart Rate Regression (MATLAB)

Models Maximum Heart Rate as a function of Age using a 303-patient cardiology dataset (`Heart_Disease_Dataset.csv`).

Includes:

* Scatter plot with correlation coefficient — r = -0.40, a moderate negative linear relationship
* Simple linear regression — MaxHeartRate = 204.29 - 1.005 × Age, so each extra year of age costs roughly 1 bpm off predicted max heart rate
* Inference — 95% confidence intervals on the slope and intercept, plus a hypothesis test for whether the slope equals zero (p-value and conclusion reported)
* Diagnostics — residual plot to check linearity and constant-variance assumptions
* Predictions for two new patients (ages 40 and 65), and a one-way ANOVA comparing heart rate across age groups

Files: `Project2_Heart_Rate_Regression.mlx` (MATLAB Live Script — opens in MATLAB), `Heart_Disease_Dataset.csv` (dataset), and `Heart-Rate-Regression-Report.pdf` (report).

## Skills demonstrated

Descriptive and inferential statistics, probability, distribution fitting, sampling distributions, confidence intervals, hypothesis testing, correlation, linear regression, and ANOVA — applied in both Excel and MATLAB.
