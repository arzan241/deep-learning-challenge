# deep-learning-challenge

# Overview of the analysis:
 
The purpose of the analysis to determine the probability of success or success rate of various applicants with their ventures. Our job is to create a machine learning model that helps us predict that. 

# Data processing and Results: 

We have used the CSV file which contains info for over 34,000 organisations that has received funding over the years. 

Features
•	APPLICATION_TYPE: Alphabet Soup application type
•	AFFILIATION: Affiliated sector of industry
•	CLASSIFICATION: Government organization classification
•	USE_CASE: Use case for funding
•	ORGANIZATION: Organization type
•	STATUS: Active status
•	INCOME_AMT: Income classification
•	SPECIAL_CONSIDERATIONS: Special considerations for application
•	ASK_AMT: Funding amount requested

Target
•	IS_SUCCESSFUL: Was the money used effectively

Extra
•	EIN and NAME: Identification columns

The data was separated into X and y based on features and target designations. With the split function if was then split into testing and training datasets. 

# Optimization model A 
We used the ReLu activation function and added 2 additional hidden layers – total 4 and increased the number of neurons per layer. With 50 epochs the summary indicated 2,361 total trainable parameters and improved the accuracy to 72.8% while reducing the loss to 58%

# Optimization model B
We used TanH and ReLu activation function along with total 6 hidden layers and a greater number of neurons per layer. With 200 epochs the summary indicted 3,583 total trainable parameters – the accuracy was higher in comparison to modal A (73.1%) but the loss was higher too (55.6%)

# Optimization model C
This time a total of 5 hidden layers were used along with the Relu activation function and multiple neurons tested at 200 epochs. With a total trainable parameter of 3,457 the model failed to achieve an improved result – with accuracy at 72.9% and loss at 56.9% 

# Summary: 
Upon comparing the 3 optimization models, Model B achieved the highest accuracy with comparatively low loss percentage. Even after improving the model (B) significantly, the outcomes we not very different from the original model. We were not able to achieve the target to 75% accuracy given the nature of the dataset. Model B outcomes indicate that a more sophisticated and robust model can perform better to a certain extent.
