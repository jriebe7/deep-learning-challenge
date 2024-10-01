# deep-learning-challenge

## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this anaylis is to look at data provided which contains more than 34,000 organizations that have received funding from Alphabet Soup over the years and to determine if a binary classifier is a viable option that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results:

## Data Preprocessing:

What variable(s) are the target(s) for your model? 
-The target variable for the model is the "IS_SUCCESSFUL" column.
What variable(s) are the features for your model?
-The features for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
What variable(s) should be removed from the input data because they are neither targets nor features?
-The EIN and NAME columns should be removed as they are merely identifiers and do not have any significance for the anayalis.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
