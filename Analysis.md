# Alphabet Soup | Successful Funding Predictor

## Overview
Alphabet Soup, a nonprofit foundation, has asked us to create a process to preditct what applicants will be the most successful.  Alphabet Soup has given us a dataset from the past several years, to allow us to use the informaiton that they have gathered; to work to predict (via neural networks).  The provided data; will help us detemring if a specific industry sector; income classification, requested funding ammount, etc., to see how best to utilize Alphabet Soups dollars. 

## Results 
After pulling in our data set, we took out the identification columns EIN and NAME as they are considered irrelevant information when using machine learning.
- Target Variable: Is-Successful.

### Attempt 1
1st Hidden Layer - 6, Relu for activation
2nd Hidden Layer - 12, Relu for activation
397 trainable params
150 epochs
Loss: 0.54998
Accuracy: 72.96%

******insert graph

### Attempt 2
1st Hidden Layer - 9, Tahn for activation
2nd Hidden Layer - 19, Relu for activation
649 trainable params
75 epochs
Loss: 0.5516
Accuracy: 72.84%

******insert graph

### Attempt 3
1st Hidden Layer - 7, Relu for activation
2nd Hidden Layer - 14, Relu for activation
3rd Hidden Layer - 21, Relu for activation
687 trainable params
100 epochs
Loss: 0.5543
Accuracy: 73.03%

******insert graph

### Attempt 4
Adjusting the Count_Binning to < 200 (the first 3 attempts were utilizing < 100)
1st Hidden Layer - 7, Relu for activation
2nd Hidden Layer - 14, Relu for activation
3rd Hidden Layer - 21
505 trainable params
75 epochs
Loss: 0.5534
Accuracy: 72.96%

******insert graph

### Attempt 5
Keeping the NAME field in the data set
1st Hidden Layer - 7, Relu for activation
2nd Hidden Layer - 14, Relu for activation
3rd Hidden Layer - 21
434 trainable params
75 epochs
Loss: 0.5416
Accuracy: .7312

******insert graph

## Summary
Overall, I was not able to obtain a 75% accuracy rating with any of the models that I was trying. I was close with 73% for many of them. Multiple layers ares still need for deep learning models
as it allows for more accuracy with predciting our information.  As there are many classifiying elements that need to be utilized to predict, it is better to not be a super high-level input with layers. 