# ** Alphabet Soup Neural Network Report **

#  Overview
The analysis aims to develop and evaluate three deep learning models for Alphabet Soup, a charitable organization.  Alphabet Soup has requested a predictive model to determine which organizations would have chances of succeeding after receeiving the funding. 
The neural network aggregates several related features per organxzation to attempt to predict the organization's success as binary devision( successful or un-successful)

# Results
## Data Preprocessing

- The following features that were removed from the dataset we 'EIN' and 'NAME' columns as these do not play any role in determining the success or failure of an organization. 

- The following features were converted to numerical values for the analysis. 
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS
- ASK_AMT

- The feature that was converted to binary values is 'IS_SUCCESSFUL' and this is the target variable of the model as it helps in deciding if an organization will be successful (1) or not (0). 

## Compiling, traning and Evalualtion
- The current model consists of two hidden layers. Layer one has  rectified linear unit(relu) and activation with 15 neurons, layer two has relu activation with 20 neurons.
- Traget performace was not achieved 
- The model was trained for 50 epochs and the accuracy was 73.06%
- Additional attempts were made by adding hidden layers and more neurons in order to achieve higher accuracy percentage. 

## Summary  
Overall this analysis involved creating and evaluating a deep learning neural model to predict the success of charitable organizations receiving funding from Alphabet Soup. This model was able to acheive an accuracy of 73.06%. To achieve better accuracy score we can implement foloowing strategies:
- Feature Engineering: Create new features, remove irrelevant features, or transform existing features to better represent the underlying patterns in the data.

- Ensemble Methods: Combine multiple models (e.g., Random Forest, Gradient Boosting) to leverage the strengths of individual models and improve overall performance

- Model Selection: Experiment with different algorithms or ensemble methods to see which one performs best for the specific problem as per the goals and guidelines of Alphabet Soup.



