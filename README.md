# Data Science Job Salaries Analysis and Prediction

## Project Overview

This project involves analyzing and predicting data science job salaries based on various features. The dataset contains information on work year, experience level, employment type, job title, salary, and other relevant attributes.

## Purpose

The main purpose of this project is to explore the factors that influence data science job salaries and build a predictive model to estimate salaries based on different variables.

## Project Structure

1. **Data Preprocessing and Cleaning:**
   - Removal of duplicate records for data consistency.
   - Transformation of categorical variables, including changing abbreviations to meaningful names using libraries like `country_converter`.
   - Handling missing values using methods like filling with mode.

2. **Descriptive Statistics and Visualization:**
   - Computation of measures of central tendency (mean, median, mode) and measures of variability (variance, standard deviation) for salary distribution.
   - Skewness analysis to understand the distribution's symmetry.
   - Visualization techniques such as histograms, box plots, violin plots, and line plots to illustrate data characteristics and trends.

3. **Exploratory Data Analysis (EDA):**
   - Exploration of relationships between different features and their impact on salary.
   - Visualizing trends in salary across different dimensions, including experience level, employment type, company size, job type, and more.
   - Identification of interesting patterns, correlations, and insights from visualizations.

4. **Hypothesis Testing:**
   - Utilizing Z-test for hypothesis testing to determine the significance of different salary scenarios.
   - Understanding p-values and their implications on accepting or rejecting null hypotheses.
   - Interpretation of results in the context of salary comparisons.

5. **Modeling and Machine Learning:**
   - Feature transformation and scaling using techniques like `RobustScaler`.
   - Implementation of predictive models, including Linear Regression and Decision Tree Regressor, for salary estimation.
   - Model evaluation using metrics like R-squared score and root mean squared error (RMSE).
   - Selection of the best-performing model based on RMSE and its justification.

6. **Time Series Analysis:**
   - Analysis of salary changes over a three-year period using line plots to identify trends.
   - Interpretation of time-based variations in salaries.

7. **Effective Data Visualization:**
   - Creation of various types of plots (histograms, bar plots, box plots, violin plots, line plots, pie charts) using libraries such as `matplotlib`, `seaborn`, and `plotly.express`.
   - Visualizing complex information in an accessible and understandable manner.

8. **Data Engineering:**
   - Utilization of pipelines for data preprocessing and feature engineering using `sklearn.pipeline`.
   - Conversion of categorical variables into numerical representations using techniques like `OneHotEncoder`.

9. **Communication and Interpretation:**
   - Clear and concise explanations of findings and insights from data analysis and visualization.
   - Interpretation of statistical measures and visualization trends to derive meaningful conclusions about salary patterns.

10. **Model Selection and Interpretability:**
    - Justification for choosing the Linear Regression model as the best performer for salary prediction based on RMSE.
    - Interpretation of model coefficients and their implications on salary predictions.

## Key Insights

- The project begins by cleaning and preparing the dataset, including handling duplicates, missing values, and transforming categorical variables.
- Descriptive statistics and visualizations provide insights into salary distribution, central tendency, variability, and correlations with different features.
- Exploratory Data Analysis (EDA) reveals trends in salary based on experience level, employment type, company size, job type, and location.
- Hypothesis testing helps validate findings and assess statistical significance.
- The project concludes with the selection of the best-performing model (Linear Regression) for predicting salaries.

## Usage

1. Clone the repository to your local machine.
2. Run the provided code to clean the data, perform exploratory analysis, and build predictive models.
3. Modify the code and parameters as needed for your specific analysis.
4. Refer to the generated visualizations and results to understand salary trends and make informed decisions.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- country_converter
- scipy
- sklearn

## Acknowledgments

This project was completed as part of Ammar's data science portfolio. The dataset was sourced from Kaggle [https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries].
