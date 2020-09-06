*** WORKING PAPER ***

The Neighborhood Dollar Index
By Michael Valentino Ochoa

# INTRODUCTION

* Chicago is a city of neighborhoods.  This paper explores how factors such a shop-to-population ratios, annual household incomes and property values are associated with neighborhood purchasing power.  It's no suprise people's neighborhoods impact their purchasing power.  Here's a look at the city's extremes.

# WHAT AM I DOING?

* This is an ambitious field experiment that estimates what the probability is of overpaying for a coffee/blunt in neighborhoods on Chicago's West and North sides. The timeliness and quality of the Blunt-Coffee index could be a helpful supplement to official city figures.

# DATA COLLECTION

* I hand collect blunt/coffee prices, dates and locations from 200+ neighborhood shops during 10 to 14 day intervals. 

# DATA PREP

* STEP 1 RawData - unformatted spreadsheet with hand collected prices 
* STEP 2 TidyDataSet - script takes raw data as input and produces tidy data as output
* STEP 3 Description - describe each variable and values in tidy data set
* STEP 4 ReproducibilityRecipe - set up calculations in a way that is easy for reproducibility

# CALCULATIONS

* I estimate what the probability is of overpaying for a coffee/blunt in neighborhoods on Chicago's West and North sides.  Then using a bit of rearrangement and the GLM function in R(programming language) I estimate the regression coefficients with the maximum likelihood function to identify the strength and direction of significant risk factors for overpayment.
* Additionally, I compute a 95% confidence intervals for the slopes / odds ratios. TLDR: that means I'm 95% sure that the odds for a chosen commercial corridor overpaying versus the city average in this model are between ___ and ___ greater than the odds for other corridor overpaying.

# EVALUATION OF DATA

# DISCUSSION

# WEB APP

* I build a digital bridge that integrates all this data to educate Chicagoans on the purchasing power of their dollar.

# REFERENCES

* An Introduction to Statistical Learning with Applications in R by Gareth James et la. 
* R Programming for Data Science by Roger D. Peng
* Business Location Decisions Class Notes from Geoffrey J.D. Hewings, University of Illinois (Fall 2014)
* Statisical Analysis Class Notes from Ellen Fireman, University of Illinois (Fall 2015)
* The Web Developer Bootcamp by Colt Steele 
