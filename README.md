# 11-challenge
Find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.


## Technologies
* import pandas as pd
* import holoviews as hv
* from fbprophet import Prophet
* import hvplot.pandas
* import datetime as dt
* import numpy as np
* %matplotlib inline


## Installation Guide
Using the Conda package manager: [My GitHub Project](https://github.com/ALovettII/11-challenge.git)

Installing Prophet may be difficult on some computers. Thus for for this project, I used Google Colaboratory
For proper installation, the following libraries are installed at the beginning of the Notebook: 

```Python
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews
```


## Usage
Running this program will provide the following for MercadoLibre ($MELI):
* Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
* An evaluation of how the company’s stock price correlates to its Google Search traffic.
* A Prophet forecast model that can predict hourly user search traffic.
* A plot of a forecast for the company’s future revenue.

If search traffic analysis of other companies is preffered: 
* Adjustments will need to be made on the data imports (found @ the beginning of each step)
* Ensure proper format compliance
* Adjust any related labels

The project will produce results similar to these:
![Seasonality Analysis - Weekday vs Hourly Heatmap](https://github.com/ALovettII/11-challenge/blob/main/screenshots_readme/wk-day_szn-htmp.png)
![Seasonality Analysis - Prophet](https://github.com/ALovettII/11-challenge/blob/main/screenshots_readme/trends_szn.png)
![Search Traffic Forecast - Prophet](https://github.com/ALovettII/11-challenge/blob/main/screenshots_readme/trends_forecast.png)
![Prediction Confidence - Prophet Components](https://github.com/ALovettII/11-challenge/blob/main/screenshots_readme/plot-components.png)
![Final Revenue Forecast - Prophet](https://github.com/ALovettII/11-challenge/blob/main/screenshots_readme/forecast-layman.png)


## Contributors
Created by Arthur Lovett