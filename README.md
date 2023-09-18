# Car-Stopping-Analysis
An in-depth exploration of the relationship between car speed and stopping distance, leveraging Python's data analysis libraries. This project showcases proficiency in linear regression modeling, data transformation, diagnostic testing, and assumption validation, all while offering insights for real-world policy-making.

Overview

This repository delves deep into the relationship between a car's speed and its required stopping distance, using advanced statistical methodologies and Python's powerful data analysis toolkit.

Technical Skills Showcased

Data Handling with Pandas: Imported and manipulated the StoppingDistance.txt dataset to ensure optimal readiness for analysis.
Visualization with Matplotlib & Seaborn: Crafted insightful scatterplots, histograms, and residual plots to visualize relationships and diagnose model assumptions.
Statistical Modeling with Statsmodels: Employed Ordinary Least Squares (OLS) regression to understand and predict stopping distances based on car speed. Validated model assumptions through diagnostic plots.
Advanced Data Diagnostics: Used techniques like DFBETAS and DFFITS to detect and address influential points, ensuring the robustness of the model.
Data Transformation: Recognized and addressed heteroscedasticity and non-linearity in the dataset to improve model fit and predictions.

Dataset

The StoppingDistance.txt dataset provides a comprehensive view of the distance (in feet) required for a car to halt on a specific rural road against the car's speed (in MPH).

Key Technical Findings:

Preliminary scatterplots and regression modeling indicated a positive correlation between speed and stopping distance.
Diagnostic plots highlighted potential violations of the linear regression assumptions.
Addressed heteroscedasticity and non-linearity through data transformations, enhancing the predictive accuracy of the model.
Post-transformation, diagnostic tools confirmed the adherence of the model to its assumptions, ensuring reliable and robust results.
