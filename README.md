# Exoplanet-Exploration-Analysis

# Report
The two models used were a Neural Net and a Random Forest Classifier. The two models were fed the exact same data set and were split and scaled accordingly. 

# Neural Net
Three neural net models were built in the script. The first model had 3 layers while the second model had 6. After scoring both models using the testing data, model one had a score of .891 while the second model with more layers had a score of .888. After reviewing this, a third model was creating using only the 15 top most important variables. The top 15 variables were chosen based on the feature importance method within the classifier and was built with 7 layers. This tuned third modeled scored a .892. After comparing all the models the best model to use for prediction was the model with 7 layers and used only the top 15 variables in the dataset.

# Random Forest Classifier
Three Random Forest Classifiers were built in the script. The first model was built with all the variables and using the default parameters. The second model was built using all the variables, but using the grid search method, the parameters were changed to maximize the score. After building both models the first model scored a .895 while the second model scored a .891. A third model was build using only the most important features. These features were calculted using the Random Forest Classifier's important feature method. After the most import features were identified only the top 15 most important features were used to train the third model. The third model was also tuned using a grid search to maximize the final score. The third modeled scored the highest with a score of .896. After reviewing all three models the best model to use is the third model.

# Compairng the Neural Net vs Random Forest Classifier
When comparing the top Neural net model and the top Random Forest Classifier model, the Neural net model scored a .892 while the Random Forest Classifier scored a .896. The most accurate model to predict the planet type in this dataset is the Random Forest model becasue it scored slightly higher.

# Interesting points
- Both Neural Net models and Random Forest Classifier models imporoved when limiting variables to the top 15.
- While the Random Forest model scored slightly higher, both models scores were in the range of 88.8% - 89.6% accurate.
