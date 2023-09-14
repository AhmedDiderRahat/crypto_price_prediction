---
Title: CRYPTO-CURRENCY FUTURE PRICE PREDICTION USING STACK LSTM
Author: Rahat, A.D.
Date: June 23rd, 2022
---

### Introduction
Cryptocurrency is a digital currency in the modern finance system. It’s an end-to-end system, enabling anyone anywhere to send and receive payments. Instead of physical money carried around and exchanged in the real world, cryptocurrency payments exist purely as digital entries in cyberspace. As a result, the interest in crypto investment increased dramatically. In this project, I try to implement stack LSTM to predict the future price of the two most widely used cryptocurrencies, BITCOIN and ETHEREUM.

### Project Goal:
This project is the part of Deep Learning course during the summer semester of 2022. The main goals of the project are:
  1. Implement an LSTM model to predict the future price of Bitcoin and Ethereum.
  2. Calculate the RMSE value.
  3. Choose the best parameter using hyper-parameter tuning.


### Project Report: 
The full report of this project is stored in this [link](https://github.com/AhmedDiderRahat/crypto_price_prediction/blob/main/documentation/report.pdf)


### Conclusion: 
As cryptocurrencies are highly dependent on other factors (like world politics, socio-economic situation, or even some Twitter posts), it is too difficult to predict the future price only with previous data. But if we look at the data, there may be some points.
  1. For the Ethereum data set, the best accuracy was gained when I used the parameter (time = 7 days, LSTM unit = 64, epochs = 100, batch size = 16).
  2. Using different parameters (on the Ethereum data set), the RMSE value for test data is too high. But the shape of the prediction is pretty much similar to the actual value except (fig-22, fig-26, fig-30, fig-34, fig-38, and fig-42), where I used (epochs = 500, batch size = 16).
  3. For Bitcoin the test RMSE value is huge 2392.9758 When applying the parameter (time = 14 days, LSTM unit = 128, epochs = 100, batch size = 64). But in the maximum case, the actual price and predicted price have almost the same shape except (fig-51, fig-54, fig-58, fig-62, fig-66).
