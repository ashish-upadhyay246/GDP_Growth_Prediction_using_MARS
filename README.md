This is a machine learning project to predict the growth of GDP of a country (here India) in Billion USD.
The algorithm of Multivariate Adaptive Regression Splines has been used to make a continuous graph for accurate predictions.
R2 score on testing data is approx 99.12% and for training data is 99.34%.
==================================================================================================================================
Linear Regression showed a large amount of residual and was not fitting the dataset well.
Decision tree and random forest algos gave the extreme values as output if out of range values were given as input.
Polynomial regression was not used as it did not perform well on sharp corners of the dataset.

Hence MARS algorithm was used to fit the data. The Earth() class from the PyEarth library was used to achieve this.
==================================================================================================================================
The dataset used contains the GDP for the years 1960 through 2021 i.e. 62 years. 
Which is not enough to efficiently train the model but with larger dataset it can perform better.
