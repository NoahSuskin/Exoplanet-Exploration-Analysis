# Exoplanet-Exploration-Analysis

# Report
The two models used were a Neural Net and a Random Forest Classifier. The two models were fed the exact same data set and were split and scaled accordingly. 

- Neural Net
Three neural net models were built in the script. The first model had 3 layers while the second model had 6. After scoring both models using the testing data, model one had a score of .8804 while the second model with more layers had a score of .8953. After reviewing this a third model was creating using only the 15 top most important variables. The top 15 variables were chosen based on the feature importance method within the classifier. This tuned third modeled scored a .8884, which is lower than the model using all the features. After comparing all the models the best model to use for prediction was the model with 7 layers and used all the variables in the dataset.
