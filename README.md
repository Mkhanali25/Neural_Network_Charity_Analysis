# Neural_Network_Charity_Analysis
## Overview
In this analysis we were tasked with creating a nueral network to predict where our clients should make investments. We were given a csv file containing our data which we had to convert into a binary classifier. The binary classifier would then help us predict which applicants would be succesful if funded by Alphabet Soup. 
## Results
Once we recieved our data we had to comb through it and remove some variables so that we can reduce clutter and get a better predicition from our model
* For my model I chose to target IS_SUCCESSFUL
  * This variable shows us if the money was used effectively
* The variables that're considered our feature variables were INCOME_AMT, CLASSIFICATION, and ASK_AMT
* The variables that are clutter are EIN, NAME, and ORGANIZATION
* This model used 2 hidden layers
  * The activation functions that were used were RELU and SIGMOID
  * The amount of neurons were 20 and 10 for each hidden layer
* I was not able to achieve the target model performance
* I tried removing some variables, adding a hidden layer, and including more neurons

## Summary
Overall the neural network didn't preform as we had expected but it was a good learning experience. There were many things that could've been changed to achieve the results that we had required. In the end the best accuracy and loss was from the original model
