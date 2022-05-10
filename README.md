# LSTM_stock_price_predictor
This project seeks to show the efficacy of the LSTM (Long Short Term Memory) RNN model in predicting stock prices on the S&amp;P 500, based on training done on historical data done on the past 20 years.

![image](https://user-images.githubusercontent.com/60477228/167581006-2d633c56-d7a4-4402-99c2-fdbcc1bdfe05.png)


### Objectives of the project:
- Using this predicting model, we wish to predict the price patterns of stocks on the S&P 500 and predict the movement of a user’s portfolio based on this historical data.
- We seek to show that the LSTM Model can predict price patterns more efficiently than other technical indicators like 1 Year or 2 Year Moving Averages and the Buy and - Hold methods of stock picking and recommend whether to buy or sell stocks based on the predicted movement of the stocks provided by the algorithm.
- See how changing the window size alotted to the LSTM Model (the amount of long term information the model should remember) affects the accuracy of the Model's results and whether it will gain better profits.

#### What is LSTM?
LSTM is a type of recurrent neural network but is better than traditional recurrent neural networks in terms of memory. Having a good hold over memorizing certain patterns LSTMs perform fairly better. As with every other NN, LSTM can have multiple hidden layers and as it passes through every layer, the relevant information is kept and all the irrelevant information gets discarded in every single cell.

#### Functioning of a LSTM
![image](https://user-images.githubusercontent.com/60477228/167577277-25836682-eef4-42a5-a375-c3dc9201d118.png)

![image](https://user-images.githubusercontent.com/60477228/167577440-a4397a05-78d9-4bea-a5df-c3fc6a149088.png)


### Results
We have found that the LSTM Model performs significantly higher than other technical indicators.
- Value predicted by the models:
![image](https://user-images.githubusercontent.com/60477228/167579441-a69f21e5-f42e-4797-8bd9-2979804b7f13.png)
- The buying and selling movements made by the algorithm based on the LSTM Model:
![image](https://user-images.githubusercontent.com/60477228/167579635-55839f20-24a2-4f6d-80f9-633282fb82e8.png)
- Value of the hypothetical portfolio compared to other popular stock buying strategies:
![image](https://user-images.githubusercontent.com/60477228/167579873-c9ea7fbf-8647-4508-8654-02d81a943b37.png)

### Conclusion
- We can see that our predictor model performs twice as good as the traditional buy and hold strategy.
- And not just that, our predictor model also performs better when more long term information is remembered by the LSTM model!

#### Closing notes
The code for the project is given in our .ipynb file in the github repository.
The Project Presentation Report we submitted to our univeristy professors is also given in the repository.

Thanks for reading 😊


