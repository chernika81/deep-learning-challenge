# Deep Learning challenge

### The purpose of this analysis is to find a tool that can help the nonprofit foundation Alphabet Soup select the applicants for funding with the best chance of success in their ventures. With our knowledge of machine learning and neural networks, I’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

### From Alphabet Soup’s business team, I have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Data Preprocessing

### . The target variable is the 'IS_SUCCESSFUL' column from application_df
### . The feature variables are the rest of the columns of the application_df except "NAME" and "EIN", which we dropped in the beginning of the preprocessing. "IS_SUCCESSFUL" not included, because it is the target variable.
### . "EIN" and "NAME" columns were dropped from the application_df, because they are neither target nor feature variables. 

## Compiling, Training, and Evaluating the Model

### For the original analysis I used 80 nodes for the first layer and 30 nodes for the second layer according to the sample result that we had in the starter file. This gave an accuracy of 73%. For the additional analysis I added a third and fourth hidden layers and used less neurons for each layer than in the original analysis, but wasn't able to achieve 75% accuracy. All of the additional attempts gave a lower accuracy than the first trial. 

## Summary

### The overall accuracy of this model was around 73% in predicting the classification problem. Additional up front data cleanup could be helpful in achieving a higher accuracy. 
