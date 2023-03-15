# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The analysis completed this challenge took two machine learning models and fed them existing parameters for loans given out. The loans were deemed either healthy loans or high risk loans. This is supervised machine learning because the dependent variables are known and the models are measured against the actuals. The financial information the data was on were the size of the loan amount, the interest rate at which loan was given, the borrower's income, the debt to income ratio for the borrower, the number of accounts the borrower has, the number of derogatory_marks, and overall total_debt held by the borrower. The variable I'm trying to predict is whether the loan status is '0' or '1'. The '0' represents a healthy loan status and the '1' represents a high-risk loan.

The stages I undertook for the machine learning process was to read in the data to be used, separating out the dependent variable(the variable we are trying to predict) and creating a new dataframe with the left over table. Next is to  instantiate the instance of the model to use and splitting the data into test data. After that we fit the model we defined on onto our test data. From there we predict the y_test data that we have to check and see if our model is accurate. We calculated the balanced accuracy score to provide a score of how the model performed. We also generated a confusion matrix as well as a classification report. Once that is completed we review the findings.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

  *Accuracy:
  *Precision: 99%
  *Recall:  95%
  *F-1 Score: 99%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
  *Accuracy: 99%
  *Precision: 99%
  *Recall: for both healthy and high risk loans were 99%
  *F-1 Score: 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
    * The model that performed the best was the oversampler model. This is known because the accuracy count is higher than that of the previous Logistics Represenation.
    * Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) 
    * Yes performance will change depending on the problem that's being solved. Predicting the unhealthy loans may require looking at multi-nomial parameters.

If you do not recommend any of the models, please justify your reasoning. 
    *I would recommend investing in the oversampler model as that provide more accurate results.
