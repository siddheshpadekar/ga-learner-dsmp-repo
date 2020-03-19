### Project Overview

 To predict the Insurance claim using logistic regression. This dataset contains information on the insurance claim. each observation is different policy-holder with various features like the age of the person, the gender of the policyholder, body mass index, providing an understanding of the body, number of children of the policyholder, smoking state of the policyholder and individual medical costs billed by health insurance.


### Learnings from the project

 I learnt how to build a Basic logistic Regression model. How to evaluate the metrics of a model by using and plotting ROC_AUC scores.


### Approach taken to solve the problem

 The data was loaded and checked for outliers however the outliers were essential to remain in the data set as more probability that outliers on Age will contribute more to the prediction.
After that I performed correlation check to view which features are highly correlated with the other feature and help us predict its better logistic regression model.
I applied the Logistic Regression Model and calculated the accuracy which comes to be 0.82 using GridSearchCV for prediction of insuranceclaim.


