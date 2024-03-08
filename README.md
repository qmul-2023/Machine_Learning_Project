# Mercedes Benz Greener Manufacturing

In this project a Machine Learning algorithm is developed to predict the time a car will spend on the test bench based on vehicle configuration. The intention is that an accurate model will be able to reduce the total time spent testing vehicles by allowing cars with similar testing configurations to be run successfully. This is an example of a machine learning regression and supervised learning task since, it requires predicting a continuous target variable (the duration of test) based on the model of the car [X1-X9].

The dataset and other details can be downloaded from kaggle website: https://www.kaggle.com/c/mercedes-benz-greener-manufacturing

## DESCRIPTION

Reduce the time a Mercedes-Benz spends on the test bench.

Following actions should be performed:
* If for any column(s), the variance is equal to zero, then you need to remove those variable(s).
* Check for null and unique values for test and train sets
* Apply label encoder.
* Perform dimensionality reduction.
* Predict your test_df values using xgboost
