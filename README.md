# Dissertation
## 1 File List

## 1.1 Data Files
Euro.xlsx: Input data for European VIX prediction, sourced from STOXX, covering the period from 1999/1/4 to 2024/6/7
 
India.xlsx: Input data for Indian VIX prediction, sourced from NSE (National Stock Exchange of India), covering the period from 2008/3/4 to 2024/6/6
 
Korea.xlsx: Input data for Korean VIX prediction, sourced from KRX (Korean Stock Exchange), covering the period from 2009/6/8 to 2024/6/7

USA.xlsx: Input data for American VIX prediction, sourced from WRDS database, covering the period from 1990/1/3 to 2024/6/7


## 1.2 Code Files
Euro.ipynb: Code for predicting European VIX

India.ipynb: Code for predicting Indian VIX

Korea.ipynb: Code for predicting Korean VIX

USA.ipynb: Code for predicting American VIX


## 2 Content of Code Files
Table of Contents
#2.1 Prework

Visualisaton for IV and HV

Summary statistics 

Data visualization

Stationarity check

Performance metrics

#2.2 Build Model

Split trainning and testing dataset using VIX

Benchmark - Multi-Layer Perceptron (MLP))

Build the ARIMA model using IV

Build ANN model - LSTM

Build ANN model - GRU

Build LSTM-ARIMA model

Build ARIMA-LSTM model

Build GRU-ARIMA model

Build ARIMA-GRU model

#2.3 Strategies

Combine models prediction results

Evaluation method: index metrics
