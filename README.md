# FXCM_currency

Using SVM model to predict and trade currencies. Currently it is on fixed/static time prediction (next bar), improvements will be used for varying forward time window predcition(Instead of using 5 min bars to predict the next 5 mins, aim to predict  longer ahead)
Example: https://github.com/SolbiatiAlessandro/RNN-stocks-prediction (dynamic prediction).

Also will aim to look at or account for variable change in prediction, say you in are currently in a trade but new data (or news) comes in suggesting that the current prediction is no longer accurate (try to minimise position or close out the current position).



Documentation for FXCM API: http://fxcmpy.tpq.io/

Adpated from : http://hilpisch.com/fxcm_ai.html

Download or install jupyter notebook to view files

Add your token from FXCM to the fxcm.cfg to start trading

Unique implimentation of this is binning the data according to voltility 
