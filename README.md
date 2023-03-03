# Deep-Learning-Challenge | Module 21

Alphabet Soup wants me to create a tool to help select the est applicant for funding successful ventures. Utilizing machine learning and neural networds, we are to create a binary classifer to predict what applicants will be successful if funded by our nonprofit. 

### Applications Utilized
- Pandas
- Scikit-Learn 
    - Standard Scaler
    - Train Test Split
    - Transform
- TensorFlow

## Step 1 | Preprocess the Data
Load in our charity_data.csv and identidy the target and feature sof the models.  Dropping the unneeded EIN and NAME columns.  Determining how manu unique values are in each column. Working with the data points, picking the correct 'rare' category variables; and then the other. Adjust columns to ensure categorical variables can be used.  Split the date via train_test_split; and then scale the data via the StandardScaler and then transform functionality

## Step 2 | Compile, Train, and Evaluate the Model
Utiling TensorFlow; I will create a neural network to model the sucess based on the fatuers in my data set. 
Creating a hidden layer; output layers.  After confirming the structure of the model, we will compile and train our data, checking the weight every 5 epochs. 2Evaluating the data to determine the loss and accuracy of the model. Saved our finding into a new file AlphabetSoupCharity.

## Step 3 | Optimize the Model
Optiming our model to achiever a target of accuarcy greater than 75%. Do capture that accuracy value, I may adjust the columns, add addtional bins for those 'rare' occurancies, or increaing/decreaing the number of values in each bin. We can adjust the number of hidden layers or activation functions.  Possible additional adjumsents can be made to the number od epochs utilized in the training regimen. Saving our findings in to the AlpahbetSoupCharity_Optimization file. 

## Step 4 | Write a Report on the Neural Network model

