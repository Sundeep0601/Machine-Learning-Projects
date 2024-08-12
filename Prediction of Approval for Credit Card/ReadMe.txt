Introduction

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, we will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do!
I am using the Credit Card Approval dataset from the UCI Machine Learning Repository.

Steps Involved 

Step 1: Firstly, loading and viewing the dataset. We find that since this data is confidential, the contributor of the dataset has anonymized the feature names.

Step2: Inspecting the applications

Step3: Handling the missing values

Step4: Then after replace all the question marks with NaNs. This is going to help us in the next missing value treatment that we are going to perform.

Step5: I have done to impute these missing values with the most frequent values as present in the respective columns. This is good practice when it comes to imputing missing values for categorical data in general.

Step6: Preprocessing the data, it includes 2 sub steps, 
                                                        i) Converting the non-numeric data into numeric.
                                                       ii) Scale the feature values to a uniform range.

Step7: Splitting the dataset into train and test sets.

Step8: Fitting a logistic regression model to the train set. It is used because it has ability to provide clear, interpretable, and probabilistic predictions makes it a popular choice.

Step9: Making predictions and evaluating performance.

Step10: Grid searching and making the model perform better. 

Step11: Finding the best performing model.

Finally, my model was pretty good! It was able to yield an accuracy score of almost 85%.

Feel free to contact if there any errors or changes to sundeep0601@gmail.com