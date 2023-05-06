# Autonomous-Trading-Agent-using-Deep-Q-Learning-and-Transformer-Networks
# https://www.youtube.com/watch?v=Rc3A5W88oYU

Our repository consists of 3 python notebooks and csv files.

Csv Files: 
    1. AAPL.csv, AXP.csv, DIS.csv, GS.csv, IBM.csv, MSFT.csv, NKE.csv, PG.csv, QCOM.csv, RTX.csv <br>
    01/01/2010-->04/30/2023, Prices <br>
    2. AAPL_Pred.csv, AXP_Pred.csv, DIS_Pred.csv, GS_Pred.csv, IBM_Pred.csv, MSFT_Pred.csv, NKE_Pred.csv, PG_Pred.csv, QCOM_Pred.csv, RTX_Pred.csv <br>
    01/01/2010-->04/30/2023, Predicted Prices <br>

Python Notebooks:
    1. StockPredictionTransformer_LongSequences - This contains code for how to use Transformer Netwrok to generate predictions for AAPL <br>
    1. StockPredictionTransformer_Multiple - Code for Transformer Netwrok trained on multiple stocks and generates multiple future stock prices to be fed into the Deep-Q Network. <br>
    2. DQNTrading - This folder contains code for the Deep Reinforcement Learning Agent trained and tested on JPMorgan's stock integrated trading signal reward shaping. 

<img src="/DQN.png" alt="DQNetwork"/>
