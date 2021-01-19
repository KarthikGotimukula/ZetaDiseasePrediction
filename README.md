# ZetaDiseasePrediction

======== Files ======================

Dataset : 2021-01-04_zeta-disease_dsi-take-home-challenge.csv

Instructions: 2021-01-04_zeta-disease_dsi-take-home-challenge.md

Python Code : CarrierTakeHomeTest.ipynb

======== Problem Statement ==========

Task : predict who will be infected by Zeta Disease.

======== Solution ===================

Step1: Read the 2021-01-04_zeta-disease_dsi-take-home-challenge.csv.

Step2: Here we used XGBoost to train and get high/better accuracy of our model.

Step3: Once the model is trained, we used that model to predict the test dataset.

======== Notes ===================

I've trained the dataset using Random Forest classifier as well using GridSearchCV (hyperparameter tuning).
The accuracy is slightly better, however since this is a disease classification dataset, the Type 2 error is more important in 
such cases. 
I've observed that the Type 2 error in RandomForest classifier is more than that of the XGBoost classifier 
and so, I chose XGBoost classifier over Random Forest classifier. 

Also, since the original dataset is not very large, we cannot expect high accuracy with the models.

========Thank You======================
