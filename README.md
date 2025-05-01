# IT salaries in Armenia

# Overview
The project involves analyzing monthly salary data in AMD (after paying the taxes) of tech professionals in Armenia to uncover patterns and trends. It combines multiple domains of Machine Learning (NLP, Dimensionality Reduction, Clustering, Regression) to deliver a comprehensive solution. At the end, a model is trained to effectively predict salaries and gain insights.

# Goal
The primary goal is to provide insights into salary distributions and factors affecting salaries in the Armenian tech industry.

# Techniques Used
Feature Engineering: Extracting valuable features from diverse text data that comes in different shapes.

Clustering: Utilizing DBSCAN to dynamically convert text data (company names and job title names) to numerical input for ML models. 

Statistical Analysis: Methods to analyze and summarize the data.

Machine Learning Models: An ensemble of Ridge Regression, Linear Support Vector Machines, and Gradient Boosting Regressor (scikit-learn's Ridge, LinearSVR, GradientBoostingRegressor respectively) to combine the strengths of diverse algorithms.

# Results
The model achieves a R-Squared score of 0.66 and Root Mean Squared Error of 0.65 when trained on the whole dataset (the salaries and predictions are converted to logarithms).

# License
[Open Data Commons Attribution License (ODC-By) v1](https://opendatacommons.org/licenses/by/1-0/)
