# Retail-Sales
Capstone Regression\
This is a capstone project on Retail Sales Prediction.\
Project name - Retail Sales Prediction\
Type- Regression\
Contribution - Team\
Team member 1 - Uttam Mishra\
Team member 2 - Kshitij Singh

# Problem Statement
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

# Project Summary -

The project is on Rossmann a company which operates thousands of drug stores in a few countries. Since they are a multinational company they try to predict their daily sales in advance. We were given two datasets namely - 'Rossmann stores data.csv' and 'store.csv' data. both of these datasets contained multiple rows and columns.

these datasets contained the data about various factor that have influenced the sales of the organisation over the past few years. with this historical data we were given a task to predict the sales for upcoming weeks, keeping in mind the fact that many of the stores were closed for refurbishment.

We started with checking the info of the dataset about the variables that are present in both the dataset and found that store column was same in both the datasets which could be used to merge the dataset for ease of work after merging the dataset we did the data wrangling by cleaning the data set of null and missing values and changing the incorrect data types which were present in it and also corrected the format of date and time to make It analysis ready.

After data wrangling we did exploratory data analysis on the dataset to find out how the various factors influence the sales of the company. We used multiple kind of charts including but not limited to bar graph, pie plot, count plot etc. EDA helped us understand which factors influence the sales.

We also did a correlation check between the variables using correlation heatmap and pairplot.

After eda we did hypothesis testing to check whether certain hypothesis are true or not which we encountered during the exploratory data analysis. In total we checked three statements. then we moved towards algorithm testing for which we had to again do some transformation on the dataset as well as introduction of new features in this process we did outlier detection, data transformation, categorical encoding, feature engineering, data splitting and data scaling. These procedures helped make data ready for model implementation.

For machine learning model implementation we chose to check with three models, first we started with the most basic model linear regression, we did the train test split with the model and predicted the output with it and then did a metrics evaluation and found the values for MSE, MAE, RMSE, RMSPE, R2, Adjusted r2 . after obtaining these results we did a visualisation for the model evaluation which showed the comparison between actual and predicted values using lineplot. After this we also did testing using Lasso and Ridge regression as well as we did a cross validation and hyperparameter tuning using GridSearchCV.

Then we moved to the second algorithm which was DecisionTree Regression we again did all the similar operations as we did on Linear Regression and plotted a lineplot for performance evaluation.

The third algorithm we used was RandomForest Regression. Similar to previous two models we did the same procedure with Random Forest Regressor as well.

After the analysis we found that the RandomForest Regression model was the best performing model among the three.
