# Python Stock Analyser
This is hand-crafted python webapp project, built with Pandas and Scikit-learn frameworks as data analyzing tools, AmCharts as visualization tool and with Flask python backend.
This stock analyser plays the role of data entry and center at the same time.

Usage:

1. Download latest miniconda version and install it on local os.
2. Set up python enviroment for running the app.
```
$ pip install -r requirements.txt
$ export FLASK_APP=app.py
$ flask run
```

## WebApp Usage:

### Once in webapp input stock symbol you want to analyze, then select start date and end date, be weary of date selection for every stock. App is using Pandas_DataReader to retrieve the data. After hitting submit, you'll be presented with a beautiful AmCharts graph.

## TODO:

#### * Create APIs for data processing instead of running the whole logica app for the data process
#### * Create other views for data analysis
#### * Make the top bar work correctly, returning the data to the ORIGIN request


***This is beta software so remember everything might probably come crashing down...

Made with ❤ by KhanovicAI