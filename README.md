# Stock Market Prediction

## Methods tried out
- Wiener Filter
- Least Mean Square Filter
- Recursive Least Squares Filter
- Kalman Filtering

```filters.ipynb``` has the implementation of each filter. 

```WallStreet.ipynb``` uses the Kalman filter with a moving average filter combined with a trading strategy to perform stock market trading. 

THe data used was obtained from Yahoo finance, of 27 companies across 5 years. The first 90% of the data is used as training and the remaining 10% is used as testing. 