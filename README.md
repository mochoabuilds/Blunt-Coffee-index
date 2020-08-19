*** WORKING PAPER ***

# INTRODUCTION

* This repository contains coffee/blunt prices, code for multiple logisitc regression and a web app.  

# DATA COLLECTION & CALCULATIONS

* My research collects dates, locations and blunt/coffee prices from 200+ neighborhood shops during 10 to 14 day intervals. Next, I estimate what the probability is of overpaying for a coffee/blunt in a neighborhood with property values and annual household incomes of X.  Using a bit of rearrangement and the GLM function in R I estimate the regression coefficients with the maximum likelihood function. The goal is to identify the strength and direction of significant risk factors for overpayment.

# INPUT DATA 

* date (MM/DD/YYYY)
* street_block
* blunt_price
* coffee_price
* property_values
* annual_income

# TRIALS

# DISCUSSION

* My goal is direct an ambitious field experiment that addresses the urban problem of predatory pricing. The timeliness and quality of the Blunt-Coffee index could be a helpful supplement to official city figures.

# WEB APP

* Build a digital bridge that integrates all this data to educate the public on the purchasing power of their dollar.

# REFERENCES

* An Introduction to Statistical Learning with Applications in R by Gareth James et la. 
* R Programming for Data Science by Roger D. Peng
* Business Location Decisions Class Notes from Geoffrey J.D. Hewings, University of Illinois (Fall 2014)
* Statisical Analysis Class Notes from Ellen Fireman, University of Illinois (Fall 2015)
* The Web Developer Bootcamp by Colt Steele 
