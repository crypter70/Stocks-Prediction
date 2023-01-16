# Stocks Analysis and Forecasting
 
## Overview
A Machine Learning project to forecast stock prices using the Long-Short Term Memory (LSTM) algorithm. The forecasted stocks consist of 4 stock codes on the Indonesia Stock Exchange (IDX), 2 stocks each in the banking sector, namely BBCA and BBNI, the mining sector, namely ADRO and INDY.

## Prerequisite
- Anaconda 3
- Python 3

## Installation
### Installing library for crawling data (yfinance)
    pip install yfinance
    pip3 install yfinance

### Installing library for forecasting (Keras and TensorFlow)
#### Keras
    pip install keras
    pip3 install keras

#### TensorFlow
    pip install tensorflow
    pip3 install tensorflow

#### TensorFlow using Conda
If you found issue with kernel after installing tensorflow using pip, then you can install using conda as follows below(creating a new environment is recommended). 

    conda install tensorflow

## Result
- BBCA

RMSE = 234.38500392654765

![1](https://user-images.githubusercontent.com/74947224/212746856-3b3266e7-1c3d-4a88-b61d-eeef97d4cba4.png)

- BBNI

RSME = 366.55772131988164

![2](https://user-images.githubusercontent.com/74947224/212746878-ab0823aa-997d-41c8-a56d-fbdb45f0a36a.png)

- ADRO

RMSE = 110.05313726697713

![3](https://user-images.githubusercontent.com/74947224/212746895-222b231e-a6ac-4785-945e-517f2b2a4629.png)

- INDY

RMSE = 90.1968382033163

![4](https://user-images.githubusercontent.com/74947224/212746905-ce0b2be2-ce2c-434b-bbaa-855d17d015e8.png)


