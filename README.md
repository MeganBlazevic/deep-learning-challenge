# Deep-Learning-Challenge | Module 21

Alphabet Soup wants me to create a tool to help select the best applicant for funding successful ventures. Utilizing machine learning and neural networds, we are to create a binary classifer to predict what applicants will be successful if funded by our nonprofit. 

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
Creating hidden layer(s); output layers.  After confirming the structure of the model, we will compile and train our data, checking the weight every 5 epochs. Evaluating the data to determine the loss and accuracy of the model. Saved our finding into a new file AlphabetSoupCharity.

## Step 3 | Optimize the Model
Optiming our model to achiever a target of accuarcy greater than 75%. Do capture that accuracy value, I may adjust the columns, add additional bins for those 'rare' occurancies, or increaing/decreaing the number of values in each bin. We can adjust the number of hidden layers or activation functions.  Possible additional adjumsents can be made to the number of epochs utilized in the training regimen. Saving our findings in to the AlpahbetSoupCharity_Optimization file. 

I have tried several adjustments to obtain the 75% threshold with out success. On the 5th adjustment; Collab started to fail, with the RAM spikes. I have been unable to 'wait' for the system to clear to try my 5th adjustment. 

## Step 4 | Write a Report on the Neural Network model
We have been asked to write an analysis with multiple sessions with headers and subheader; with an overview analysise and sharing the results.
We should be answering the following 6 questions.

Data Processing
- What variable(s) are the target(s) for you model?
- What variable(s) are the features for your model?
- What variable(s) shoudl be removed from the input data because they are neither features or targets?

Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Were you able to achieve the target model performance?
- What steps did you take in an attempt to increase model performance?

My Outcomes
Despite much trial and effort, I was unable to produce a model that had an accuracy rating of 75% of greater.  Each of the attempts, had minor tweeks, and when working through the intial compile and training, I had made some initial adjustment and attempts that did not have any significant changes in the outcomes of the modeling. 
