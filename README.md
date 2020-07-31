# Stock Market Prediction Project
CAP5610 Final Project: Deep Learning for Tesla Stock Price Prediction 
 
Abstract 
 
The main focus of this project is to see if we are able to predict the price movements of a single stock. For this project, we will be observing Tesla and be using deep learning and deep neural network techniques.  
 
Introduction and Problem Statement 
 
We know that investing in individual stocks in the market involves a certain risk because it has to do a lot with price prediction. The problem that we have is that as humans there is a big margin for human error. 
 
Using machine learning, we could potentially see how the market will perform in a day without the human error factor. Therefore, we could predict how a stock like Tesla will perform over an allotted time. 
 
Motivation 
 
Due to the recent fluctuations in the market, we decided it would be smart to see how well a machine would be able to predict the movements of a singular stock, to then be able to apply it to multiple stocks to improve portfolio diversity and maximize profit. 
 
Hypothesis 
 
We should be able to predict the movement of the stock with a relatively reasonable percentage, and able to predict the magnitude of the movement at times.  
 
Methodology 
 
In order to predict the stock market, we will be doing the following: 
 
1. Design a model using LSTM and Deep Neural Networks. 
2. Use a service like Alpha Vantage to acquire data concerning the Tesla stock. 
3. Prepare the data set for processing. 
4. Develop the model in Python 
5. Train the model 
6. Evaluate how well the model can predict the movements of the market. 
7. If necessary, make improvements based on results and train again. 
 
Expected Results 
 
We expect to predict the stock price movement of Tesla over time with a successful prediction rate of 65% or more. 
 
Related Work 
 
● Deep Learning for ETF Price Prediction: This project used Long-Short Term Memory(LSTM) and Convolutional Neural Network (CNN) models on ETFs to predict future one week prices of stocks (see reference). 

● Stock Prices Prediction using Deep Learning Models: Long Short Term Memory cells are like mini neural networks designed to allow for memory in a larger neural network. This is achieved through the use of a recurrent node inside the LSTM cell (see reference). 
 
● Stock Prices Prediction using Deep Learning Models: Long-short term memory (LSTM) is then used to predict the stock price. The prices, indices and macroeconomic variables in the past are the features used to predict the next day’s price. It compares the performances of models with two different forecast targets of stock price: absolute stock price and price rate of change. The results show that predicting stock price through price rate of change is better than predicting absolute prices directly (see reference). 
 
● A Machine Learning Model for Stock Market Prediction: This paper proposes a machine learning model to predict stock market price.  The proposed  algorithm integrates  Particle swarm  optimization  (PSO)  and  least  square  support  vector machine (LS-SVM). The PSO algorithm is employed to optimize LS-SVM  to  predict  the daily  stock  prices.  Proposed  model  is based  on  the  study  of  stocks  historical  data and  technical indicators (see reference). 

Running the Code:

1. Clone the repository 
2. If using miniconda, create an enviornment by doing "conda create --name stocks python=3.7" Python 3.7 is needed to install the packages necessary for the project.
3. Upon creating the enviornment, do "pip install -r requirements.txt"
4. If going to use jupyter notebook, "pip install jupyter", and open jupyter notebook.
5. Run the TeslaMovementPrediction.ipynb file and observe the code working.

(If there are issues with runnign 