# Traffic Volume Forecasting using RNN-LSTM
 This project was a part of the Neural Network and Deep Learning final at DePaul University setup as a Kaggle competition. A neural network is developed to forecast traffic volume using data from Minnapolis-St.Paul.

## Description:
The goal of this project is to develop a neural network that takes 6 timesteps as input and predicts traffic volume 2 timesteps into the future.
The data used in this project was recorded hourly so the network will take as input 6 hours of consecutive data and predict traffic volume 2 hours from the end of that data.
The original results of this project finished 8th out of 46 in a Kaggle competition.
The notebook includes a description of the project and task, description and exploration of the data, data cleaning, preprocessing, model setup, and model evaluation.

## Data:
Traffic Time Series Dataset
Author: John Hogue Social Data Science & General Mills
Description: Hourly Interstate 94 Westbound traffic volume for MN DoT ATR station 301, roughly midway between Minneapolis and St Paul, MN. Hourly weather features and holidays included for impacts on traffic volume.
Samples: > 48,000
Features: 9
Target Variable: traffic_volume