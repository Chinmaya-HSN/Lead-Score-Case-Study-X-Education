# X Education Lead Scoring Model

This repository contains the implementation of a lead scoring model for X Education, an online education company. The goal of this project is to identify potential leads that are most likely to convert into paying customers, thereby improving the lead conversion rate.

## Problem Statement
X Education is facing challenges with its lead conversion rate. Although they receive a significant number of leads, their conversion rate is poor. To address this issue, the company aims to identify the most promising leads, referred to as 'Hot Leads', by assigning a lead score to each lead. This lead score will help prioritize leads with higher conversion potential, leading to a more efficient sales process.

## Approach
The lead scoring model is developed using machine learning techniques on a dataset containing past leads' attributes and conversion outcomes. The target variable is 'Converted', indicating whether a lead was converted or not.

The steps involved in the project are as follows:

1. Exploratory Data Analysis:
   - Cleaning and Proning the Data to identify important categories and numerical variables
   - Replacing Null Values
   - Graphical observations of data to retain orop columns and grouping category levels where needed.
     
1. **Data Preprocessing**: 
   - Handling missing values, particularly the 'Select' level in categorical variables.
   - Exploring the dataset and understanding the distribution of features.

2. **Feature Engineering**:
   - Selecting relevant features that contribute to lead conversion.
   - Encoding categorical variables and scaling numerical features if necessary.

3. **Model Building**:
   - Training various machine learning models such as logistic regression.
   - Evaluating model performance using appropriate metrics like accuracy, precision, sensitivity, and specificity.
   - Tuning hyperparameters to optimize model performance.
   - Model Diagnosis Using Probability Calibration, ROC AUC Curve, Precision-Recall Curve

4. **Lead Scoring**:
   - Assigning lead scores based on the probability of conversion predicted by the model. 

5. **Deployment**:
   - Integrating the lead scoring model into X Education's sales process.
   - Providing recommendations on lead prioritization and communication strategies.

## Files Description
- `X_Education_Lead_Scoring.ipynb`: Jupyter Notebook containing the code for data preprocessing, feature engineering, model building, and lead scoring.
- `data/Leads.csv.csv`: CSV file containing the dataset with past leads' attributes and conversion outcomes.
- `data/Leads Data Dictionary.xlsx`: Excel file providing a data dictionary explaining the attributes in the dataset.

## Getting Started
To run the lead scoring model:
1. Clone this repository to your local machine.
2
. Open and run the `X_Education_Lead_Scoring.ipynb` notebook in a Python environment.

## Dependencies
- Python 3.x
- Jupyter Notebook
- scikit-learn
- statsmodels
- matplotlib
- seaborn
- pandas
- numpy

## Acknowledgments
This project is part of a case study provided by [Upgrad & IIITB college](https://www.upgrad.com/) for educational purposes.

## Group of Authors
Chinmaya Prasad B D - LinkedIn Profile: (https://www.linkedin.com/in/chinmaya-prasad-b-d-71721371/)
Kajal Vidhate       - LinkedIn Profile: (https://www.linkedin.com/in/kajal-vidhate-a6513b279/)

Feel free to reach out for any questions or suggestions!
