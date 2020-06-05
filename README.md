# Time Series Data Meet Up Milan - 05 June 2020

Welcome to this page where you can download all material related to the meetup presentation **Time Series Data - extracting, visualising and analysing of stock market securities**.

## Python Script

Python script is based on Jupyter Notebook and file name is: *Time_Series_Stock_Exchange_Presentation.ipynb*. It can be used without any restriction.

In order to correctly work, the script requires to install via ***pip*** the following libraries:

* datetime
* matplotlib.pyplot
* matplotlib
* pandas
* pandas_datareader.data
* json
* csv
* itertools
* elasticsearch 
* yahoo_earnings_calendar
* dateutil.parser

The part related to yahoo_earnings_calendar is not required unless you want the whole amount of data. Rememebr that you can download earning data from other sources, same for stock data records.

## Data

Here are provided all data already download, cleaned and in .csv format in case you want directly inport with Logstash or other tools/languages.

## Kibana Visualisations and Dashboards

Visualizations and dashboards are provided as saved object and are stored inside **kibana** directory. Directory contains one file named: *saved_object_kibana.ndjson*.

It is required that all indices with stock data are firstly created, the saved object includes the index patterns associated.

Name of indices used for this demo:

* netflix_index
* tesla_index
* estc_index
* okta_index
* nasdaq_index
* netflix_earning_index
* tesla_earning_index
* indeces_combined 

## In case of help

Please send a mail to **luca.gennari@elastic.co** in case of comment, notes, help or even just to have a beer!
