# Credit_Risk_Analysis
I have been tasked by Jill to utilize machine learning to assess and predict credit risk.  I have used 6 different machine learning methods in order to determine which method would be best used in predicting credit risk.

# RESULTS

## Over Sampling

![OversamplingResults](https://user-images.githubusercontent.com/38074766/149702832-ea9de88c-62a9-4b0c-b0d9-f69471900213.png)

### Balanced Accuracy Score: 63%

The high risk precison rate was at 1%, with a recall of 63% and an F1 score of 2%.

The low risk precision rate was at 100%, with a recall of 64% and an F1 score of 78%


## SMOTE

![SmoteennResults](https://user-images.githubusercontent.com/38074766/149702840-921673aa-5fd1-4131-8f52-241282285de6.png)

### Balanced Accuracy Score: 62%

The high risk precision rate was at 1%, with a recall of 59%, and an F1 score of 2%

The low risk precision rate was at 100%, with a recall of 65%, and an F1 score of 79%

## UNDERSAMPLING

![UndersamplingResults](https://user-images.githubusercontent.com/38074766/149702850-8aded302-4f90-40b4-85aa-d578aef2f5d0.png)

### Balanced Accuracy Score: 52%

The high risk precision reate was at 1%, with a recall of 60%, and an F1 score of 1%

The low risk precision rate was at 100%, with a recall of 45%, and an F1 score of 62%

## COMBINATION SAMPLING

![CombinationSamplingResults](https://user-images.githubusercontent.com/38074766/149702865-27e3f7af-9f21-4b18-b2b8-1252e3d5770e.png)

### Balanced Accuracy Score: 61%

The high risk precision rate was at 1%, with a recall of 62%, and an F1 score of 2%

The low risk precision rate was at 100%, with a recall of 60%, and an F1 score of 75%

## BALANCED RANDOM FOREST CLASSIFIER

![BalancedrandomforestclassifierResults](https://user-images.githubusercontent.com/38074766/149702871-1c78d5cf-f713-41a0-8c0e-c3595eac52dc.png)

### Balanced Accuracy Score: 81%

The high risk precision rate was at 3%, with a recall of 71%, and an F1 score of 7%

The low risk precision rate was at 100%, with a recall of 60%, and an F1 score of 75%

## EASY ENSEMBLE CLASSIFIER

![EasyensembleclassifierResults](https://user-images.githubusercontent.com/38074766/149702875-770487cf-c40e-4f36-a86c-d977f9e21c45.png)

### Balanced Accuracy Score: 93%

The high risk precision rate was at 8%, with a recall of 91%, and an F1 score of 14%

The low risk precision rate was at 100%, with a recall of 94%, and an F1 score of 97%

---------------------------

Out of all the models, the easy ensemble classifier was the best one.  It yielded the highest percentage, as well as a much higher precision rate for the high risk category.  In additon, it yieleded a 92% in the recall for high risk, as well as 94% recall in the low risk category. In conclusion, the model that we must use is the Easy ensemble classifier model.
