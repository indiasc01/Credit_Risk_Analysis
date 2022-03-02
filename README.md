# Credit_Risk_Analysis

## Analysis
In this challenge, looked at different types of machine learning models to predict credit risk. Looking at the different types of models, we are able to determine which model is better to predict credit risk.

## Results

RandomOverSampler Model
-The RandomOverSampler model, the balanced accuracy score is 65%
-With a high number of the low_risk population, it's precision is almost 100% with a sensitivity of 55%.

SMOTE Oversampling Model
-The balanced accuracy score is 66%
-With a high number of the low_risk population, it's precision is almost 100% with a sensitivity of 69%

ClusterCentroids Model
-The balanced accuracy is lower compared to the previous two models with a score of 54%
-With a high number of false positives, the low_risk sensitivity is at 42%

SMOTEEN Model
-The balanced accuracy score is 64%
-With the high number of false positives, the low_risk sensitivity is at 58%

BalancedRandomForestClassifier Model
-The balanced accuracy score increased compared to the other models with a score of almost 79%
-With a lower number of false positives, the low_risk sensitivity is 87% with a 100% precision

EasyEnsembleClassifier Model
-Out of all the models, this model is the highest with a balanced accuracy score of 93%
-With a low number false positives, the low_risk sensitivity is 94% with a 100% precision

## Summary
After going through all the models, the results showed that if the credit risk is high, the precision will be low. The ensemble models had higher improvement on high risk credit, especially the EasyEnsembleClassifier model. With a low precision, some of the low risk credits were falsely detected as high risk. With a lot of false positives for credit risk, I would not recommend using any of these models.
