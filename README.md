# poultry_price_scraping_prediction
Here the data of daily prices of poultry birds of various category and markets is scraped. Sequential data is prepared from it and fed into Neural Net for Prediction of AVERAGE PRICE for next 10 days. 

# Scraping
Selenium is used for scraping data and then saved in csv files.
Scraping files are: delhi_market.ipynb & gujrat_mumbai_punjab.ipynb

# RNN
3 CuDNNLSTM layers, and a dense layer with Dropouts layers in between is used to make neural net.
