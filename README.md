# Demand-Forecasting-using-Linear-Regression
Problem Statement:

In this project, the task is to build a multiple linear regression model to predict the demand for shared bikes, with a requirement to submit the solution in a Jupyter notebook.

Background:

BoomBikes, a US bike-sharing provider, faced significant revenue declines due to the ongoing pandemic. To revive their business post-lockdown, they aim to understand the post-quarantine demand for shared bikes. They've gathered a dataset based on various factors, including weather and people's habits, to analyze the factors influencing bike demand in the American market.

Business Goal:

The goal is to model the demand for shared bikes using available independent variables. This model will help the management understand how demand varies with different features, enabling them to adapt their business strategy post-lockdown. Additionally, the model will provide insights into the demand dynamics of this new market.

Data Preparation:

Certain variables in the dataset, like 'weathersit' and 'season', are numeric but represent categorical values. These need to be converted into categorical strings.

Model Building:

The dataset includes columns like 'casual', 'registered', and 'cnt', representing different types of users and total bike rentals. The target variable is 'cnt', indicating the total number of bike rentals. The model will be built considering 'cnt' as the target variable.

Model Evaluation:

After building the model and conducting residual analysis, the R-squared score on the test set needs to be calculated. This step is crucial as it holds marks for evaluation. The R-squared score should be computed 
