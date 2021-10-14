# Deep-Learning

- Using deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.


## Prepare the data for training and testing
- Prepared data for training and testing by using 70% of the data for training and 30% for testing for all model.
- The previous closing price will be use to predict the next closing price.
- MinMaxScaler to the X and y values to scale the data for the model.

Build and train custom LSTM RNNs

![image](https://user-images.githubusercontent.com/80086711/137254563-921c7572-081c-4831-91de-db30dbf602a8.png)

## Evaluating the performance of each model

- For the following, 
* Which model has a lower loss? 
* Which model tracks the actual values better over time?
* Which window size works best for the model?

- ![image](https://user-images.githubusercontent.com/80086711/137254631-d1e0993b-d734-4b75-a18c-48c6cfa6d67e.png)

## Plotting of the real vs the predicted

![image](https://user-images.githubusercontent.com/80086711/137255040-4c59e27a-c709-4c82-85da-b5568b55e1ff.png)



