# A Machine Learning and Statistical Approach to predict COVID-19 Global Patterns for Epidemiological Insights

## Abstract

The COVID-19 pandemic has reshaped global public health strategies, emphasizing the need for data-driven insights to guide interventions. Traditional epidemiological models struggle to adapt to the complex, nonlinear dynamics of a rapidly evolving pandemic. 
This study uses the Our World in Data COVID-19 dataset to explore disease patterns using statistical analysis, feature engineering, and machine learning. We construct a comprehensive pipeline from data cleaning and exploratory analysis to predictive modeling and 
clustering to uncover critical indicators influencing case and death rates globally. Using classification and regression models, we identify key predictors of high case burden and total mortality. We further group countries using unsupervised learning to reveal 
structural epidemiological clusters. Our results highlight socioeconomic and demographic factors shaping national outcomes, offering new directions for targeted policy interventions and real-time pandemic monitoring.

## Research Objectives

1. To perform a thorough exploratory data analysis of global COVID-19 trends and assess the quality of the dataset.
2. To identify the most influential features affecting infection and mortality rates using statistical correlation and hypothesis testing.
3. To build machine learning models that predict high case rates and total deaths based on country-specific characteristics.
4. To cluster countries using unsupervised learning techniques to uncover epidemiological patterns and groupings.
5. To develop an interpretable, end-to-end pipeline that supports real-time, evidence-based decision-making in pandemic response.

## Datasets

The primary dataset originates from Our World in Data, encompassing COVID-19 case counts, deaths, testing rates, vaccination data, GDP, healthcare capacity, and population demographics across 200+ countries and territories. 
The data spans from the beginning of the pandemic through multiple waves, including:

Cumulative and daily cases/deaths
Vaccination metrics
Healthcare system indicators
Economic and population statistics

After preprocessing, engineered features include:

1. 7-day rolling averages
2. Case fatality rates
3. Cases/deaths per million
4. Lagged variables
5. Categorized severity labels (e.g., high vs. low case rates)

This rich, high-dimensional dataset enables multivariate analysis and robust modeling of pandemic dynamics at a global scale.
