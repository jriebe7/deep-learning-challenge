# deep-learning-challenge

## Overview of the analysis: Explain the purpose of this analysis.
The purpose of this anaylis is to look at data provided which contains more than 34,000 organizations that have received funding from Alphabet Soup over the years and to determine if a binary classifier is a viable option that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results:
After running multiple variants of the model, the final version I ran was able to predict with ~73% accurracy

![App Screenshot](https://github.com/jriebe7/deep-learning-challenge/blob/main/model_final.JPG)
![App Screenshot](https://github.com/jriebe7/deep-learning-challenge/blob/main/model_accuracy.JPG)

## Data Preprocessing:

### What variable(s) are the target(s) for your model? 
- The target variable for the model is the "IS_SUCCESSFUL" column.
### What variable(s) are the features for your model?
- The features for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
### What variable(s) should be removed from the input data because they are neither targets nor features?
- The EIN and NAME columns should be removed as they are merely identifiers and do not have any significance for the anayalis.

### Compiling, Training, and Evaluating the Model

I tried multiple versions with my models, initially starting with 2 hidden layers, which was able to predict ~72% accurracy.  I then played around with adding more layers, few and more epochs, more neurons and layers, and consistently received similar results, and in the end I was not able to break the 75% threshold.
