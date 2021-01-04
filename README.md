# Stock-Volatility-Prediction-using-Sec 8K-filings

### Overview:

* Extract meaningful information / swings in company’s stock price.
* Use SEC 8-K filings to predict stock volatility. 
* Experiment with Various Neural Network architectures.

### Data Extraction:

* Using BeautifulSoup we extracted text and submission datetime of the SEC 8-K filings from SEC Edgar website.
* Extracted historical adjusted opening and closing price for all given tickers using AlphaVantage API.
* Calculated price change before and after the release of the 8-K documents.

### Learnings:

* Finance:
  * SEC 8K Filings
  * Volatility Index
  * GSPC 

* NLP:
  * Beautiful Soup
  * GloVe
  * Large Data lemmatization
  
* Deep Learning:
  * Auxiliary Inputs
  * Bi-Directional RNN
  * GRUs

