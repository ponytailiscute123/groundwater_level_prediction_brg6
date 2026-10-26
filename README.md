# Groundwater Level Prediction Using Machine Learning
A self-directed machine learning project exploring groundwater-level prediction using historical monitoring data from the BRG6 peatland site in Indonesia.
# Project Overview
Groundwater-level monitoring is important for understanding hydrological changes and supporting water-resource management. This project explores the use of time-series data and machine learning techniques to estimate subsequent groundwater levels.
The project compares a Linear Regression model with a Naive Baseline to investigate their predictive performance.
# Objectives
1. Explore historical groundwater-level monitoring data.
2. Develop features from previous groundwater-level observations.
3. Apply time-based validation to time-series modelling.
4. Compare Linear Regression predictions with a simple baseline.
5. Visualize actual and predicted groundwater levels.
# Dataset
1. Monitoring site: BRG6, Indonesian peatland
2. Data type: Historical groundwater-level observations
3. Valid records: 545, as identified during the notebook analysis
The dataset is used for an educational and analytical project. Please refer to the original data source and its usage conditions before redistributing the data.
# Tools & Technologies
1. Python
2. Pandas
3. Scikit-learn
4. Matplotlib
5. Jupyter Notebook
# Methodology
1. Exploratory data analysis
2. Time-series visualization
3. Lag-feature engineering using previous observations
4. Time-based validation
5. Linear Regression modelling
6. Comparison with a Naive Baseline
7. Visualization of actual and predicted groundwater levels
# Results
The models were evaluated using time-based validation and a final test set to compare their performance in predicting groundwater levels at the BRG6 monitoring site. During time-based validation, Linear Regression achieved a mean absolute error (MAE) of 0.0212 m, compared with 0.0216 m for the Naive Baseline. However, the Naive Baseline achieved slightly lower RMSE and a higher average R².
On the final test set, the Naive Baseline outperformed Linear Regression, achieving an MAE of 0.0161 m, an RMSE of 0.0282 m, and an R² of 0.9857. Linear Regression achieved an MAE of 0.0204 m, an RMSE of 0.0309 m, and an R² of 0.9828. These results demonstrate that a simple baseline can perform competitively with a machine learning model for this dataset. Further evaluation is needed to determine how well these findings generalize to other monitoring periods and locations.
# Limitations
1. The analysis focuses on a single monitoring site.
2. Predictive performance may vary under different hydrological conditions.
3. Further evaluation is required before applying the approach to operational groundwater forecasting.
4. The prediction horizon should be explicitly confirmed from the notebook before interpreting the results as daily or multi-day forecasts.
# Applications
This project demonstrates an introductory workflow for applying data analysis and machine learning to groundwater monitoring, with potential relevance to hydrogeology, environmental data analysis, and water-resource management.

# Author
Haya Nidaan Khofyya

Geological Engineering | Hydrogeology & Environmental Data Analysis
