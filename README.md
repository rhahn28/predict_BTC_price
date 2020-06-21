# LTSM BTC price predictor



## Deep Learning

The code uses LTSM deep learning model from the Keras library to predict BTC prices. Two approaches are taken. The first is using just BTC close prices and applying LTSM. The second approach uses both BTC closes prices and a BTC fear and greed index (fng). https://alternative.me/crypto/fear-and-greed-index/

## Data

Data starting from Feb. 1, 2018 was collected from yahoo finance. That date was selected for symmetry with the earliest data point for the BTC FNG index, which is Feb. 1, 2018. 

## Closing price

Using various numbers of epochs and window sizes, the closing price model accurately predicted the prices, however 1 day later. Therefore, as a prediction model, the algoritm would seem to have little utility, since it is always predicting well after the fact.

## FNG index

The FNG index did a fairly good job of predicting price swings up until 20 days ago, which coincides with the exepcted halving event in BTC. The large swings show the inability of past FNG data to accurately predict during highly speculative times. 



