# Challenge3Repo
The Challenge is to use data preparation techniques to clean and prepare data from two Bitcoin exchanges to better compare their price histories across a period of years.

# User Story
Role: Analyst at a high-tech investment firm.

Gaol: task is to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.

Reason: As Bitcoin trades on markets across the globe, there is a commercial basis to capitalize on simultaneous price dislocations in those markets hence management is considering arbitrage opportunities in Bitcoin and other cryptocurrencies.

# General information about the analysis.

Exchange arbitrage is a form of riskless or pure arbitrage in which the same asset trades on two exchanges with the asking price on one exchange overlapping with the bid price on another exchange.
A box plot gives us a basic idea of the distribution of the data. IF the box plot is relatively short, then the data is more compact. If the box plot is relatively tall, then the data is spread out. 

### datasets
The datasets used for this anaysis are named are
1. bitstamp DataFrame  with the beginning date of 2018:01:01 and end date of 2018:04:01
2. coinbase DataFrame  with the beginning date of 2018:01:01 and end date of 2018:04:01
The datasets were sliced into intervals for the analysis as follows
Full length of the dataset  from 2018:01:01 to 2018:04:01 to visualize the prices over the full lenth of the dataset
1 month interval - 2018-01-05' : '2018-02-05 for the price action of both DataFrames for a one month period early in the dataset

The three dates chosen for the 1 day interval arbitrage profitabilty analysis for each DataFrame are:
2018-01-17' : '2018-01-18  - early
2018-02-15': '2018-02-16'  - middle
2018-03-30' : '2018-03-31' - late

### libraries used in the analysis.
The libraries used in the analysis are:
- import pandas as pd
- from pathlib import Path
- %matplotlib inline
- import matplotlib.pyplot as plt
- import numpy as np

## Analysis
The analysis were done and the results dispalyed in 3 ways:
1. generating the date
2. plotting the individual dataframes as line plots over a time interval designated as early, middle and late
3. plotting and overlay of both DataFranes over a time interval designated as early, middle and late
4. plotting the box plots for individual dataframes as well as laying the two dataframes side by side over a time interval designated as early, middle and late