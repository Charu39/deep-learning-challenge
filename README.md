# deep-learning-challenge

**# Background**
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures.
The foundation has provided you with a dataset of historical funding data for organizations that have received funding in past. Using the dataset create a machine learning model that can predict whether an organization receiving funding from Alphabet Soup will be successful or not.

**# Instructions**

# Step 1: Preprocess the Data
Create a dataframe containing the charity_data.csv data , and identify the target and feature variables in the dataset 
Drop the EIN and NAME columns 
Determine the number of unique values in each column
For columns with more than 10 unique values, determine the number of data points for each unique value
Create a new value called Other that contains rare categorical variables
Create a feature array, X, and a target array, y by using the preprocessed data 
Split the preprocessed data into training and testing datasets
Scale the data by using a StandardScaler that has been fitted to the training data

# Step 2: Compile, Train, and Evaluate the Model
Compile, Train and Evaluate the Model 
Create a neural network model with a defined number of input features and nodes for each layer
Create hidden layers and an output layer with appropriate activation functions 
Check the structure of the model 
Compile and train the model 
Evaluate the model using the test data to determine the loss and accuracy 
Export your results to an HDF5 file named AlphabetSoupCharity.h5

# Step 3: Optimize the Model
Repeat the preprocessing steps in a new Jupyter notebook 
Create a new neural network model, implementing at least 3 model optimization methods 
Save and export your results to an HDF5 file named AlphabetSoupCharity_Optimization.h5 

# Step 4: Write a Report on the Neural Network Model (30 points)
Write an analysis that includes a title and multiple sections, labeled with headers and subheaders 
Format images in the report so that they display correction 
Explain the purpose of the analysis
Answer all 6 questions in the results section 
Summarize the overall results of your model 
Describe how you could use a different model to solve the same problem, and explain why you would use that model

