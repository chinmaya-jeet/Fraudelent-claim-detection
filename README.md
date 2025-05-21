# Fraudelent-claim-detection
> The objective is to build a model to classify insurance claims as either fraudulent or legitimate based on historical claim details and customer profiles. By using features such as claim amounts, customer profiles, claim types and approval times, the company aims to predict the claims that are likely to be fraudulent before they are approved.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This Project contains Presentation for the summary, recommendations and business implications based on the analysis. It also contains a report which include the overall approach of the assignment, covering the problem statement, methodology, techniques used and key insights.

## Conclusions
- Model performance is relatively good with ~87% accuracy in identifying legitimate claims
- Top predictors:
	- Incident_severity and total_claim_amount highly predictive of the fraud.
	- Features like policy_annual_premium, days_between_policy_and_incident, and incident_hour_of_the_day also 	show strong importance in the Random Forest model.
- Class imbalance was found in the target variable (65% to 35% distribution of No fraud and Fraud respectively). - 	Addressing the class imbalance issue with resampling significantly improved the model.
- Hyper-tuning in Random Forest helped to improve the sensitivity and F1 scores in the model.
- Implement strategic actions such as update of fraud detection policies and improving data collection methods.
- Threshold tuning can allow better control over false positives and false negatives.
- Model should be monitored regularly to understand the changes in pattern and accordingly update the model.
- Train staff on fraud indicators, share identified patterns and improve documentation practices.


## Technologies Used
Python 3.11, Jupyter Notebook , Pandas, Matplotlib, Seaborn, train_test_split, RandomOverSampler, MinMaxScaler, RFECV,LogisticRegression, StratifiedKFold, statsmodels.api, variance_inflation_factor, metrics, roc_auc_score, confusion_matrix, precision_recall_curve, RandomForestClassifier, classification_report, cross_val_score, GridSearchCV, 


## Acknowledgements
Give credit here.
- This project was inspired by upgrad ...
- References if any...

## Contact
Created by Chinmayajeet and Chaitanya - feel free to contact me!
