# deep-learning-challenge
Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively




Model Report

Purpose:
Predict the accuracy in classifcation to find whether applicants will be successful if funded by Alphabet Soup.


Data Preprocessing

What variable(s) are the target(s) for your model?
 'IS_SUCCESSFUL' column
What variable(s) are the features for your model?
all the other columns
What variable(s) should be removed from the input data because they are neither targets nor features?
EIN and Name columns

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
8 layers
Were you able to achieve the target model performance?
No
What steps did you take in your attempts to increase model performance?
adding more layers and removing columns


Summarize and recommendation:
Overall, the deep learning model was around 70% accurate in predicting the problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. Data clean up would be reccomended.
