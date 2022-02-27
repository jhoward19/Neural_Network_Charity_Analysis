# Neural_Network_Charity_Analysis
# Overview of the analysis 

The purpose of the analysis to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. In order to accomplish this task knowledge from machine learning and neural network will be used. 

# The Results
1.  Data Preprocessing 
* The variable that was considered the target for the model was IS_SUCCESSFUL column.
* The variables that were considered the features of the model were the following column: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
*	The variables that were neither targets nor features and were removed was EIN and NAME column because they were identification that had no impact on the output

2.	Compiling, Training, and Evaluating 
*	In the neural network model for the Alphabet Soup Charity and Optimization segment two hidden layers, 80 and 30 neurons, ReLu activation function was used for the hidden layers and sigmoid was used for the output layer.  segment These were used to speed up the training process. 
*	The target model performance was around 73% which not sufficient to predict the outcome. 
*	In order to increase the model performance, bucketing technique was used on ASK_AMT feature, increased the number of neurons, and used a neural network model with three hidden layers, in addition used a different activation function. 

# Summary 

In conclusion, after preprocessing the data, compiling, and training it the model performance did not meet a sufficient score to predict the outcome. Even after trying different steps like bucketing, increasing the neurons and hidden layers, and trying a different activation function the model continue to not perform better. A different model like a Balanced Random Forest Classifier or Easy Ensemble Classifier could probably help solve this classification problem by combining multiple models like decision tree algorithms to help improve the accuracy and decrease the variance of the model.

