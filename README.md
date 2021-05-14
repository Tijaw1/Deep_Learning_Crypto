![DeepLearning_Crypto](https://github.com/Tijaw1/Deep_Learning_Crypto/blob/main/DeepL_Crypto.jpg)

# Deep_Learning_Crypto

Cryptocurrency, such as Bitcoin is currently a thriving open-source community and payment network, which is currently used by millions of people. As the value of Bitcoin varies everyday, it would be very interesting for investors to forecast the Bitcoin value but at the same time making it difficult to predict. Bitcoin is a cryptocurrency technology that has attracted investors because of its big price increases.

Deep learning represents the best opportunity for building robust predictive models for crypto assets. From many angles, crypto seems to be like the perfect asset class for deep learning-based quant models. That’s because of the  the digital DNA and the transparency of crypto assets and that the rise of crypto has coincided with a renaissance of machine learning and the emergence of deep learning.

This program evaluates deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data. 

The program runs the two models independently and compares the loss from each and determine which model provides a better result based on the loss value (both mosels use the same parameters for training steps). Each model will need to use 70% of the data for training and 30% of the data for testing.

Based on the observations from the model evaluation:
- FNG model has a higher loss average than the simple closing model.
- Simple closing model tracks the actual value better overtime. 
- A window that is less 10 (around 5) appears tp work better for both models. The 
