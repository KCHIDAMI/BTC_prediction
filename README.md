# BTC_prediction
BTC prediction using HRHN (Hierarchical Attention-Based Recurrent Highway Networks) model + PID (Proportional Integral Derivative) corrector + VAR (Vector Auto Regressive) predictor, on-chain and off-chain data from coinmetrics.io 

- all the data here has been extracted from coinmetrics which organizes the world’s crypto data and makes it transparent and accessible. Check their website for more information : https://coinmetrics.io/#

- for more information about HRHN for Time Series Prediction please find the description in the research paper HRHN_for_time_series

- WHY BTC ?
The data contained in the bitcoin blockchain is public and can be viewed by anyone. This information is a unique source of intelligence about the network activity in terms of user growth and transaction patterns, hence, it can provide valuable insights for assessing the supply and demand and can be a leading indicator for
future price movements. However due to the amount of data recorded everyday in the bitcoin blockchain, it is really difficult to analyze it at scale. 
The goal of this project is to extract on-chain information, combine it to market data (off-chain information as price and volume of exchanged bitcoins) and use advanced deep learning models as HRHN to find patterns in order to predict future bitcoin price movements.

part of the HRHN+PID+VAR code is from Alexandre Bourrieau amazing course (in french) in UDEMY :
- part 1 : https://www.udemy.com/course/modeles-avances-des-series-temporelles-avec-keras-partie-1
- part 2 : https://www.udemy.com/course/modeles-avances-des-series-temporelles-avec-keras-partie-2
