# Heart Attack Data Science Project

## Data analysis part

In the data analusis part we are going to explore the given heart attack dataset and try to find some useful information for the classification modeling task. First, we are just going check if the data is clean and does not have any missing values in the rows. If there appears to be missing data in the rows, then we are going to drop those rows, because they are just going to add noise to the dataset and make classification harder. Then we are going to check how much variance there are between features and try to analyze from that some of the important features. After that we are going to just explore different feature distributions and look for outliers which might give some information for the classification modeling. Then we are trying to find some correlations between some features, which might help us in the classification part.

## Classification part

In the classification part we are going to use XGBoost Classifier for our classification and HyperOpt's Optimizer for hyperparameter tuning. First we are going to split data into training and testing data and scale the features. After that we are going to test the base model performance. After that we are going to do some feature engineering and see if we can improve the base model performance with it. When we have completed the feature engineering we start optimizing the model with HyperOpt's optimizer by fine tuning hyperparameters.

© Sami Anttalainen
