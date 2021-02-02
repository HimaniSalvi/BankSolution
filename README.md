# BankSolution

To predict if the client will subscribe to term deposit.

This is a classification problem
First we clean the data, check for null values or missing values, replace them.
We have done univariate analysis, Bivariate analysis.
Then we looked for corelation between variables

Then we built our model,
we checked for AUC score for different models as to see which model fitted the best.
We tried Logistic Regression Model, 
we will look for Decison Tree Model to check whether we get better accuracy, similarly we check for Random Forrest Classifier , XGBoost model, Gradient Boosting model.

So there is this feature wise ranking which will be of importance while finding the score
This choses best features that affect the score and we can find the AUC score based on those features and exclude the less important feautres or parameters.

So after selecting best features the ROC AUC score has improvised.
FOr RandomForest is now 0.93
For Grid Search - 0.91
For XGBClassifier- 0.94

Hence if the score is not satisfactory you can chose the best festures in the dataset and again fit them in the model to get a better score.
Thus more or less 0.94 i.e 94% accuracy has been achieved.
