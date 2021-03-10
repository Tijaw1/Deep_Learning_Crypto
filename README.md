# Deep_Learning_Crypto

This program evaluates deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data. 

The program runs the two models independently and compares the loss from each and determine which model provides a better result based on the loss value (both mosels use the same parameters for training steps). Each model will need to use 70% of the data for training and 30% of the data for testing.

Based on the observations from the model evaluation:
- FNG model has a higher loss average than the simple closing model.
- Simple closing model tracks the actual value better overtime. 
- A window that is less 10 (around 5) appears tp work better for both models. The 