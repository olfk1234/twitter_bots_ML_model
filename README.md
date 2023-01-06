This project is a categorical machine learning project intended to run different machine learning algorithms on a dataset outlining which accounts are or are not twitter bots and then comparing the accuracy, precision, and recall scores among the models to determine the optimal mode to use.
Steps:
1) The data was cleaned and optimized so that the variables could be used in a machine learning model.
2) The data was scaled, so that the difference in units between the categories could be optimized.
3) Different machine learning methods were called and a grid search was done for each to find the optimal hyperparameters.
4) The accuracy, precision, and recall scores are compared for all utilized models and a confusion matrix is displayed for all models.
5) The optimal model and the scaler is dumped into a joblib file for use on future data. 
