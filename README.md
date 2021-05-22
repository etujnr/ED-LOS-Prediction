# ED-LOS-Prediction
Prediction Model for COVID-19 patient ED Length of Stay

Abstract

Study objective: The outbreak of COVID-19 has become a global public health threat. The influx of COVID-19 patients has caused a prolonged emergency department (ED) length of stay (LOS) in the United States. Our objective is to develop a reliable prediction model for COVID-19 patient ED LOS and identify factors associated with LOS within a “4-hour target.” 

Methods: Data were collected from an urban academic hospital in Detroit for all COVID-19 patients’ ED presentations from March 16 to December 31, 2020. Four machine learning models namely logistic regression (LR), gradient boosting (GB), decision tree (DT) and random forest (RF) are trained to predict COVID-19 patients with an ED LOS less or greater than 4 hours. 10-fold cross-validation is employed to evaluate the performance of the models. 

Results: The data on 3,301 COVID-19 patients with known LOS at the ED are used in this analysis. Seventeen significant factors predicting COVID-19 patient ED LOS were physician available, bed available, nurse available, CKD, DM, ESI, type 2 DM, patient race, CAD, CLD, CVD, obesity, AFIB, RR, SpO2, PVD, and HR. The RF model outperforms the DT model and the two baseline classifiers (LR and GB) with a weighted accuracy of 85% and F-1 score of 0.85 for predicting ED LOS in the testing data. No significant accuracy gains are achieved through further splits. 

Conclusion: This study identified key independent factors from a combination of patient demographics, comorbidities, and ED operational data that predicted prolonged COVID-19 patients’ ED stays. The machine learning models can serve as a decision-support tool to improve ED and hospital resource planning and inform patients with better ED LOS estimations.

Models

This Github repository contains the two main Python files used for predicting COVID-19 patient ED LOS:

1. Exploratory data analysis - we look at the descriptive statistics of the data, conduct pre-processing, and visualize the data. See the file named "Exploratory Analysis".
2. Model building - we build the prediction model using different machine learning algorithms such as Gradient Boosting, Random Forest, Decision Tree, and Logistic Regression. See the file named "Model Building"
