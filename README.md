# STLF_IRISH_RESIDENCES
Short Term Load Forecasting of Load consumption data from Irish Residences using Polynomial Regression and Machine learning techniques

For this study we have executed all the 4 models and obtained the MAPE scores
given in the model results benchmark table.The polynomial regression being simple model which has
the least complexity of parameters as well as it is lighter on the system to run. This
model helps us achieve our goal of comparing the linear models with non-linear
models. These experiments establish the fact that linear models although being the
simpler and less complex ones are not an optimal option for short term load
forecasting of our smart energy meter dataset. Random forest algorithm is also a non-
linear model which we have implemented as a simple machine learning model which
gives us a better result than the polynomial regression but the deep learning model we
have used which are LSTM and LSTM-stacked which gives us better results than the
random forest ensemble of regression trees. The MAPE scores of LSTM and Multi-
stacked LSTM are close to each other with the simpler version giving better score,
reason being it Is simple in terms of complexity and as well it takes less time to
execute with hyper parameter optimization algorithm. The LSTM-multi stacked gives
a slightly higher MAPE with a difference of 0.14777. In theory Multi-stacked LSTM
should give better results although in this case we have limited number of computing
resources and time to train the model. If we execute the model tuning more
hyperparameters we are bound to achieve best results with the multi stacked LSTM
however, LSTM multi stacked is too complex and computation intensive which does
not fit in our goal to establish a model which is less computation intensive and
accurate. From the perspective of establishing a model with low complexity yet
providing a accurate result we come to a conclusion that the Single stacked LSTM is a
better model for predicting short term load forecast.
