# TrafficAccidentSeverity
🛣️ Statistical and Predictive Analysis of Traffic Accident Severity

📘 Project Overview

Road accidents are a major global concern, causing fatalities, severe injuries, and economic losses. This project aims to analyze and predict the severity of traffic accidents through statistical and predictive modeling techniques.
By exploring both global datasets and Bangladesh-specific traffic data, the project seeks to uncover key factors influencing accident severity and provide insights for improving road safety policies.

The study applies descriptive, inferential, and predictive statistical methods to discover trends, test hypotheses, and build a regression-based prediction model for accident severity.

⚙️ Tools and Technologies

Jupyter Notebook – Interactive environment for analysis and visualization

Python Libraries:

🧮 NumPy – Numerical computations

🧹 Pandas – Data cleaning, manipulation, and grouping

📊 Matplotlib & Seaborn – Data visualization and plotting

📈 SciPy – Statistical testing (Shapiro-Wilk, KS test, parametric & non-parametric tests)

🤖 Scikit-learn – Machine learning and predictive modeling

🎯 Objectives

Clean and preprocess the traffic accident dataset for analysis

Apply descriptive statistics (mean, median, mode, standard deviation, skewness, kurtosis)

Assess data normality using Shapiro-Wilk and Kolmogorov-Smirnov tests

Perform parametric and non-parametric tests to identify significant factors affecting accident severity

Build and evaluate a regression model to predict accident severity

Derive insights into Bangladesh’s traffic accident patterns, alongside global analysis, to support localized road safety improvements

🧠 Methodology
1. Data Cleaning & Preparation

Handle missing values, duplicates, and inconsistencies

Encode categorical variables where required

2. Exploratory Data Analysis (EDA)

Group data by relevant factors (e.g., weather, road type, time of day)

Compute measures of central tendency and dispersion

Visualize distributions, correlations, and patterns

3. Statistical Analysis

Normality Testing: Shapiro-Wilk, Kolmogorov-Smirnov

Parametric Tests: t-test, ANOVA

Non-Parametric Tests: Mann-Whitney U, Kruskal-Wallis

4. Predictive Modeling

Split data into training and testing sets

Build a Linear Regression or Logistic Regression model (depending on target variable)

Evaluate model performance using metrics like R², MAE, or Accuracy

5. Interpretation & Insights

Summarize statistical test outcomes and regression model findings

Identify major contributing factors influencing accident severity

📊 Expected Outcomes

✅ A cleaned, structured dataset ready for analysis

📈 Statistical summary and visual insights of accident severity factors

🔍 Identification of key variables affecting accident severity

🤖 A regression-based predictive model for estimating severity levels

🧭 Actionable insights to help policymakers and organizations enhance road safety

📚 References

McKinney, W. (2017). Python for Data Analysis. O’Reilly Media

Traffic Accident Datasets:

Global Road Accidents Dataset (Kaggle)

Road Accident Statistics in Bangladesh (Kaggle)

Official Documentation:

NumPy

Pandas

Matplotlib

Seaborn

SciPy

Scikit-learn

🚀 Future Enhancements

Incorporate time-series and geospatial analysis

Compare machine learning models (e.g., Random Forest, XGBoost) for improved accuracy

Integrate real-time traffic data for dynamic prediction
