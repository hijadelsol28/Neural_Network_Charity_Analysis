# Neural_Network_Charity_Analysis

## Overview
The purpose of this assignment is to effectively use machine learning analysis, specifically neural networks, to create a binary classifier that is capable of predicting whether or not applicants funded by the charitable organization “Alphabet Soup” will be successful. This project used a dataset containing measures on 34,000 organizations that have previously been funded by Alphabet Soup.

## Results
### Data Pre-Processing
•	The target model is the “Is-Successful” column, representing funds used effectively.
•	The features of the model are all columns other than the “Is-Successful” model.
•	The Variables that were neither targets or features for the datasets were the EIN and NAME columns, which were removed from the dataset in this analysis.

### Compiling, Training, and Evaluating the Model
•	For the neural network model, there were three hidden layers. The first with 100 nodes, the second with 50 nodes, and the third with 20 nodes. The first two layers were relu activation, the third and outer layer were sigmoid, which I believed fit better.
