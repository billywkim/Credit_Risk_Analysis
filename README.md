# Credit_Risk_Analysis

## Overview of the Analysis

The purpose of this analysis was to use Machine Learning statistical algorithms to perform tasks such as learning from data patterns and making predictions. Different techniques and models were created to assess their accuracy and precision including RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.

## Results

**Naive Random Oversampling**

![Naive Random Oversampling](https://user-images.githubusercontent.com/88448731/205807513-ad813676-a8c9-4398-a0bd-13640c9480bf.PNG)

From the results, the model accuracy score is 0.657. The precision is low for high-risk loaners with a recall of 0.71 and high precision for low-risk loaners with a recall of 0.60. 

**SMOTE Oversampling**

![SMOTE Oversampling](https://user-images.githubusercontent.com/88448731/205808202-2c042d6f-ab00-42f6-a734-30c0699c4e63.PNG)

The model accuracy score is 0.654. Likewise, the precision for high-risk loaners is low with a recall of 0.61 and the precision for low-risk loaners is high with a recall of 0.69.

**Undersampling**

![Undersampling](https://user-images.githubusercontent.com/88448731/205808557-0ee427f2-f4eb-48aa-92f2-43be76f13f96.PNG)

The model accuracy score is 0.654. The precision for high-risk loaners is low with a recall of 0.69 and the precision for low-risk loaners is high with a recall of 0.40.

**Combination (Over and Under) Sampling**

![Combination Under-Over Sampling](https://user-images.githubusercontent.com/88448731/205808642-e62337f5-3c95-48fa-955f-252602c705f3.PNG)

The model accuracy score is 0.544. The precision for high-risk loaners is low with a recall of 0.72 and the precision for low-risk loaners is high with a recall of 0.58.

**Balanced Random Forest Classifier**

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/88448731/205808830-6cc08bdf-82ae-4e8e-839a-1fccf07df7b7.PNG)

The model accuracy score is 0.788. The precision for high-risk loaners is low with a recall of 0.67 and the precision for low-risk loaners is high with a recall of 0.91.

**Easy Ensemble Classifier**

![Easy Ensemble Classifier](https://user-images.githubusercontent.com/88448731/205808968-022ee66a-c281-462c-b7c1-1b9d57616c38.PNG)

The model accuracy score is 0.925. The precision for high-risk loaners is low with a recall of 0.91 and the precision for low-risk loaners is high with a recall of 0.94.

## Summary

In comparison to all of these tested models, the Easy Ensemble Classifier is the most ideal model to use with an accuracy score of 0.925 whereas the other models were below 0.8. Moreover, this model also has the highest precision and recall score. Moving forward, this model should be used to analyze any credit risk for loaners.
