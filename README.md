# StockMarketPrediction

> Cracking the Code: Stock Market Prediction

The stock market, and particularly stock price prediction is an area that draws significant attention from researchers and practitioners alike. Traditional methods for time-series forecasting such as **_Autoregressive (AR)_**, **_Autoregressive Moving Average (ARMA)_**, and **_Autoregressive Integrated Moving Average (ARIMA)_** models have played a significant role in this aspect. These approaches depend on predefined mathematical equations to model univariate time-series and have been widely accepted due to their simplicity and interpretability.

Nevertheless, *AR*, *ARMA*, and *ARIMA* have inherent limitations, making them unsuitable for capturing latent dynamics that characterize financial time series data. One limitation is that a model identified for one time-series does not generalize well to others, reducing its versatility. In addition, they struggle to identify intricate patterns embedded in the data, limiting their effectiveness.

---

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)	![GitHub License](https://img.shields.io/github/license/shortthirdman/StockMarketPrediction?style=for-the-badge)	![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/shortthirdman/StockMarketPrediction?style=for-the-badge)	![GitHub repo size](https://img.shields.io/github/repo-size/shortthirdman/StockMarketPrediction?style=for-the-badge)	[![Static Badge](https://img.shields.io/badge/Jupyter_Notebooks_Python3-1-brightgreen?style=for-the-badge&logo=jupyter&logoSize=auto&label=Jupyter%20Notebooks%20(Python3))](/notebooks)

---

### Local Development

  - Create a Python virtual environment and activate
	
	```shell
	$ python -m venv --upgrade-deps --clear dev
	$ export PIP_CONFIG_FILE="pip.conf"
	```
 
	```shell
	# PowerShell
 	$ .\dev\Scripts\Activate.ps1
	
	# Linux/macOS
	$ source dev/bin/activate
	
	# Windows Command Prompt
    $ .\dev\Scripts\activate.bat
 	```

  - Install the packages and dependencies as listed in requirements file
	
	```shell
	$ pip install -U -r requirements.txt --no-cache-dir --disable-pip-version-check
	```

  - Start your development `Jupyter Notebook` or `Jupyter Lab` server
	
	```shell
	$ jupyter lab --notebook-dir=.\notebooks --no-browser
	```

  - Install the below packages to run the Python script
  
    ```shell
	$ pip install -q numpy pandas matplotlib yfinance vectorbt
	```

---