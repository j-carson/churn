# Churn analysis example

## Need for study

This study was done for a challenge from my Metis alumni study group.
Customer churn (customers leaving a service) is a basic task for data scientists in the business world. 

## Data

The data is from (Kaggle)[https://www.kaggle.com/blastchar/telco-customer-churn], and includes 21 features to predict "churn" or "no churn." Approximately 7000 customer
records are included.

## Methods used

- Cohort analysis: Dividing customers into groups based on starting service at a similar time
- Unbalanced classes: Random oversampling of the minority class
- Logistic regression
- Random forest
- Train-test split, cross-validation

## Results

For each of four cohorts, accuracy scores were in the range of 70 to 80 percent. The area under the ROC curve
was in the range of .75 to .91. 

