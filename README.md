# deep-learning-challenge

# Overview 
## The purpose of this analysis is to create a tool to help the organization, Alphabet Soup, select applicants for funding depending on those with the best chance of success in their ventures.

# Results 

## Data Preprocessing

###	What variable(s) are the target(s) for your model? Loan Risk 
###	What variable(s) are the features for your model? Income, credit score, loan amount. 
###	What variable(s) should be removed from the input data because they are neither targets nor features? The EIN and the name as they are irrelevant. 

## Compiling, Training, and Evaluating the Model

###	How many neurons, layers, and activation functions did you select for your neural network model, and why? You'll see above in the markdown comments for each attempt how many nuerons, layers and epochs used for each attempt. I tried to keep a balance in the number of layers and epochs so as to capture intricate relationships but not to overfit. 
###	Were you able to achieve the target model performance? I was able to achieve a 73% accuracy score, not 75%.
###	What steps did you take in your attempts to increase model performance? I adjusted the model 3 times. The first two times I adjusted the number of hidden layers and epochs to run for to see if it would adjust the accuracy score. It did not fluctuate much. On my third attempt, I tried a different approach with a Random Forest algorithim, as opposed to Logistic Regression. This proved to be less effective for this type of model with a 2% decrease in accuracy. 

# Summary 
## In summary, the logistic regression model proves to be better suited for this assignment. I believe a higher accuracy score can be achieved by continuing to adjust the optimizer learning rates and using different types of optimizers. 
## In the current state of the model, it would not be effective enough to use to accurately classify whether applicants will be successful or not in their ventures.

# Instructions to Final Work 
## Located in the "deep-learning-challenge_code.ipynb" in the "deep-learning-challenge_docs" folder. 

Thank you! 
