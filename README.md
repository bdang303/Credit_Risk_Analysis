# Credit_Risk_Analysis
ML


## Overview of the analysis 

This analysis utilizes various machine learning algorithms & models to predict the credit risk of applicants. As we run the dataset and its features through each of the models, we’ll be able to assess the accuracy score as well as metrics via classification reports to determine which method & model is most appropriate. The models used include: 

- Oversampling
- Under sampling
- SMOTE Oversampling
- Combination of Oversampling & Under sampling

In addition, we’ll run the data through two ensemble models using: 

- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

## Results

### Naïve Random Oversampling

The first model used was a random oversampling model

- This model resulted in a balanced accuracy score of ~65%
- Predicted High Risk Applicants: With 1% precision, & 69% recall 
- Predicted Low Risk Applicants: With 100% precision, & 61% recall 

![Model 1 Accuracy Score]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M1AS.png)

![Model 1 Classification Report]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M1CR.png)

### Under sampling

The second model used was a SMOTE oversampling model

- This model resulted in a balanced accuracy score of ~66%
- Predicted High Risk Applicants: With 1% precision, & 63% recall 
- Predicted Low Risk Applicants: With 100% precision, & 69% recall 

![Model 2 Accuracy Score]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M2AS.png)

![Model 2 Classification Report]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M2CR.png)


### Under Sampling

The third model used was an under-sampling model

- This model resulted in a balanced accuracy score of ~54%
- Predicted High Risk Applicants: With 1% precision, & 69% recall 
- Predicted Low Risk Applicants: With 100% precision, & 40% recall 

![Model 3 Accuracy Score]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M3AS.png)

![Model 3 Classification Report]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M3CR.png)


### Over/Under Sampling

The fourth model used a combination of over & under sampling

- This model resulted in a balanced accuracy score of ~55%
- Predicted High Risk Applicants: With 1% precision, & 69% recall 
- Predicted Low Risk Applicants: With 100% precision, & 40% recall 

![Model 4 Accuracy Score]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M4AS.png)

![Model 4 Classification Report]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M4CR.png)


### Balance Random Forest Classifier

The fifth model used the Balance Random Forest Classifier algorithm

- This model resulted in a balanced accuracy score of ~79%
- Predicted High Risk Applicants: With 3% precision, & 70% recall 
- Predicted Low Risk Applicants: With 100% precision, & 87% recall 

![Model 5 Accuracy Score]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M5As.png)

![Model 5 Classification Report]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M5CR.png)


### Easy Ensemble AdaBoost Classifier

The last model used the Easy Ensemble AdaBoost Classifier
algorithm

- This model resulted in a balanced accuracy score of ~93%
- Predicted High Risk Applicants: With 9% precision, & 92% recall 
- Predicted Low Risk Applicants: With 100% precision, & 94% recall 

![Model 6 Accuracy Score]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M6AS.png)

![Model 6 Classification Report]( https://github.com/bdang303/Credit_Risk_Analysis/blob/main/images/M6CR.png)




## Summary

All of these models predict high risk candidates extremely poorly, however the if the intent is to determine which applicants are low risk and therefore eligible to be approved for credit, then the Easy Ensemble AdaBoost Classifier algorithm may be the best bet given its accuracy score.
