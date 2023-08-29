# Life Expectancy Prediction Project

This repository contains the code for a data analytics project focused on estimating life expectancies across countries on a global scale. The project utilises data provided by the World Health Organization (WHO) covering the years from 2000 to 2015 and spanning 183 countries. This was a group project with decision made toegther to ensure that we all followed the ethical practices we were tasked with and to ensure we completed our task within the 1 week deadline we had.

## Project Overview

We were given the task by our stakeholder to construct two Life Expectancy prediction models.

* One model was to be a Minimal Information Model: This model utilises the least amount of information necessary to make life expectancy predictions. It aims to provide basic estimates without relying on sensitive data. As a group we had to decide which columns were considered to be sensitive and omit these columns from our minimal (simple) model.

* The second model had to be a Advanced Information Model: This more elaborate model can be used if countries decide to share additional sensitive data. It aims to provide more accurate predictions by leveraging data that we believed to be more sensitive in nature.

* Throughout the project we had to comply with ethical considerations ensuring that we maintained data integrity and privacy throughout the project.

* Another requirement of our task was to make sure we got a RMSE of 5 or under with our detailed model. What RMSE means is the error from our actual value and the one we predicted. In our task we had to get a RMSE of 5 years or under - so this means predicting a countries life expectancy within 5 years.
With our model we were able to get a RMSE of under 3 years.

## Data

The dataset comprises various population statistics and features related to life expectancy for each country. Please note that due to data privacy concerns, some measurements for life expectancy might be missing. Our data analytics team has taken these missing cases into consideration during the analysis.

## Workbooks

The project has been split up into 4 section and thus there are 4 workbooks to reflect that. In order to replicate or to use our workbooks effectively please note the order in which to use them:

1. Data Exploration Through Graphs
2. Feature Engineering
3. Model Tuning
4. Model

The first workbook - Data Exploration Through Graphs was used so that we could identify any patterns or trends throughout our data. We used this workbook to see if there were any null rows or columns and we dealt with those as we saw fit. We visualised our insights through boxplots to see any outliers and see any columns that would need to be scaled. We used heatmaps to visualise the correlations between columns, so we could identify potential columns that would cause multicollinearity.

The second workbook - Feature Engineering is where we started using libraries from SKLearn such as RobustScaler, MaxAbsScaler, PowerTransformer, Normalizer, MinMaxScaler. These were used to scaler our columns. We experimented with multiple scalers so we could see which one was best to use.

The third workbook - Model Tuning is where we implemented a function called Stepwise and VIF in order to see which columns would give us the best results in terms of modelling and not cause any multicollinearity between our target columns and our other features.

The fourth workbook - Model is where we created our target and features for our model using test train split. We also created our simple and detailed models to use.

## Getting Started

To utilize our life expectancy prediction function, follow these steps: 

Clone this repository to your local machine:

git clone https://github.com/AmritBinning/Life_Expectancy_Linear_Regression_Model

Run the appropriate script to access the prediction function.

## Conclusion

Our project aims to provide valuable insights into life expectancies across countries while upholding the principles of ethical data usage and privacy. By developing predictive models and offering transparent documentation, we contribute to better understanding population needs and risk factors.

## Contact

If you have any questions or suggestions related to this project, feel free to contact me at amritbinning14@gmail.com.

Thank you for exploring my Predictive Analysis repository!
