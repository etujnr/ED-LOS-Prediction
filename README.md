# ED-LOS-Prediction
Prediction Model for COVID-19 patient ED Length of Stay

Abstract

Study objective: The outbreak of COVID-19 has become a global public health threat. The influx of COVID-19 patients to the hospital has caused a prolonged emergency department (ED) length of stay (LOS) in the United States. Our objective is to develop a reliable prediction model for COVID-19 patient ED LOS and identify factors associated with a LOS of "4-hour target".

Methods: Data were collected from a community hospital in Detroit for all COVID-19 patients’ ED presentations between March 1 and April 30, 2020. Decision tree (DT) and random forest (RF) models are trained to predict COVID-19 patients with an ED LOS less or greater than 4 hours. 10-fold cross-validation was employed to evaluate the performance of the models. 

Results: The data on 536 COVID-19 patients with known LOS at the ED were used for this analysis. The RF model performance outperforms the DT one with an overall accuracy of 77% (i.e., F-1 score of 0.772 for ED LOS <4hrs and 0.765 for ED LOS >=4hrs). No significant accuracy gains were achieved through further splits. Results illustrate chronic kidney disease, age, oxygen flow, and hypertension as significant factors associated with prolonged COVID-19 patients’ LOS.

Conclusion: We applied machine learning models (i.e., DT and RF) to predict COVID-19 patients’ ED LOS. The models can serve as a decision-support tool to help ED managers and clinicians with hospital resource planning and inform patients with better ED LOS estimations.

Models

This Github repository contains the two main files used for predicting COVID-19 patient ED LOS

Python Files:

1. Exploratory data analysis - we look at the descriptive statistics of the data, conduct pre-processing, and visualize the data. See the file named "Exploratory Analysis".
2. Model building - we build the prediction model using different machine learning algorithms such as Gradient Boosting, Support Vector Machine, and Logistic Regression. See the file named "Model Building"
3. Model Building II - we focus only on Decision trees and hyperparameter tuning. See the file named "Model Building II"
4. Model Building III - we focus only on Random forest and hyperparameter tuning. See the file named "Model Building III"

WEKA Files:

1. Decison tree + hyperparameter tuning (j48)
2. Random forest + hyperparameter tuning

Note: The WEKA software will need to be downloaded to view the code and results on WEKA.
