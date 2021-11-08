# TECHNICAL SCREENER FOR INDIAN MARKETS

---


> In this technical screener, you select a pattern to recognize and then the screener does its magic by finding stocks which show that particualr pattern for last trading day.


### DEPENDENCIES

1. [Pandas](https://pypi.org/project/pandas/)
2. [Yahoo Finance](https://pypi.org/project/yfinance/)
3. [Flask](https://flask.palletsprojects.com/en/1.1.x/quickstart/)
4. [TA-Lib](https://mrjbq7.github.io/ta-lib/index.html)

#### Instructions for TA-Lib installation on Windows
[Install TA-Lib](https://blog.quantinsti.com/install-ta-lib-python/)


### DATASET

The dataset contains daily data on all the companies listed on NSE for a period of 10 months from 2020-08-26 to 2021-06-26.

### HOW TO RUN

1. First start the flask server using command 

> flask run

2. Open localhost:5000 in your browser of choice.

#### Difficulties while running flask server

Most likely the problem is with setting the environment variables.
On Windows :
            To run the code in development mode use the following command
> $env:FLASK_ENV="development"  


OR 


> set FLASK_ENV="development"

            To enable debugging

> $env:FLASK_DEBUG=1

            To disable debugging

> $env:FLASK_DEBUG=0

