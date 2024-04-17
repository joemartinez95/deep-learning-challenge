For this analysis, the purpose was to build a neural network model that would estimate whether or not future applicants will be successful.

Results: 
Data Preprocessing
The target model identified was the IS_SUCCESSFUL variable
All other variables in the model were considered features including affiliation, income amount, and ask amount. Name and EID were removed from the dataset as these are not relevant features to include in this model.

Compiling, Training, and Evaluating the Model
 26 Neurons were used as we had 9 different variables in the model to include for the analysis. 3 layers were used and the tanh function was utilzied as well. This was for the purpose of trying to speed up the model and add more interactions for better prediction accuracy. We were not able to achieve the target model performance though steps taken along the way were to progressively add more neurons and layers to the model. 

Summary: Based on the result of the model, there is 73% accuracy to determine whether future applicants will be successful. A different model with more epochs or bins adjusted for identify rare occurrences can be used in order to create a predictive model with at least 75% accuracy. 

