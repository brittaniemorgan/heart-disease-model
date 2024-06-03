# Heart Disease Prediction Model
## Overview
This dataset contains demographic and health data relating to patients such as age, sex, type chest pain, cholesterol, heart rate and other health factors. It then uses this data to predict if the patient has heart disease. It is preprocessed and evaluated to determine which factors to pass on to the model. This type of work is relevant in health care to highlight the most important symptoms of heart disease and providing early diagnosis.

## Explorative Analysis
This includes perfroming descriptive statisics to obtain information such as the mean and standard deviation of numerical values. It also includes generating a correlation matrix which shows the relationship between each numerical column. Bar plots where used to show the distribution and relationship between categorical values.

## Hypothesis Testing
The information from the explorative analysis was used to perform hypothesis testing to verify any conclusions made. These tests were carried out useing t-means tests for numerical values and chisquare tests for categorical values.

## Data Preprocessing
This includes checking for empty columns, replacing empty values with the median where possible, removing irrelevant columns and encoding. The remaining values are standardised split into train and test.

## Model Training and Selection
The result from preprocessing was used to train three models, a Support Vector Machine, Logistic Regression and Random Forest. Their accuracy, precision, recall and f1-score were evaulted and the Support Vector Machine was chosen as it the best metrics with an accuracy of 84.8%.
