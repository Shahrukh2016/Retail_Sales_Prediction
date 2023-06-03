# Rossman Sales Prediction

This repository contains the code and documentation for the Rossman Sales Prediction project. The goal of this project is to forecast the daily sales of Rossmann stores for up to six weeks in advance. By accurately predicting sales, store managers can make informed decisions regarding promotions, competition, holidays, and other factors that influence sales performance.

## Problem Statement

Rossmann operates over 3,000 drug stores across 7 European countries. Currently, store managers rely on their own predictions for daily sales, leading to varying levels of accuracy. The objective of this project is to develop a machine learning model that can forecast the "Sales" column for the test set. The dataset provided includes historical sales data for 1,115 Rossmann stores, taking into account factors such as promotions, competition, school and state holidays, seasonality, and store locality. It is worth noting that some stores in the dataset were temporarily closed for refurbishment.

## Project Summary

The Rossman Sales Prediction project involved extensive data analysis, feature engineering, and model selection to accurately forecast sales. Here is a brief overview of the project steps and key findings:

1. Data Gathering and Cleaning:
   - Collected historical sales data for Rossmann stores, including competitor details, holidays, customer count, and daily sales.
   - Performed data cleaning to handle missing values and ensure data consistency.
   - Merged relevant datasets to enhance the feature set.

2. Exploratory Data Analysis (EDA):
   - Conducted in-depth EDA by exploring univariate, bivariate, and multivariate relationships.
   - Generated insightful visualizations to uncover patterns and trends in the data.
   - Extracted meaningful insights to inform future decision-making in the machine learning pipeline.

3. Feature Engineering and Preprocessing:
   - Created additional features such as PromoDuration and CompetitionDuration to capture relevant information.
   - Addressed multicollinearity among independent variables using variance inflation factor (VIF) analysis.
   - Detected and treated outliers using the Interquartile Range (IQR) technique.
   - Encoded categorical variables using One-Hot Encoding for compatibility with machine learning algorithms.
   - Applied various transformation techniques to achieve normal distribution of data.

4. Model Selection and Training:
   - Split the preprocessed data into training and testing sets.
   - Utilized a variety of machine learning algorithms, including linear regression, decision trees, random forests, LightGBM, and XGBoost.
   - Evaluated model performance using metrics such as R-squared score, accuracy, and mean absolute percentage error (MAPE).
   - Employed regularization techniques (e.g., Lasso, Ridge, Elastic Net) for improved model performance.
   - Identified XGBoost as the optimal model due to its high accuracy, with an MAPE of only 2% and an R-squared score of 0.94.

5. Model Deployment and Conclusion:
   - Finalized the XGBoost model for deployment, as it demonstrated the highest accuracy and the least error.
   - Developed a comprehensive machine learning pipeline that combines data processing, feature engineering, and model evaluation.
   - Successfully created a model capable of accurately predicting sales for Rossmann stores up to six weeks in advance.

This project showcases the effective utilization of data analysis, feature engineering, and machine learning techniques to solve a real-world forecasting problem. The insights gained from the analysis provide valuable information for decision-making within the retail industry.
*****************************************************************************************************************************************

Feel free to explore the code and documentation provided in this repository to gain a deeper understanding of the project and replicate the results and if you have any questions or suggestions, please don't hesitate to reach out.

You can check out my [BI Portfolio](linktr.ee/shahrukh2016) for more projects, information and social handles.

Happy forecasting!
*****************************************************************************************************************************************
