This is a machine learning project to predict the growth of GDP of a country (here India) in Billion USD.
The algorithm of Multivariate Adaptive Regression Splines has been used to make a continuous graph for accurate predictions.
R2 score on testing data is approx 99.12% and for training data is 99.34%.
Hinge function is used to fit our data to the model. The data available on the internet was fot eh years 1960-2021 i.e. 62 years, 
rate of growth of GDP before 2001 was very gradual but it witnessed a sudden increase in the rate.
Linear regression showed a large amount of residual error hence it was not fit to train the mdoel, random forest and decision trees gave 
extreme values of the dataset when out of range input was given. Hence, MARS was chosen for the data fitting.
