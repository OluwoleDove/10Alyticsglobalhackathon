# **10AlyticsGlobalHackathon**
This repository contains a data science project aimed at analyzing the factors contributing to high youth mortality rates across various regions. The project focuses on identifying socioeconomic, healthcare, and environmental factors that impact youth mortality, proposing actionable recommendations, and building predictive models to assess risk across populations.

# Table of Contents
Overview
Dependencies
Installation
Data Analysis & Modeling
Correlation Analysis
Visualization
Recommendations
Overview
The project focuses on the following objectives:

Identify socioeconomic, healthcare, and environmental factors contributing to high mortality rates.
Propose actionable recommendations to address gaps in vaccination coverage, healthcare access, and maternal support.
Develop predictive models to identify regions and populations at higher risk of high mortality rates.
Key features of the project include:

Data cleaning and preprocessing of multiple health datasets.
Exploratory Data Analysis (EDA) to identify relationships between factors influencing mortality rates.
Building predictive models (Random Forest, Gradient Boosting) to predict youth mortality.
Visualization of correlations and model performance.

Dependencies
This project requires the following Python libraries:

NUMPY - For numerical operations.
PANDAS - For data manipulation and analysis.
SEABORN - For creating informative and attractive data visualizations.
SKLEARN - For machine learning and model evaluation.
STATSMODEL - For statistical modeling and tests.
Installation
To set up the environment and install the necessary libraries, run the following commands in your terminal or command prompt:

bash
Copy code
pip install numpy
pip install pandas
pip install seaborn
pip install -U scikit-learn scipy matplotlib
pip install statsmodels

Data Analysis & Modeling
The analysis focuses on:

Data Cleaning: Merging and cleaning datasets related to youth mortality, vaccination coverage, healthcare access, and socioeconomic data.
Predictive Modeling: Using machine learning models like Random Forest and Gradient Boosting Regressor to predict youth mortality rates based on relevant features.
Grid Search Optimization: Tuning model parameters using GridSearchCV to find the best model performance.
Correlation Analysis
This section investigates the relationships between vaccination coverage (e.g., BCG and DTP3 rates), healthcare access, and youth mortality rates. The correlation is explored using heatmaps, where the dataset is merged to compute the correlation between relevant features.

Visualization
The project includes visualizations to display the findings, such as:

Correlation Heatmaps: Showing the relationships between vaccination rates, healthcare access, and youth mortality.
Performance Metrics: Visualizing the performance of machine learning models like Random Forest and Gradient Boosting, using metrics like Mean Absolute Error (MAE) and R² Score.

Recommendations
Based on the analysis, the following actionable recommendations are proposed:

Increase Vaccination Coverage: Focus on regions with low vaccination rates (e.g., BCG, DTP3) to improve health outcomes.
Improve Healthcare Access: Enhance access to skilled healthcare staff and health insurance coverage to reduce mortality rates.
Enhance Maternal Health Support: Invest in maternal health programs to lower both maternal and infant mortality, which directly impacts youth mortality