*** WORKING PAPER ***

# INTRODUCTION

* Chicago may be a single market, but its products do not have single prices. Some price differences are inevitable.  Goods downtown will cost more than ones in neighborhoods on the city's edge. My question is: how much do prices vary across the city? 

# WHAT IS IT?

* The Corner Store Index uses the price of select goods to compare the values of ones dollar across the city.  Its calculations  shows how social and environmental factors relate to neighborhood purchasing power.  It's a look at the city's extremes.

# WHY AM I DOING THIS?

* This is an ambitious field experiment that estimates what the probability is of overpaying for select goods in corner stores on Chicago's West and North sides. The timeliness and quality of the Corner Store Index could be a helpful supplement to official city figures.

# WEB APP

* Generate a color gradient map with a searchable tile-based interface of data sorted by luminance, from least to most bright (to represent the value of a dollar across the city) 

# DATA COLLECTION

* All price data is collected in-person during 10 to 14 day intervals from approximately 150+ neighborhood corner stores.

# DATA PREP

* STEP 1 RawData - unformatted spreadsheet with hand collected prices 
* STEP 2 TidyDataSet - script takes raw data as input and produces tidy data as output
* STEP 3 Description - describe each variable and values in tidy data set
* STEP 4 ReproducibilityRecipe - set up calculations in a way that is easy for reproducibility

# CALCULATIONS

* I estimate what the probability is of overpaying for a select goods in neighborhood corner stores on Chicago's West and North sides.  Using a bit of rearrangement and the GLM function in R(programming language) I estimate the regression coefficients with the maximum likelihood function to identify the strength and direction of significant risk factors for overpayment. I also compute a 95% confidence intervals for the slopes / odds ratios. TLDR: I'm 95% sure that the odds a location is overpaying versus the city average are between ___ and ___ greater than the odds for other locations are overpaying

# DATA EVALUATIONS

# DISCUSSION

# REFERENCES

* An Introduction to Statistical Learning with Applications in R by Gareth James et la. 
* R Programming for Data Science by Roger D. Peng
* Business Location Decisions Class Notes from Geoffrey J.D. Hewings, University of Illinois (Fall 2014)
* Statisical Analysis Class Notes from Ellen Fireman, University of Illinois (Fall 2015)
* The Web Developer Bootcamp by Colt Steele 
