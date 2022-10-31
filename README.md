# Monte-Carlo-Simulation

The purpose of this project is to create a Monte Carlo simulation, using two different portfolios that have different stock allocation, to see which would be the better investment for retirement. Also, looking through current finances to see if the individual has enouh money in their savings for an emergency fund. 

## Technologies

In this challenge, I am using os, requests, json, pandas, dotenv, MCForecast Tools, and the Alpaca API.


## Installation Guide

import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

## Usage

I was able to create two simulations. One is a 30 year simulation with more of an even balanced portfolio, and the other is a 10 year simulation with a more heavy weight in stocks. I am able to generate the summary statistics, graphs, and other relivent information to make an educated investment decision based on this.

## Contributors

I was the main contributor for this project!