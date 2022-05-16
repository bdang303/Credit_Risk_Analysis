# Credit_Risk_Analysis
ML


## Overview of the analysis: Explain the purpose of this analysis.

This analysis utilizes various machine learning algorithms & models to predict the credit risk of applicants. As we run the dataset and its features through each of the models, we’ll be able to assess the accuracy score as well as metrics via classification reports to determine which method & model is most appropriate. The models used include: 

- Oversampling
- Under sampling
- SMOTE Oversampling
- Combination of Oversampling & Under sampling

In addition, we’ll run the data through two ensemble models using: 

- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Naïve Random Oversampling

The first model used was a random oversampling model

- This model resulted in a balanced accuracy score of ~65%
- Predicted High Risk Applicants: With 1% precision, & 69% recall 
- Predicted Low Risk Applicants: With 100% precision, & 61% recall 

![Model 1 Accuracy Score](URL)

![Model 1 Classification Report](URL)

### Undersampling

The second model used was a SMOTE oversampling model

- This model resulted in a balanced accuracy score of ~66%
- Predicted High Risk Applicants: With 1% precision, & 63% recall 
- Predicted Low Risk Applicants: With 100% precision, & 69% recall 

![Model 2 Accuracy Score](URL)

![Model 2 Classification Report](URL)





### Under Sampling

The third model used was an under-sampling model

- This model resulted in a balanced accuracy score of ~54%
- Predicted High Risk Applicants: With 1% precision, & 69% recall 
- Predicted Low Risk Applicants: With 100% precision, & 40% recall 

![Model 3 Accuracy Score](URL)

![Model 3 Classification Report](URL)


### Over/Under Sampling

The fourth model used a combination of over & under sampling

- This model resulted in a balanced accuracy score of ~55%
- Predicted High Risk Applicants: With 1% precision, & 69% recall 
- Predicted Low Risk Applicants: With 100% precision, & 40% recall 

![Model 4 Accuracy Score](URL)

![Model 4 Classification Report](URL)


### Balance Random Forest Classifier

The fifth model used the Balance Random Forest Classifier algorithm

- This model resulted in a balanced accuracy score of ~79%
- Predicted High Risk Applicants: With 3% precision, & 70% recall 
- Predicted Low Risk Applicants: With 100% precision, & 87% recall 

![Model 5 Accuracy Score](URL)

![Model 5 Classification Report](URL)


### Easy Ensemble AdaBoost Classifier

The last model used the Easy Ensemble AdaBoost Classifier
algorithm

- This model resulted in a balanced accuracy score of ~93%
- Predicted High Risk Applicants: With 9% precision, & 92% recall 
- Predicted Low Risk Applicants: With 100% precision, & 94% recall 

![Model 6 Accuracy Score](URL)

![Model 6 Classification Report](URL)




## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

All of these models predict high risk candidates extremely poorly, however the if the intent is to determine which applicants are low risk and therefore eligible to be approved for credit, then the Easy Ensemble AdaBoost Classifier algorithm may be the best bet given its accuracy score.
