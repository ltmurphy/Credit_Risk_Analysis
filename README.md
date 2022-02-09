# Credit_Risk_Analysis

## Overview of Credit_Risk_Analysis
### Purpose
___

### Credit risk classification can be tricky. With good loans far outnumbering bad loans, the classification is inherently unbalanced. To combat this many different techniques are employed to train and evaluate models with unbalanced classes. The libraries imbalanced-learn and scikit-learn are used to build and evaluate models using resampling.Oversampling,undersampling, a combination of the two, and two new models will be introduced. 
### Technologies used:
  * RandomOverSampler algorithm
  * SMOTE algorithm
  * Undersampling using ClusterCentroids algorithm
  * Overunder using SMOTEEN algorithm
  * BalancedRandomForestClassifier model
  * EasyEnsembleClassifier model

## Credit_Risk_Analysis Results
___
### Below is a list of images showing the code for the different models and the results each one yields.
### Naive Random Oversampling

![Oversampling1](https://user-images.githubusercontent.com/89947873/153102368-0d7e6bbc-77d9-4fb9-a16f-3ad83fe0e0c2.png)

![Oversampling2](https://user-images.githubusercontent.com/89947873/153102378-84bb8051-7e33-41d1-b3b6-c148e49285af.png)

![Oversampling3](https://user-images.githubusercontent.com/89947873/153102383-6e196e8f-211c-4c5b-875c-1b8a38a04a42.png)

![Oversampling4](https://user-images.githubusercontent.com/89947873/153102389-35a94c74-150e-48a7-a1e2-b3974f1b7e50.png)

### SMOTE Oversampling

![SMOTEOversample1](https://user-images.githubusercontent.com/89947873/153103002-beab3fb3-18d5-4640-926a-5392a8ffe305.png)

![SMOTEOversample2](https://user-images.githubusercontent.com/89947873/153103009-9df26fb3-afa4-4414-9a5e-db7cd5e90810.png)

![SMOTEOversample3](https://user-images.githubusercontent.com/89947873/153103016-848c23e7-60d2-46bf-a48c-2bfa72e67a7c.png)

![SMOTEOversample4](https://user-images.githubusercontent.com/89947873/153103030-cab6e60d-4637-4d48-b112-e65d63e7ff9d.png)

### Under Sampling

![Undersampling1](https://user-images.githubusercontent.com/89947873/153103514-02c8ee70-691e-40c3-a306-5a90472f7358.png)

![Undersampling2](https://user-images.githubusercontent.com/89947873/153103524-9247f080-ddd3-4222-89c5-d3de9d7992fe.png)

![Undersampling3](https://user-images.githubusercontent.com/89947873/153103531-a7b9d39d-b972-41cf-ab52-4e77d6d3b866.png)

![Undersampling4](https://user-images.githubusercontent.com/89947873/153103539-0e1624db-a0cc-4556-b4ee-7bf102e0abd8.png)

### SMOTEEN Sampling

![SMOTEEN1](https://user-images.githubusercontent.com/89947873/153103866-d47f253d-d894-42b5-b6fc-6d2631fb62bc.png)

![SMOTEEN2](https://user-images.githubusercontent.com/89947873/153103873-d8be7a3c-5d7d-444d-8b31-7a16ac54d4f2.png)

![SMOTEEN3](https://user-images.githubusercontent.com/89947873/153103878-367e43c9-86ba-46d9-9768-68a842cb9a1a.png)

![SMOTEEN4](https://user-images.githubusercontent.com/89947873/153103882-31c20520-cd44-4832-a700-0908fb182429.png)

### Balanced Random Forest Classifier

![BalancedRandomForestClassifier1](https://user-images.githubusercontent.com/89947873/153104247-77b6e98f-4ac0-4473-8cdd-ce5ed14a9e64.png)

![BalancedRandomForestClassifiers2](https://user-images.githubusercontent.com/89947873/153104261-c84123e1-fcda-4e7c-a9d8-416a9f1f2da9.png)

![BalancedRandomForestClassifier3](https://user-images.githubusercontent.com/89947873/153104266-547bc974-0810-4a0c-ad63-5e9809dcad2a.png)

### Easy Ensemble AdaBoost Classifier
####There was an unknown internal error with the Easy Ensemble module. After much troubleshooting it appears to be a lack of support for older technology in the new update. However, even regressing to Easy Ensemble's earliest iteration still does not rectify the problem. Below is an image of what the model would potentially look like.
![EasyEnsemble1](https://user-images.githubusercontent.com/89947873/153303778-bd57608a-30af-47a1-8b59-7bf4a67905c2.png)

### Scores 
 * Naive Random Samping: Balanced accuracy(65%), precision(1%), recall(62%)
 * SMOTE Oversampling: Balanced accuracy(64%), precision(1%), recall(63%)
 * Undersampling: Balanced accuracy(52%), precision(1%), recall(60%)
 * SMOTEEN Sampling: Balanced accuracy(62%), precision(1%), recall(68%)
 * Balanced Random Forest Classifier: Balanced accuracy(80%), precision(4%), recall(70%)
 * Easy Ensembl Analysis Summary: Balanced(94%), precision(7%), recall(90%)

## Credit_Risk_Analysis Summary
### In depth investigation supports the above image and its results. The Easy Ensemble model presents the best accuracy with 94%. The next closest it the Balanced Random Forest model with 80%. Over, under, and combination sampling produced nothing over 65%. Another helpful statistic is the precision ratings. Easy Ensemble again has the highest at 7%. While this may seem like a clear indicator other models might provide higher numbers. These ratings combined point at Easy Ensemble as the best choice for model.
