
# Seoul Bike Sharing Demand Prediction 

## Project Description
Rental bikes have been introduced in many urban cities to enhance mobility comfort. It is crucial to make rental bikes available and accessible to the public at the right time to reduce waiting time. Hence, predicting the bike count required at each hour is essential for a stable supply of rental bikes in the city.

The Seoul Bike Sharing Demand Prediction project aims to predict the demand for shared bikes in Seoul based on various features, including temperature, rainfall, season, and snowfall. The project involves the following five key stages:

Defining the problem

Data processing

Exploratory Data Analysis (EDA)

Modeling

Evaluation and deployment

## Data Processing
After understanding the data, the project involved cleaning and preparing the data for modeling. We wrangled the data and engineered new features, such as creating columns for month and weekdays to gain a better understanding of how different factors influence bike rentals in Seoul.

We also performed one-hot encoding to convert categorical variables to a more predictable format and checked for multicollinearity to avoid redundancy in the model. 

## EDA
The EDA stage helped to identify relationships between the dependent variable, 'Rental Bike Count,' and independent variables such as temperature, rainfall, and functioning day. The team discovered that rented bikes are less used in winters than in summers, and functioning day is a crucial factor in determining the number of bikes rented.

We also identified that some columns contained outliers that could affect the models' performance. Therefore, took steps to address the issue by removing the outliers.

## Modeling
We split the dataset into training and testing sets and applied multiple linear regression, ridge regression, lasso regression, elastic net, decision tree,  random forest, XG boost and Light GBM to develop models. We used R2 score as evaluation metrics.

## Evaluation and Deployment
The results showed that the Light GBM model outperformed other models, with the highest R2 score. 

## Conclusion
The Seoul Bike Sharing Demand Prediction project demonstrates best practices in data science projects, including understanding the problem and data, applying data processing techniques, performing EDA, evaluating and selecting models, and ensuring transparency and interpretability. The project's success shows the importance of data-driven decision-making in enhancing mobility comfort in urban cities.
