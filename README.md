
# Home Credit - Default Risk Classification 
https://www.kaggle.com/c/home-credit-default-risk/overview

### Goal  
   - Predict if a bank should accept or reject a loan application of an individual (binary classification)
   - Achieve an acceptable AUC score (0.75+).
   - Perform threshold optimization. 


### Overview:  
   - Will perform manual feature engineering
   - Will evaluate different algorithms using AUC score
   - Will use LGBM for the classification
   - Will perform parameter tuning using RandomSearch
 
### Notebook Structure :
    
 - Exploratory data analysis
 - Handle Missing Values
 - Handle Categorical Features
 - Evaluate algorithms  
    - LGBM
    - Tree
    - Random Forest
   - Feature importance
 - Threshold optimization （G-MEAN)
 
### Learning Material: 
 
#### @Will Koehrsen: https://www.kaggle.com/willkoehrsen/home-credit-default-risk-feature-tools
- Learned a lot about EDA and feature engineering from his notebook.

#### @Misha Lisovyi: https://www.kaggle.com/mlisovyi/lightgbm-hyperparameter-optimisation-lb-0-761
- The hyperparameter tuning skills are learned from here. Good tutorial.

#### @Jason Brownlee: https://machinelearningmastery.com/threshold-moving-for-imbalanced-classification/
- Great article about parameter tuning for imbalanced classification.

#### Note: Some of the codes here are learned from the aboving three notebooks.
