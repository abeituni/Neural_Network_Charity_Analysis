# Neural_Network_Charity_Analysis

## Overview
In this project, we were tasked with creating a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup. To solve this task, we used deep learning neural network models to optimize our model.

## Results
- Data Preprocessing
    - The main variable considered the target array for our model was the column "IS_SUCCESSFUL".
    - "APPLICATION_TYPE" & "CLASSIFICATION" columns were two variable features in our model.
    - We removed "EIN" & "NAME" columns because they weren't necessary for our input data.

- Compiling, Training & Evaluating the Model
    - For this neural network model, we went with the Tensor Flow Keras model. In our most successful attempt to increase model performance (Attempt 1), we decided to use two hidden layers. Layer 1 contained 90 input features & Layer 2 contained 45 features. We used the Relu activation functions. 
    - We were not able to achieve the target model performance. Our accuracy only increased by about 0.03% through the three attempts. 
    - A few steps were taken to try and increase model performance. We attempted to change the number of hidden nodes, the number of hidden layers & the activation function.

## Summary
All in all, we could not optimize the neural network model to achieve a performance of over 75% after three attempts. A few improvements we can implement in future tries to achieve our goal would be to increase the amount of Binning in our variable features. We can also increase or decrease the number of epochs. Lastly, we could try and find a different activation function to use. 