Overview of the Analysis
The purpose of this analysis is to create a binary classifier using a neural network to predict whether applicants will be successful if funded by Alphabet Soup.

Results
Data Preprocessing
Target Variable: IS_SUCCESSFUL
Feature Variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
Removed Variables: EIN, NAME
Compiling, Training, and Evaluating the Model
Neurons, Layers, and Activation Functions: Initially, the model had two hidden layers with 80 and 30 neurons using ReLU activation functions and one output layer using sigmoid activation.
Model Performance: Initial model accuracy was below the target of 75%.
Optimization Attempts:
Increased neurons and added hidden layers.
Experimented with different activation functions.
Adjusted epochs and batch sizes.
Summary
The optimized models showed very little if any improvement. I was not able to sucessfully optimize the model to above 75% accuracy.
