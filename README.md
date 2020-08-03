*** WORKING PAPER ***

# INTRODUCTION

* This repository contains the data for the Blunt index, and code for its calculations. My research collects blunt prices from more than 100 stores during five to seven days intervals. I then estimate the probability a store would price a blunt above the median area price using logistic regression and 5000+ labeled examples.  From this I create the adjusted Blunt index, that's relative to the income per person in that area. This price index signals where purchasing power is changing across a city.

# SOURCE DATA

* Price data comes from comes from commerce corridors in Chicago's neighborhoods; socio-economic data comes from Social Explorer reports.

# OUTPUT DATA

Variables
* date
* local_price
* street_block
* census_tract
* zip_code
* BLUNT_adjusted - Adjusted index, relative to the income per person in area

# CALCULATING THE BLUNT INDEX

* The code is provided as a Jupyter Notebook.  Code is written in Python.  To run the notebook requires a little setup.

# DISCUSSION

* Based on results I argue that the relative ease and low cost of data collection could serve as a way of keep track of changes in city purchasing power across neighborhoods, as they happen, rather than in unknown intervals.  

# BIBLIOGRAPHY
