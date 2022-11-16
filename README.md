# VideoGameSalesDataAnalysis
This repository will show the process of predicting the global sales for different video games released since 1970.
This will be done by utilizing different regression models with varying amounts of features
then comparing their results. We will identify key features of a video game that are associated with global
sales and explain how these features impact the sales of the video game. After cleaning the data and using
imputation to add missing features four models that will be created to predict global sales. The model that
will used are Regression Trees, Random Forests, Elastic Net, and Least Squares Linear Regression. The best model will
be Least Squares Linear Regression with a test root mean square error of 0.62 and 6 features. This means
for the model the predictions were off by 620,000 sales. The worst model is the regression tree which gets
a score of 2.03, so a random forest is used instead. The random forest has a test root mean square error
of 1.84 then lastly Elastic Net has 1.94. The features for all four models that lead to the highest predicted
global sales were the publisher Nintendo and games that had a higher critic and user score. The features
that lead to a lower predicted global sales were the year the game was released.
