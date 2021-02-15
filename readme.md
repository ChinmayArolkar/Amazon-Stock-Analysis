Performed Analysis on Amazon Stock and built various predictive models and built Trading Strategies using Python3

The models incorportated are as follows:

1. Garch

2. Kalman Filter

3. Mixed Data Sampling (Midas)

Note: Mixed Data Sampling was infered from https://github.com/mikemull/midaspy

4. Moving Average

5. Random Forest

6. Ensemble Model combination using Random forest ( Autoregression, Fama French Regression, Moving Average)

The Trading Strategies were:
1. Buy and hold 
      - If prediction > yesterday’s close price -> buy;
      - If already bought -> hold
      - Else sell  
2. Long and Short 
      - If predicted > yesterday’s close price -> go long  else go short 
3. Day/Month/Quater Trading 
      - If predicted > yesterday’s close price -> buy it at open and sell at close 
      
      
      
PLEASE REFER PDF FOR UNDERSTANDING



