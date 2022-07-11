# Data Science Salaries

## Dataset description and Inspiration

> The dataset is a 12 feature data set that consists of over 600 columns. The features present in the dataset include but not limited 
to company location, employee residence, salary, remote ratio, e.t.c.
This dataset was obtained form kaggle and I was inspired by it after completing my udacity course and learning machine learning.

> This project contains an EDA notebook and a Machine Learning notebook that uses a decision tree regressor to predict the salary of a particular job title given some certain other features.

## Wrangling and EDA
> during WRangling and EDA, a number of issues were addressed including the changing the data type of some features and removing particular outliers.
> In the end, the summary of the findings are listed in the notebook, with cogent information about what affects the salary of a datascientist
> At first, it seemed as if the salaries of data scientist increase with increasing year. 
In order to properly evaluate this, we decided to hold the experience level constant (Only used senior level),
and we discovered that the year did not actually have much to do with the increasing salaries.

> We discovered that with the increasing year, there seem to be more Senior level or higher roles ratio than 2020.
We also discovered that the two highest paid salaries jobb actually do not have entry levels. So they
are roles only attached to higher levels and came into play after 2020.

## Machine Learning
> Since most of the features we are dealing with are object variables, I decided to go with a decision tree that and an ordinal
encoder.
> We identified Feature Importance and we discovered that location of a company actually plays a vital role in the split
that the decision tree made.
